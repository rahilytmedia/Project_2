Import Amazon_fashion_data file and open as transform in the power query editor


so lets correct image url first, if you click on the column data you will notice at the bottom status bar there is | character between two image urls

lets split two image urls into columns

Go to Large column and right click put | and select "Left most delimiter" click ok

now you have two column of image urls
choose first column which have only single image url

we will remove another column

but first lets check other columns which have some issues

Now go to Category column and you will notice category names doesnt have space so first add space between names

Right click and split "Lower to Uppercase" and you will get three Categories columns

You will get some "null" values in the categories 2 & Categories 3 column so replace null values as blank

![Alt Text](https://raw.githubusercontent.com/rahilytmedia/Project_2/refs/heads/main/ssss.png)

