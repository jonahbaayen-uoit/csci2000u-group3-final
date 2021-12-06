# **Fuel Efficiency of Battery-Electric Vehicles**
By Jackie Jiang ([JackTop325](https://github.com/JackTop325)), Jonah Baayen ([jonahbaayen](https://github.com/jonahbaayen)), Rija Baig ([rijabaig](https://github.com/rijabaig)), and Saawi Baloch ([saawibaloch13](https://github.com/saawibaloch13)).

---

### **Introduction**
This paper will go over the fuel consumption statistics of newly-released vehicles available for sale in Canada from 2012 to 2021.

The data being analyzed was published by [Natural Resources Canada](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64), and contains data that includes but is not limited to the vehicle model, class, consumption, and emissions. By working with this data, it is possible to determine which vehicles are the most-efficient in terms of fuel consumption, and use this to improve performance going forward.

---

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

The technology behind vehicles is expected to improve overtime as more technological advancements are made, so the consumption will be analyzed per-year from 2017 to 2021. The important column to pay attention to is **Comb Consumption kWh**.

*2017*:

![image](https://user-images.githubusercontent.com/90221511/144763819-ab2212ab-f240-4b4f-8f4c-262acf7ea90b.png)

*2018*:

![image](https://user-images.githubusercontent.com/90221511/144763826-bad8899c-28f2-4cd8-b06a-e70b74b5e413.png)

*2019*:

![image](https://user-images.githubusercontent.com/90221511/144763829-dede5dab-06d3-4706-b05b-d3acd30878b8.png)

*2020*:

![image](https://user-images.githubusercontent.com/90221511/144763832-2804d659-59db-4af9-bb7d-90e3a062901f.png)

*2021*:

![image](https://user-images.githubusercontent.com/90221511/144763834-7a390256-5068-434c-a4ae-5c59ccabf7ae.png)

The goal is obviously to get consumption as low as possible (while still maintaining acceptable range and etc, however we will purely be focusing on consumption itself here).

As evident by watching the Comb Consumption kWh column over the years, the average and lowest fuel consumption values are indeed getting lower over time. This is desirable behaviour, however more can be analyzed from this data by paying attention to the range, the vehicle class, and the manufacturer (the Make column).

The average range of the most fuel-efficient vehicles is shown to increase over-time, going with the highest in 2017 only being 201km, and the highest in 2021 being 568km. This is good, as it shows that as fuel efficiency increases over-time, range is not being sacrificed.

While the vehicle class was very mixed in 2017, with all 3 top vehicles being of different classes, every year starting with 2018 has shown that the most fuel-efficient vehicles are mid-sized. This could be a result of either mechanical efficiency with mid-size vehicles being optimal for travel, or of business reasoning by manufacterers on the assumption that mid-size vehicles will sell the best.

Observing the Make over-time shows that Tesla got a good foot in the industry in 2018, and slowly increased their fuel-efficiency until they were responsible for all 3 top-performing vehicles by 2021.

Similar to observing the range analysis results, it looks easy to conclude that Tesla is clearly the most efficient in terms of fuel consumption as well. However, one last key observation is important to note when considering this: each manufacterer's output of different vehicle models over time.

#### **Model Releases Per Year**

Below is the number of models that each relevant manufacterer has released from 2017-2021.

![image](https://user-images.githubusercontent.com/90221511/144764214-a882fc63-10d4-469b-9f24-ace65a3b7cfd.png)

As you can see from this table, Tesla produces an insanely higher number of vehicle models per year than any other manufacterer. This may in-part be because, while other manufacterers may release a single model, Telsa releases numerous variants along the lines of a "Standard Range" model, a "Standard Range Plus" model, a "Mid Range" model, a "Long Range" model, and more as shown by this sample from 2019:

![image](https://user-images.githubusercontent.com/90221511/144764338-9c650a4b-3def-4505-a650-2a0f325d6b22.png)

So while they are clearly still producing the most efficient vehicles in terms of range and fuel consumption, it is important to remember that they may have a midleadingly-high lead above other manufacteres by having so many more models, despite said models being very similar to eachother.

---

### **Conclusion**

#### Summary:
In conclusion, the data analyzed has shown that Tesla is the most-efficient manufacterer of battery-electric vehicles in terms of both range on a single charge and fuel consumption. They are also the most diverse manufacterer class-wise, meaning that it is safe to conclude that they are currently leading the battery-electric vehicle industry forward. Other manufacterers are starting to catch on, however, as the number of new makes involved in the battery-electric veihcle industry increases each year.

In terms of the future, the efficiency of vehicles on average is also increasing each year steadily, with mid-size vehicles showing to be the best option in terms of efficiency going forward.

#### Reflection

While Tesla has been a big-name in the media in terms of electric vehicles for the past few years, it was incredibly interesting to analyze objective data and reach the conclusion that they are indeed leading the electric vehicle industry in terms of efficiency and output. To reach the same conclusion through objective observation shows  that their popularity was not a fluke or product of good marketing, but instead an indication of the quality of their product.

Given the chance to go deeper into this subject, it would be interesting to compare how this data changes over time in comparison to more external factors such as government subsidies and see if there is a correlation present in the adoption of electric vehicles.

--- 

### **Acknowledgements**

This project was submitted as the final course project for CSCI 2000U “Scientific 
Data Analysis” during Fall 2021. The authors certify that the work in this 
repository is original and that all appropriate resources are rightfully cited.

--- 

### **README**

To analyze this data, the csv file had to be converted to support UTF-8 encoding. While it does not do this by default, the file was manually converted by removing unsupported characters. This 'readable' file can be found in the root directory under the name [MY2012-2021 Battery Electric Vehicles Readable.csv](https://github.com/jonahbaayen/csci2000u-group3-final/blob/main/MY2012-2021%20Battery%20Electric%20Vehicles%20Readable.csv).

To run the python notebook, this file must be placed in the same directory as the notebook. If this file is present, all the code should work properly.
