For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
        > Microsoft Excel
    > Who is your intended audience? 
        > Municipal & provincial policymakers, public sector energy manager & energy analysts
    > What information or message are you trying to convey with your visualization? 
        > The EUI and GHGI in the Broader Public Sector, and the relationship between those two metrics.
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
        > Aesthetic: Made the visualization simple & used colours that are easy to differentiate between GHGI and EUI.
        > Substantive: Displayed GHGI and EUI for all relevant subsectors that data was available for.
        > Perceptual: Clearly shows which subsectors have the highest EUI and GHGI, and how those two variables are correlated.
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
        > Used Excel so the visualization is not reproducible. If someone wanted to create this again, they wouldn't know what steps I took to get to this point.
    > How did you ensure that your data visualization is accessible?  
        > Color blindness: used an online colorblind image tester to make sure the 2 colors used for the different variables can be interpreted by someone with deuteranopia. Used high contrast colors.
        > Made sure the visualization followed the principles of being clear and concise.
        > Made sure all font sizes were 12+ and used arial (sans-serif) font.
        > Converted EUI to kwh/m2 and GHGI to kgCO2e/m2 for readability and interprebility.
        > Added a legend to clearly differentiate between the data shown in the bars vs the line.
    > Who are the individuals and communities who might be impacted by your visualization?  
        > Energy managers for BPS facilities
        > Municipal net-zero planning divisions
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
        > EUI and GHGI are calculated columns in the dataset, but when I looked at the averages for each subsector - they seemed off (columns C & G). There's likely some errors in the self-reported GFA for each building. So I took the total GFA and total energy (GJ)/ total GHG emissions (tonnes) and calculated the EUI/ GHGI as an average across the subsector. 
        The objective of the visualization is to see total energy use, so that's the column I included. Used weather-normalized energy use so that it's more comparable across different locations in Ontario.
        > I also did not include non-BPS subsector (since this is focused on showing BPS) or municipal boards, because weather-normalized data was not available for that subsector.
        > Grouping by subsector made sense as it was granular enough to be a useful grouping, but not too granular that it would be a massive graph. I thought about grouping by 'primary property type', but that column had 58 unique values.
    > What ‘underwater labour’ contributed to your final data visualization product?
        > Collecting the data from all of the facilities
        > Cleaning & sorting the data