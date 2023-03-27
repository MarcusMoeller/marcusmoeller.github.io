---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# About the data

This data story covers historical police department incident reports from 2006-2017 in San Francisco. The story will address the number of crimes related to drugs and narcotics and where this is a problem in San Francisco. There will be drawn attention to what kind of drugs and narcotics are the most common crime cases as well as whether it is possession, sale, or transport of these drugs that have been registered.

# Time-series / bar chart

<iframe src="/timeseries.png"
    sandbox="allow-same-origin allow-scripts"
    width="1200"
    height="800"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>


The following bar chart shows the occurrences of drug/narcotic crimes per year for every district in San Francisco. Note that the y-axes are not comparable. Try to compare all the ranges on the y-axes. 


Now, it is clear that Tenderloin is the district with by far the most drug related crime[link to article]. Keep in mind here, that the bar chart does not take into account the areas or populations of the districts. The drug crime occurrences is higher in Tenderloin despite the fact that it is one of the smallest San Francisco districts. 

The overall tendency throughout the entire city is that drug related crimes are decreasing. However, it is clear to see that there has been a huge decrease in Tenderloin specifically, compared to all other districts. Since the drug problem is far more significant in this district, police actions have been targeted here specifically. The Tenderloin Station newsletter from April 2018 states that the “good work Tenderloin Station Officers are doing is paying off.” and that this good work “causes a significant disruption in the Tenderloin drug network.” 



# Map

<iframe src="/heatmap.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

This is the Tenderloin district which confirms our numbers in the time-series plot.
The occurrences are distributed across every street in this area where most occurrences happen during waking hours. Can the higher amount of registered reports be explained by the increased police presence during the daytime?




On the following map, you can see where the drug/narcotic crimes occur in an hourly pattern throughout the day. All occurrences during each hour are aggregated which corresponds to each frame in the visualization. Hence, frame 1 corresponds to all occurrences that happened between 01:00 and 01:59 and so forth. You are able to play the video chronologically or in a reversed manner as well as navigate through each frame. The frames per second can also be adjusted and it is possible to drag and zoom in and out on the map.
It looks like there is a more dense area of occurrences in a neighborhood in the northeastern part of San Francisco.
Try to scroll closer to this dense area of dots!


# Bokeh viz

<iframe src="/bokeh1.html"
    sandbox="allow-same-origin allow-scripts"
    width="1200"
    height="800"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

The bar chart below shows the occurrences of crimes related to specific drugs. To the right you can play around with showing the different crime types, either possession, sale, or transport.

Firstly, it is clear that there are some types of drugs which are more prevalent in San Francisco than others, including amphetamine, cocaine, heroin, and marijuana.
Furthermore, the bar chart shows us that possession of drugs is the crime type which is most common compared to sale and transport. Could this possibly be explained by the fact that possession is easier to discover?



# Conclusion

The data has taught us that some districts have been more affected, some hours are busier, and that some drugs are more prevalent. All these are facts that the SFPD can use to optimize their police force for both prevention and treatment of crime. Some of the initiatives which the SFPD have reported throughout the years have been numerous sobriety 
checkpoints (https://www.sanfranciscopolice.org/search?search=drug%20crimes&type=All&page=2), where the police systematically checks drivers for DUIs. Furthermore, the police has taken part in several prescription drug “Take Back” days (https://www.sanfranciscopolice.org/news/sfpd-nationwide-prescription-drug-take-back-day-nets-over), where citizens are able to safely and securely get rid of unwanted prescription drugs. Lastly, the SFPD has initiated different more specific initiatives to fight the drug-related crimes throughout the city, such as the Opiate Overdose Prevention Program (https://www.sanfranciscopolice.org/news/sfpd-announces-opiate-overdose-prevention-program), which turned out to be a success according to the SFPD news (https://www.sanfranciscopolice.org/news/sfpd-experiences-continued-success-opiate-overdose-reversals).

The data and the SFPD report have shown that the San Francisco Police Department has managed to decrease the amount of drug-related crimes in the city from its peak around 2008 until 2017.



