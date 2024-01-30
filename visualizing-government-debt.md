| [Home](https://kcufford.github.io/portfolio/) | [Visualizing Debt](visualizing-government-debt) | [Critique by Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |

# Assignment 2: Visualizing Government Debt

### Part 1: Working with Web-Based Visualization Tools and Data

<iframe src="https://data.oecd.org/chart/7kiD" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7kiD" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

<br/>

This first exercise was to demonstrate that visualizations can be sourced from different websites, customized, and then embedded on your own site. I opted to select data from 2020 for this chart, which provides a good number of countries to compare to the average OECD debt-to-GDP ratio. The chart is interactive, which allows users to hover over a country’s bar to get more information. The bar gets highlighted in a different color for easy visibility, and a tooltip appears to provide specific data about the country’s ratio.

-------------

### Part 2: Working with Tableau

<div class='tableauPlaceholder' id='viz1706575459696' style='position: relative'><noscript><a href='#'><img alt='General Government Debt-to-GDP Ratio: 1995-2022 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DebttoGDP1995-2020&#47;DebttoGDP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DebttoGDP1995-2020&#47;DebttoGDP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DebttoGDP1995-2020&#47;DebttoGDP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706575459696');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<br/>

The purpose of this next visual was to show that data can be exported from one source and then uploaded to Tableau to create a new visualization.  In this case, we created a heatmap, which differs from the previous chart in that data is shown for all countries spanning over a longer period of time (1995-2022).  Tableau allows for custom colorization, so the heat map showcases blue for positive ratios under 100%. For those ratios greater than 100%, the colors go from orange to deep red to show the extremely high ratios that may be of concern.

-------------

### Part 3: Creating Your Own Visualization

<div class='tableauPlaceholder' id='viz1706575895474' style='position: relative'><noscript><a href='#'><img alt='Japan&#39;s debt-to-GDP ratio continues to rise, while Germany stays lowA look at the G7 debt-to-GDP ratio trends over the past 20 years. This ratio is a key indicator for the sustainability of government finance, and changes over time primarily reflect the impact of past government deficits. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;G7&#47;G7DebttoGDP2002-2022&#47;G7&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='G7DebttoGDP2002-2022&#47;G7' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;G7&#47;G7DebttoGDP2002-2022&#47;G7&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706575895474');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<br/>

For this final section, I chose to use data from 2002-2022 for the G7 countries. Using all the countries from the OECD download for the heat map felt like a bit of information overload to me, which is why I chose to stick with the 7. I thought it would be interesting to see what I could do with a smaller data set. My initial idea was to show the ratio trend over the 20 years, so I opted to do a line chart. I set my x-axis tick marks every two years to prevent overcrowding along the axis. Additionally, I have the axis time period ending in 2023 (not shown) to allow for a little extra space along the righthand side so the labels aren’t butting up against the border of the graphic.

The first thing that stood out to me was Japan’s high ratio trend line. I wanted a basis for comparison within the chart, so I picked Germany, which was on the other end of the spectrum. My use of color helps highlight these two countries, with the blue representing Germany’s lower (better) ratio compared to the red representing Japan’s higher (worse) ratio. Since I included all G7 countries, I made the remaining five countries grey. The grey is not distracting from the story of Japan and Germany, but it provides additional insight into how the two countries compare with the rest of the group. I found it interesting that the trend line for these five countries is very similar. I felt showing the labels at the end of all the lines was necessary so the viewer could easily interpret which line belonged to which country.  

-------------

### Summary


Citation: OECD (2024), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 27 January 2024)
