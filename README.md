# **Fuel Efficiency of Battery-Electric Vehicles**
By Jackie Jiang, Jonah Baayen, Rija Baig, and Saawi Baloch.

---

### **Introduction**
This paper will go over the fuel consumption statistics of newly-released vehicles available for sale in Canada from 1995 to 2014.

The data being analyzed was published by Natural Resources Canada, and contains data that includes but is not limited to the vehicle model, class, consumption, and emissions. By working with this data, it is possible to determine which vehicles are the most-efficient in terms of fuel consumption, and use this to improve performance going forward.

### **Discussion**
There are a number of metrics that can be used to judge the efficiency of a vehicle, so it is important to analyze all of them.

Vehicles will be analyzed based on their metrics involving:
- Range on a single fully-charged battery (in km)
- Combined City + Highway Fuel Consumption (kWh)

#### **Range:**

Different classes of vehicles are designed to travel different distances, so analysis of range will be split-up by class.
Below are the top-5 vehicles in terms on range for each vehicle class:

*Subcompact*:

![image](https://user-images.githubusercontent.com/90221511/144763091-e151b7ac-8764-4a7b-aa19-d0306654b5d7.png)

*Mid-Size*:

![image](https://user-images.githubusercontent.com/90221511/144763104-1651f3c0-5c51-4e82-b214-3ecc9310b7dd.png)

*Compact*:

![image](https://user-images.githubusercontent.com/90221511/144763112-2125f5e9-1bd0-40e3-97a7-2bfca83ffe21.png)

*Full-Size*:

![image](https://user-images.githubusercontent.com/90221511/144763118-128e953a-4355-4a9f-b148-d6aeb94e3e70.png)

*Station Wagon*:

![image](https://user-images.githubusercontent.com/90221511/144763132-d4940b14-20cb-4a27-be12-b43047d7a25a.png)

*SUV: Standard*:

![image](https://user-images.githubusercontent.com/90221511/144763141-f813b086-0cef-4116-bd80-cd9f2c73e6be.png)

*SUV: Small*:

![image](https://user-images.githubusercontent.com/90221511/144763146-f78738bf-e6b5-461f-8e5e-bbb8b04a66a6.png)

The first thing to notice in the data is that, with a single exception by Chevrolet in the Station Wagon class, a single manufacturer is responsible for all top-5 vehicles in each respective class.

**BMW** is the top manufacterer in terms of range for Subcompact vehicles, **Porsche** for Compact vehicles, **Smart** for Two-Seater vehicles, **Ford** for Station Wagons, and **Tesla** for Standard SUVs, Small SUVs, Full-Size, and Mid-Size vehicles. An important takeaway is that while every other manufacterer only dominates in a single class, **Tesla** produces the most range-efficient cars in four categories. At a first glance, it is easy to assume that Tesla is therefore the best manufacterer, however this will be looked into deeper later in the paper.

Another thing to notice is that different variations of the same model count as seperate vehicles in the dataset. An example of how this affects the results of this analysis is that, looking at the Subcompact data for example, all the models are either BMW i3 or BMW i3s from different years. While they are technically different models and are indeed the top-5 most efficient vehicles in their class, they have identical ranges despite being from a range of 2 years, indicating no actual _improvement_ over time. This concern does not apply to most other categories, with the only other manufacterer suffering from this problem being 'smart' in the Two-Seater class.

From this analysis of the range efficiency, the main takeaway is that the best manufacters seem to have a tendency to find a vehicle class they are good at and stick to it, with the exception being Tesla who has spread out into multiple classes.

#### **Fuel Consumption**
