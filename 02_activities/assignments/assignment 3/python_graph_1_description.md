- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
        > Python, using matplotlib/ seaborn
    > Who is your intended audience? 
        > Municipal & provincial policymakers, public sector energy manager & energy analysts
    > What information or message are you trying to convey with your visualization? 
        > How much total energy the Broader Public Sector uses, by showing energy use by subsector and sector
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
        > Aesthetic: Made the visualization simple & used colours that are easy to differentiate.
        > Substantive: Displayed both sector & subsector clearly, to show two categories of data.
        > Perceptual: Clearly shows which subsectors and sectors use the most energy overall.
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
        > Used Python code so that the code behind the visualization is well-documented and commented.
    > How did you ensure that your data visualization is accessible?  
        > Color blindness: used an online colorblind image tester to make sure the 3 colors used for the sectors can be interpreted by someone with deuteranopia. Used high contrast colors.
        > Made sure the visualization followed the principles of being clear and concise.
        > Added data labels so small values are easy to interpret.
        > All visual elements described in the legend.
        > Made sure all font sizes were 12+ and used arial (sans-serif) font.
        > Converted GJ to millions of GJ for readability.
    > Who are the individuals and communities who might be impacted by your visualization?  
        > Energy managers for BPS facilities
        > Municipal net-zero planning divisions
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
        > The objective of the visualization is to see total energy use, so that's the column I included. Used weather-normalized energy use so that it's more comparable across different locations in Ontario.
        > Grouping by subsector made sense as it was granular enough to be a useful grouping, but not too granular that it would be a massive graph. I thought about grouping by 'primary property type', but that column had 58 unique values.
    > What ‘underwater labour’ contributed to your final data visualization product?
        > Collecting the data from all of the facilities
        > Cleaning & sorting the data