# Final Project'
# Part 1 

# data source: 
https://www.education.pa.gov/DataAndReporting/Graduates/Pages/default.aspx
In the dataset, it gives all counties in PA‘s public schools many metrics about the postsecondary education like graduate number, college number, non-degree number, and so on. 
I will use the data to present the students next eduction type proportion of PA and this situation compared among different counties. 



# Outline
Summary: This project is trying to describe the high school graduates' post-education situation after high school in different counties in Pennsylvania in 2021-2022. The data storytelling will cover the entire post-high school education statistical performance of all the public high schools. 

Structure: 
1. overview for the whole state: the story will begin by showing the general data proportion of different types of post-education in the whole state.
2. then the story will dig into micro perspective to unfold each county's different post-education proportion. 
3. then the project will give an interactive map with heatmap features to indicate the comparison of university rates along different counties and provide concrete information in hidden layers.

#Sketches
Whole State Overview
<div class='tableauPlaceholder' id='viz1700633891854' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='The Student Situation after high school in whole PA' src='https://public.tableau.com/static/images/Th/TheStudentSituationafterhighschoolinwhoePA/1/1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='TheStudentSituationafterhighschoolinwhoePA/1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/Th/TheStudentSituationafterhighschoolinwhoePA/1/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object>
</div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1700633891854');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Each County Data
<div class='tableauPlaceholder' id='viz1700634978533' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='Top 5 High Postsecondary rate County' src='https://public.tableau.com/static/images/To/Top5HighPostsecondaryrateCounty/1/1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='Top5HighPostsecondaryrateCounty/1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/To/Top5HighPostsecondaryrateCounty/1/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object>
</div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1700634978533');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>




Interactive Map
In this part, I find there are some difficulties in drawing data map at the county level in Tableau. I need to research on it in the future so I just draw handwriting sketches now
<img width="452" alt="截屏2023-11-22 上午2 58 38" src="https://github.com/Qingyuan666/Telling-story-with-data/assets/115184503/e86697a0-d3bb-4d56-93e7-d2260582ceaa">

# Method and medium
Platform: 
Mainly Tableau + Online data map tools: Google map, and Datawrapper to solve the county-level data presentation. 

Improvement points:
1. more clear shown of the each education type's name in the chart;
2. subdivide all counties into high, medium and low college rate, three groups, to show the data structure of counties within each group.
3. Figure out some emphasis at the dense and complex data map of all counties.  


