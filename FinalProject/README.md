# Capstone Project
### Kayla Bracall 
### ATE 252
### Spring 2020

## Capstone Inquiry
This project aims to look at fatality among older drivers, specifically those ages 65 and older. Are older drivers more likely to be involved in a fatal accident? Are drivers 75 and older more likely to be involved in a fatal accident than those aged 65 to 74? What are the most fatal driving conditions for older drivers?

## Data Cleaning 
Data was complied from the PA Crash Dataset.
Source: [https://data.pa.gov/Public-Safety/Crash-Incident-Details-CY-1997-Current-Annual-Coun/dc5b-gebx](https://data.pa.gov/Public-Safety/Crash-Incident-Details-CY-1997-Current-Annual-Coun/dc5b-gebx)
1. Within the online dataset, data was filtered down to drivers ages 65 and older
2. This data was saved as a csv file and further filtered down to remove columns that would not be analyzed
3. The filtered csv file was uploaded into OpenRefine
4. Boolean columns with "Yes/No" values were converted to 0 and 1 through text faceting 
5. The Boolean columns were transformed to integer values for analysis
6. Null values were removed and the transformed file was saved as a csv file

## Analysis

1. The first step was to pull in some constants that were not reflected in the transformed file: Total Crashes and Total Fatalities. The dataset had 2,751,551 rows, so we are able to determine the total crashes. Finding total fatalities took some more work, as the whole dataset was too large to download as a csv for analysis. Pennsylvania publishes a yearly report with crash information. Fatalities were totaled from each year's report from 1997 to 2018
2. Next, additional dataframes were created. A dataframe was created that only contained fatal crashes, a dataframe was created that only included drivers ages 65 to 74, and a dataframe was created that only included drivers ages 75 and older. This allowed for further analysis into fatalities and into the two different age groupings. 
3. Finally, basic statistical analysis was performed on the dataframes to determine:
    1. Are older drivers more likely to be involved in a fatal crash than younger drivers?
    2. Is there a further discrepancy in older drivers? Are drivers ages 75 and older more likely to be involved in a fatal crash than drivers ages 65 to 74?
    3. What are the most fatal conditions to older drivers? 

## Findings 

Ultimately, the data does show that older drivers(ages 65 and older) are more likely to be involved in a fatal accident than drivers under the age of 65. The risk of fatality seems to increase with drivers age 75 and older.

The three most "fatal" conditions to older drivers are:
* **Unbelted** -
Approximately 40% of fatalities involving an older driver also involved someone not wearing a seatbelt. This is unsurprising, as not wearing a seatbelt increases the risk of fatality for any driver or passenger, regardless of age.  
* **Wet Road Conditions** -
Approximately 13% of fatalities with an older driver involved wet road conditions. This was the most surprising finding to me, as I had expected that snow slush or icy roads would be more fatal than wet road conditions. 
* **Drinking Driver** -
Over 9% of fatal crashes involving an older driver also involve a drinking driver. Again, this is not an unusual finding, as alcohol impairs any driver. 

## Data Limitations 
* The first data limitation that I experienced was null values in the dataset. Fortunately, there was only one row in the data that I selected that contained null values. I ultimately chose to change these values to "no" responses
* The second limitation that I ran into was that the 2002 PA Crash fatality count was not available online. The 2003 PA Crash report noted that in 2002, a different form was used to compile information, so the report was not generated that year. To solve this limitation, I averaged the fatality counts from the years 2000, 2001, 2003, and 2004. The fatality count has been trending down throughout the years. As such, I did not average all years, as I did not want the value to be inaccurately low.

## Relevance of Findings

I believe this information is relevant to the PA Dept. of Transportation (PennDOT), as they maintain the roads and license drivers. I believe further research is needed to determine the causes behind fatality in older drivers. For example, the fatality of wet roads to older drivers is the most intriguing to me. Is the fatality rate on wet roads similar to the fatality rate on wet roads for younger drivers? What is the cause of this fatality rate? Is it poorer eyesight in older drivers? Is it slowed reaction time? If these are indeed the causes behind increased fatality rates, perhaps PennDOT would research into retesting licensed drivers after a certain age. 

I think this is also relevant to the families of older drivers, as it can help determine the safety of those older family members on the road. If family members know the conditions that contribute to fatal crashes in older drivers, perhaps they can help mitigate them. For example, the can offer alternate transportation for older family members, rather than having them drive in conditions dangerous to them. 

## Future Research Opportunities 

I have stated throughout this summary that I believe further analysis is needed to determine the statistical significance of increased fatality rates in older drivers. I also think that a future research opportunity is to research the causes behind the conditions that cause increased fatality in older drivers. As stated above, is this due to factors such as poorer eyesight and slower reactions times? Or is it something else? If due to biological causes, I think it'd also be imperative to research thing such as fatal crashes in older drivers in the day vs the night and in warmer months vs colder months. 

Regarding substance use, are older drivers more likely to be considered a "drugged" driver due to medication use? To what extent does prescription use affect an older driver's ability to drive?

Is there an age where the likelihood of fatality increases so much that PennDOT would consider retesting drivers of that age, or limiting drivers' privileges, similar to how drivers under 18 have a junior license?

Overall, I think this is a good starting point that brings interesting points to the surface, but ultimately there is much more research to be done. 

