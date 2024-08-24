A breif summary about the EDA
Out of the given 19 metrics in the dataset i have chosen to only focus on 10 metrics as they are the most relevant metrics for our analysis and ultimately business objectives.The key columns(KPIs) that i have considered are:

1.GHI(W/m2): is a metric which indicates the total sunlight that was recieved on a surface. I consider this metric very significant to the analysis since it directly indicates optimal solar panel locations with immense potential for generating solar energy.

2.DNI(W/m2): This metric indicates areas with low interference by clouds and atmospheric pressure.Areas having high DNI values are ideal for installing solar panels.

3.DHI(W/m2): This metric aids in assessing solar potential even in areas with cloud cover or atmospheric scattering. It shows overall sunlight availability.

4.Tamb(°C): The temprature of air is crucial and has an immmense effect on the efficiency of solar panels because extreme temprature resuces their performance. So, this metrics helps us in selecting areas with optimal temprature ranges.

5.RH(% - Relative Humidity): This metric indicates humidity levels which is a key factor in the performance of solar panels. This is because in areas with high humidity it leads to decreased effectiveness due to condensation.

6.WS(m/s) and WSgust(m/s): This metric helps us assess and locate areas with lower wind speed and gust as these areas are ideal because they can support solar installations without excessive damage.

7.Precipitation(mm/min): This metric helps us in selecting drier areas which are optimal for loacting solar panels. This is becasue high precipitation goes hand in hand with reduced sunlight and increased maintenance cost.

8.TModa(°C) and TModb(°C): This metrics are key for the fact that they indicate the performance of the sensors in different environments and the condition inturn affecting the solar measurements are tracked.

9.WSstdev: The standard deviation of wind speed is a useful tool for calculating the variations in wind speed over time. High variability may be a sign of erratic wind conditions, which could affect how well solar panels function, particularly in terms of upkeep and durability.

In general, my justifications for choosing the above metrics are summarized below:
           -Sunlight Exposure(GHI, DNI and DHI)
           -Temprature(Tamb)
           -Humidity and Precipitation(RH, Precipitation)
           -Wind factors(WS and WSgust)
           
In the next stages i am going to continue with my prior basic exploration and analysis with only these 11 KPIs are going to be used for the comparison to select optimal areas to install solar panels. So, i am going to drop or subset the metrics that are irrelevant to the main analysis. I am going to use subseting sue to the reason that maybe i want to look at the other metrics in the end.
