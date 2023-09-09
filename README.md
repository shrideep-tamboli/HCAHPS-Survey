# HCAHPS-Survey
### Overview:
Analyzing the impact of the Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey conducted by the American Hospital Association (AHA) for the last 9 years.
### Problem:
How to enhance the quality of service hospitals give from the survey results?
### Requirements:
1. Have hospitals' HCAHPS scores improved over the past 9 years?
2. Are there any specific areas where hospitals have made more progress than others?
3. Are there any major areas of opportunity remaining?
4. What recommendations can you make to hospitals to help them further improve the patient experience?
### Solution:
1. Calculate increase / decrease in the values of Top Box Rating (9 or 10) & Bottom Box Rating (0-6) **by YEAR**.
2. Calculate increase / decrease in the values of Top Box Rating (9 or 10) & Bottom Box Rating (0-6) **by MEASURE_ID**(type of service).
### Details:
1. KPIs on this dashboard:
* Excellent Services / Top Box check: Change in Top Box Rating since 2013 i.e. [Top Box Rating in 20XX] - [Top Box Rating in 2013]
* Poor Services / Bottom Box check: Change in Bottom Box Rating since 2013 i.e. [Bottom Box Rating in 20XX] - [Bottom Box Rating in 2013]
2. Indication of performance:
* Hike in performance: Blue is above Pink.
* Drop in performance: Pink is above Blue.
### Results:
<div class='tableauPlaceholder' id='viz1694243826154' style='position: relative'><noscript><a href='#'><img alt='Dashboard (Combined) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HC&#47;HCAHPSSurvey_16927047066870&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HCAHPSSurvey_16927047066870&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HC&#47;HCAHPSSurvey_16927047066870&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1694243826154');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='2560px';vizElement.style.maxWidth='3000px';vizElement.style.width='100%';vizElement.style.minHeight='1087px';vizElement.style.maxHeight='1227px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='2560px';vizElement.style.maxWidth='3000px';vizElement.style.width='100%';vizElement.style.minHeight='1087px';vizElement.style.maxHeight='1227px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='2827px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
