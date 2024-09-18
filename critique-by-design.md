| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Makeover Monday Activity 
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: Choosing Visualization to Makeover 

Data Visualization: 
Natural Disasters
How many people die from disasters, and how are these impacts changing over time?
https://ourworldindata.org/natural-disasters

Include paragraph or two on why you selected this particular data visualization.  For obvious reasons, the data visualization you select should come from a publicly accessible source._

## Step two: Critiquing the Visualization 
What stood out to me, What I don't think works well, and What I would Change: 

What stood out was that the site displayed the data as a table, map, and chart. All three of these visualizations let you filter by country, year, and different natural disaster data. I didn't notice this at first. Having the data available in different mediums can be helpful for different audiences. It's an effective interactive tool. I am a map enthusiasts so I focused on assessing the map portion of this dashboard. Displaying world data on natural disasters as a map is definitely an effective and engaging way to display the data.

I love GIS so in this critique we will just focus on the map. (However there is a plot twist at the end.)
The color scheme choropleth is unclear at first glance. There is a light blue tone among a choropleth that includes beige, coral, & red tones. It is unclear at first glance to determine where on the color scale the light blue color falls. Besides this blue, it is clear that the lightest color is the countries with the least amount of deaths by natural disasters. However, I do think these colors need to be more distinct from each other and have a light orange to dark red choropleth.  There are seven bins. The last bin is for countries with deaths between 1 million to 10 million, for 2020 this is particularly not relevent. I would alower the amount of bins to 5. This would allow for a choropleth map that has colors that are very distinct from each other. 

The data is aggregated by decades, termed here ‘decadal averages.’ I think this term can be confusing at first. A viewer can think 1990 averageas are 1981-1990 or 1990 to 1999. Though it can be confusing, after understanding what decadal averages are it also makes sense to think about the data in terms of decades. So for instances we can say in the 90's there were more deaths by natural disasters. 

The map aggregates the data by all-natural disasters. Since this is an overview map of all-natural disasters, it does make sense that the data is a decadal average of all-natural disasters. However, What could be more helpful is a time-lapse map of a decadal average of each natural disaster in addition to the map of all-natural disasters. The time-lapse video changes quickly between frames, slowing this down would be helpful for the viewer to capture the information. 

Audience, Audience, Audience ! This is important to think about for visuals as much as it has been ingrained for us to think about it being important for writing. For these visuals and dataset, the primary audience is someone who can or is empowered to create change. This includes government officials, researchers, professors, students, and community members. The authors provide the data as a table, map, and chart. A government official can filter the data as needed. The authors could have provided maps and charts with disagregated data. Assessing the map on its own, the visual could be more effective in reaching the intended audience. A government official would benefit more from a visual it can look at quickly to get numbers. The aggregated deaths of all natural-disasters is not particularly helpful for a government. For them to make actionable changes, disaggregated data would be more informative. It would be helpful to understand what natural disasters are more prominent in a particular country or region. 

## Step three: Sketch the Makeover

![Sketch the Makeover](Sketches.png)

## Step four: Test the Makeover

**Feedback #1: **
Can you describe to me what this is telling you?
The map represents deaths caused by natural disasters. 

Is there anything you find surprising or confusing?
The countries being listed 1 - 10 could be confusing in terms of if 1 is the highest death or the lowest among the top 10. 

Is there anything you would change or do differently?
What are the natural disasters that happened in these countries. Is there really no deaths from natual disasters in those regions. The map is overall clear, it is straight forward with the darkest color being highest death. Did have questions about the difference between determining a polygon is gray with line and just a solid grey color. Listing countries in a chart to the side of the map. 

**Feedback #2: **
Can you tell me what you think this is? Can you describe to me what this is telling you?
It's a map of natural disasters as of 2020. 

Is there anything you find surprising or confusing?
The decadal average term is confusing. 

Is there anything you would change or do differently?
Make 1-10 numbered countries clear. The gradient color is good. The legend number is clear and cleaner that way so leave it as is. 

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

Both individuals that provided feedback were curious to know what sort of natural disasters were driving the total number of deaths in each country. Turkey had the highest natural disasters. Feedback provider #1 asked, "what goes on in Turkey?". The authors of this dataset on the impact of natural disasters on countries around the world probably gathered this information to help government officials be prepared for natural disasters. A map with total deaths from natural disasters is too general for a government to form an actionable plan from the visual. Given this curiosity in what natural disasters are causing deaths in a nation I will instead focus on a region of the world and choose a natural disaster that impacts that region the most. This way I can provid more detailed information for a smaller region than provding less information for a larger region. 

## Plot Twist !

I see dataset with spatial data and jump with enthusiasm ! I think lets make a map and exciting I get to practice my mapping skills !

In this excercise I learned that maps aren't always the makeover solution. Yes even when there is spatial data involved and the data is about counties, states, countries, and the whole world. 

I got to this conlucsion by thinkining about -- Audience --. How can the data be best visualized for a government official or united nations member to look at & quickly gather the data ? How can the data compare country information side-by-side to quickly make comparisons ? 

So I scratched the map idea. I decided to focus on just a portion of the world and show more detailed information that could be helpful for a government official. I studied abroad and traveled South America, I hold these countries close to heart for this reason and because as a Latina I want to adovcate for the Latino community. Given these reasons and many more I decided to choose it as the region to dive into. 

The dataset had information of almost all natural disasters. I used the authors map visual and filter to determine which natural disaster most affected South America and which year ranges had more information. Flooding impacted South America the most between 2010 to 2019. This is why I chose flooding as the natural disaster to create a visual for.

Thats the plot twist: the map enthusiast had to challenge herself to make a line chart because its what will benefit the audience the most. 


## Step five: Build the Makeover

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._


Critiquing My Makeover: 
I'm new to Tablaeu, I have yet to discover its full potential. Given that I am developing mt Tablaeu skills there are many things that I would do to adj


<div class='tableauPlaceholder' id='viz1726628267003' style='position: relative'><noscript><a href='#'><img alt='The Toll of Flooding on South American Economies and Communities 2010 - 2020 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Na&#47;NaturalDisasters-LineChart&#47;EffectsofFloodLineChart&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NaturalDisasters-LineChart&#47;EffectsofFloodLineChart' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Na&#47;NaturalDisasters-LineChart&#47;EffectsofFloodLineChart&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
var divElement = document.getElementById('viz1726628267003');                   
var vizElement = divElement.getElementsByTagName('object')[0];                   
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                   
var scriptElement = document.createElement('script');                   
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

