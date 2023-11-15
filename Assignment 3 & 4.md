# Assignment 3&4

Original Data :
https://gml.noaa.gov/aggi/aggi.html
I Mainly redesign the firgure 3 chart 
<img width="990" alt="截屏2023-11-15 上午2 09 16" src="https://github.com/Qingyuan666/Telling-story-with-data/assets/115184503/6409a5e8-fe8f-4f38-a656-2e44c7be6ae4">


Original data visualization critique:
In this part, I first read the questions in Google form and took them to understand the original data visualization. 

# Redesign Sketch:
Based on what I find in the critique part, I conclude the main problems of the original visualization are:
1. non-interactive causing no concrete data information given by chart;
2. not easily figure out the two y-axis means in the same chart and the possible data tortuosity when matching the two y-axises in one chart.
3. Cannot quickly get to know what the radiative forcing value and the AGGI value means just seeing the chart.

Therefore, for redesign sketching, I plan to change the cumulative color area chart into an interactive, cumulative bar chart providing all data points of all years along all greenhouse gases and shown the obviouse contrast between total and each type of gas. Simultaneously, I want to divide the aggi and the radiative forcing value into two charts.

![sketch](https://github.com/Qingyuan666/Telling-story-with-data/assets/115184503/2ee6b9d7-ba50-41a6-883a-5ac94b08ee44)


The handwriting sketch cannot truly show all 40+ years and all concrete tags, marks, and interactive effects on every bar, but I express the core meanings of what I want to do in the redesign and show the picture to my teammates with language explanation. 
They understood and gave me the advice as follows. 

# Solution Test:
1. No title and text explanation of the two metrics in y-axises;
2. The radiative forcing value for all greenhouse gases may be more important than the aggi so the high and low position of the two parts should be converted.
3. If as I think, giving line at the frontier of each of the gas' bar area. The visual effect will be very dense especially I put all gas types on in the final version and the frontier of bars can show the changing tendency along the past years. So I should eliminate the line of each types just remain that one of total.


# Final Data Visualization:
<div class='tableauPlaceholder' id='viz1700023567086'>
    <noscript>
        <a href='#'>
            <img alt='How does the Greenhouse Gas Change in past 40 years? Radiative forcing, relative to 1750, of virtually all long-lived greenhouse gases. The NOAA Annual Greenhouse Gas Index (AGGI), which is indexed to 1 for the year 1990.' 
                 src='https://public.tableau.com/static/images/As/Assignment34_17000235375810/1/1_rss.png' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='Assignment34_17000235375810/1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/As/Assignment34_17000235375810/1/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='zh-CN' />
        <param name='filter' value='publish=yes' />
    </object>
</div>

<script type='text/javascript'>
    var divElement = document.getElementById('viz1700023567086');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

# Summary
Following the feedback from my teammates, I conducted the final version of the redesign in tableau and found a new problem the gas types with the least proportion in greenhouse gas produce a very small part of the cumulative bar so they will be partly covered by the total value line. Unfortunately, I have not found a good solution for this problem because if I want the total data can be shown in the chart I must use a line of it. If I also use a cumulative bar of the total, the total part cannot be compared with each type of gas and make clear that all types construct to the total one. So I choose to remain the current look with some layer hidden. 

My final version of data visualization achieves the following items:
1. Aiming at showing the aggi and radiative forcing two different values more clearly and making the user figure out there are two types of metrics, I split the two things into two chart parts. This point originates from the perceptibility in the measuring system. 
2. In order to show the different greenhouse gas proportions constructed to the total, I made a cumulative bar chart for each type shown in different colors and used a line to show the total greenhouse value. In this way, we can clearly figure out the different percentages of different greenhouse gases in the total. And the interactive way can provide each time point's concrete and entire information by moving the mouse to there. This way is for usefulness, completeness, and perceptibility. 
3. At the aggi part, I add a markable tag to show when the ratio is 1 and let the use know what are above 1 and lower than 1.
4. In deciding the color usage of bar chart, I do not choose to use transforming color because the different areas showing big and small very clearly of those types, which does not need use transforming color to show different types of gas' high or low proportion. Within one type, using transforming color to show high or low in different year is ok but this will cause too many different colors in the chart. It will cause messy visual effects so I give up it. The color choosing depends on the aesthetics and usefulness principles.
5. I added the explanation of the two y-values as a subtitle of the chart and made the title of the chart telling very simple and concise things to help the user quickly know what is the chart generally about. It is for intuitiveness and perceptibility. 



