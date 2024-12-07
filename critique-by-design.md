| [home page](https://h-calderon.github.io/portfolio/) | [visualizing government debt](visualizing-government-debt.md) | [critique by design](critique-by-design.md) | [final project part 1](final-project-part-1.md) | [final project part 2](final-project-part-2.md) | [final project part 3](final-project-part-3.md) |


# Critique by Design
## Original Design

These are the original charts, posted in the New York Times in 2020. I felt this was an interesting topic because it's supposedly an old saying that you're supposed to spend at least 2 months worth of your salary when buying an engagement ring, and the data presented here goes against that notion.

![original bar](original-bar.png)

> Source: <a href="https://www.nytimes.com/2020/02/06/learning/whats-going-on-in-this-graph-engagement-ring-costs.html">New York Times, 2020</a>

Overall I felt the graph types were appropiate for the message they wanted to convey (AKA how most people aren't spending that much money on engagement rings), but there were a couple of things I decided to change on my redesign.

## Sketches

For the first graph: I like the use of a histogram to tell this story, but it felt a bit cluttered to me, and the marks on the Y-axis felt distracting due to their thickness. On the X-axis side of things, the marks where spaced unevenly, which was also confusing.

![sketch 1](sketch-1.jpg)

For the first sketch, I decided to keep the graph type, but redid the bar-chart to have thinner bars to make it less claustrophobic. Leaving them more spaced out while also having the marks on the X-axis happen every $1,000. Since I now had more space to work with, I decided to add the numeric value of each bar to the plot. Note that I decided to switch the metric from a numeric value to a percentage. This is because I feel it adds readability: I'm not sure if 260 people choosing a $500 ring is a lot, but I know what 16% stands for.

Finally, I decided to add onto the story the fact that 50% of the respondents were on the lower side of the spending spectrum, which is why I decided to shade that part differently and add a subtitle to the graph.

![sketch 2](sketch-2.jpg)

For the second graph, I changed the category metric from months to weeks, so all the data would be represented by weeks. Much easier to read this way. As for the bar chart: I wanted to make this graph a bit more allusive to the topic of rings, so I decided to switch the size comparison to circles: a sort of bubble chart within a table, in a sense. The story I wanted to tell highlighted the fact that only one of the annual income categories spent a high percentage of their annual salary on rings, so I changed its color to make it a bit more striking.

# Feedback

The feedback process for the first couple of sketches was very enlightening. I interviewed 3 people of ages between 27 and 35, and their comments were the following:

## Graph 1
* The message conveyed by the graphs was easy to understand, and it basically confirmed their initial thoughts that people weren't spending a ton of money on unnecessary things because we're in a bad economic position.
* One of the people interviewed asked why I was highlighting the 50% of respondents in the first graph. He thought it was an arbitrary affirmation, and the stopping point could have been anywhere else. I have to say, I agree that it is arbitrary, but I like the 50% because it's like a toin-coss, 50/50 chance kind of deal, so I kept that
* Someone recommended trying a line graph for the first chart instead of an histogram, and then adding small circles or "rings" on the important parts of that line chart. I'll admit I liked the idea in theory, but in practice, I couldn't find a way to make a line chart more passable than what I already had
* For the highlighted parts in the histogram, I was told the gray area wasn't having a good contrast with the white area, and that the line separating both was a bit confusing. It was recommended that I switch the color on those first few columns if I wanted to highlight them, which I did on my final revision. I agree, it looks much better than this. As for the color, 2 out of the 3 people interviewed said that green was something they associated with cash.

## Graph 2
* All 3 of the people interviewed wanted the second graph to include information on the average ring cost for each of the annual earnings categories. I agree, it'd have made for an interesting piece of information to include into the table, maybe by adding another column to the right of the percentages. However, that data wasn't available in the original charts, so this couldn't be added.
* For the second graph, one person asked me why I was using circles instead of bars. They said they couldn't really tell the size difference between the last 3 categories. But then again, this is on purpose: the values in the last 3 categories are pretty close to one another, the real difference to look at is the lower earnings categories. But I will concede that the circles weren't really working well and it wasn't allusive of rings at all (as I was repeatedly told by the interviewees). So in the end, I made them all to be actual rings.
* Finally, the color red of the highlighted category was changed to green as well, to match the previous chart
* Turns out only 1 out of the 3 people I interviewed was familiar with that whole "engagement ring worth 2-3 months of earnings" saying, which leads me to believe I'm so inmersed in television and pop culture I can no longer tell what is common knowledge and what is not. So upon further discussion, it was suggested I add this information to the second graph

# Final Result

## Graph 1
<div class='tableauPlaceholder' id='viz1731550500690' style='position: relative'><noscript><a href='#'><img alt='The Price of Love50% of the respondents spent up to $2,300 dollars on an engagement ring ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;PriceEngagementRing&#47;ThePriceofLove&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='PriceEngagementRing&#47;ThePriceofLove' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;PriceEngagementRing&#47;ThePriceofLove&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731550500690');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Graph 2

<div class='tableauPlaceholder' id='viz1731552569322' style='position: relative'><noscript><a href='#'><img alt='3 Months&#39; Salary for a Ring?Unlike what the famous saying might have you believe, only people with lower annual income are willing to spend more than 8 weeks of earnings for an engagement ring ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;We&#47;WeeksSalaryforanEngagementRing&#47;3MonthsSalaryforaRing&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='WeeksSalaryforanEngagementRing&#47;3MonthsSalaryforaRing' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;We&#47;WeeksSalaryforanEngagementRing&#47;3MonthsSalaryforaRing&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731552569322');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>





  
