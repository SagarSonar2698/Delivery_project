# Delivery_project
delivery project _ feature engineering


Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.
The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

The company wants to understand and process the data coming out of data engineering pipelines:

• Clean, sanitize and manipulate data to get useful features out of raw fields

• Make sense out of the raw data and help the data science team to build forecasting models on it


**Outcome of the project**
1) the mean of actual_scan_time and start_scan_to_end_scan is same this is proven using kruskal test and hence correlation between both column is high hence the difference between this two column can be used to gauge wheather delivery is late or fast.

2) the p_value for hypothesis testing between actual_time and osrm_time is very low hence we can not infer anything by comparing both of this column this is may be because actual_time take road conditions and traffic conditions where as osrm_time does not considers this aspects.

3)mean of actual_time and segment_actual_time is signifincant since p_value is high and hence we can refer this values to draw inference.

4) mean of osrm_distance and segment_osrm_distance is statistically not significant and hence we can not consider both the columns in
