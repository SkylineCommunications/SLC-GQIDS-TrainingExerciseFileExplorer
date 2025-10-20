# Training Exercise GQI Ad Hoc Data Source

## Description

The goal of this exercise is to create a GQI (Generic Query Interface) ad hoc data source which can be used to get the file list from the DataMiner server.

The ad hoc data source must have these input arguments:
* Path (string, default: C:\Skyline DataMiner\Documents\DMA_COMMON_DOCUMENTS)
* Search Pattern (string, default: \*.\*)
* Recursive: Specifies whether the search operation should include only the current directory or all subdirectories (boolean, default: False)

The ad hoc data source returns a list of files with these fields:
* File Name
* Path
* Created
* Last Modified
* Size
* Type
* Read Only

![image](https://user-images.githubusercontent.com/110403333/218708219-fa58076d-bdc7-4a22-9df5-1d492a8274e1.png)

![image](https://user-images.githubusercontent.com/110403333/218708735-027ceb48-8d5f-4ac0-bfff-f3c7afb79e21.png)
