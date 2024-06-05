### SIT744 Deep Learning ~ *Sharath Vijayananda* 

# Recycling Dataset 
 

This is a dataset repository for my assignment project in SIT744 Deep Learning. <br/>

I have curated the data from different source, selectively choosing and altering them as required for the unit and learning purposes. 

For the purposes of I have used 5 classes: 
Cardboard, Glass, Metal, Paper, Plastic 

### Original_Data 
* **Cardboard:** *461* <br/>
* **Glass:** *420* <br/>
* **Metal:** *790* <br/>
* **Paper:** *500* <br/>
* **Plastic:** *921* <br/>

### NewSrcTest  
* **Cardboard:** *42* <br/>
* **Glass:** *48* <br/>
* **Metal:** *42* <br/>
* **Paper:** *47* <br/>
* **Plastic:** *61* <br/>



I plan to split the Original_Data for training,validation,test splits with a 70% - 20% Train+Val - Test and 75% - 25% Train - Val splits, and NewSrcData for additional testing. 

I plan to incorporate a few of my own images in combination with the NewSrcData and evaluate the model again. 

Additionally, I plan to test on extreme cases such as images with blur, noise, various light and exposure levels, etc., and also incorporate non-recyclable classification as well. <br/>
<br/>
## Source: 

* **data/original_data : IEEE Dataport: RealWaste** <br/>
Sam Single, Saeid Iranmanesh, Raad Raad, December 22, 2023, "RealWaste", IEEE Dataport, <br/> doi: https://dx.doi.org/10.21227/65m5-rr72.

* **data/newsrcdata : Roboflow Universe: garbage dataset** <br/>
Open Source Data, February 1, 2022, "garbage dataset", Roboflow Universe, Roboflow, <br/> url: https://universe.roboflow.com/new-workspace-jpl4j/garbage-nwdk6 


