| [Home Page](README) | [For Reference](For-Reference) | [Data Viz Examples](dataviz-examples) | [Vizualizing Govt. Debt](visualizing-government-debt) | [Critique by Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |

# Water World- A Critique by Design

## The Original Visualization  

<img src="Water World.png" align=left width="600"/>

I chose this visualization because it has some elements in its favor, including a pretty aesthetic and an interesting subject. However, it also has plenty of room for improvement, with a design that's not immediately intuitive. 

<br clear="left"/>
Source: [Information is Beautiful](https://informationisbeautiful.net/visualizations/water-world-distribution-of-the-all-the-water-in-all-the-world/)

## The Critique
### Overall Observations- What stood out?  What worked well?  What didn't work well?

- Although quite pretty, it took me a long time to understand what I was looking at. Once I looked at it for a while it made plenty of sense but it wasn’t immediately intuitive.
- It really is quite aesthetic. The colors are nice, it’s a unique visualization, I like the concept of the layers, and I like how dots are (kind of) proportional to percentage.
- The grey ovals representing the different layers get confused with the lines stemming out to the three largest categories (oceans, salt groundwater, and freshwater). Consequently, despite the colors, it took me a bit longer than is preferable to understand the layering.
- There’s not much to tell me what I should be gathering from this visualization. It’s certainly possible that there’s more in the book it came from (“Knowledge is Beautiful”), but I don’t have it here. I’m guessing, given the white circles, that he wants us to head through the layers to ultimately see how humans are using water. If so though, why did he include the organisms?
- None of the items are in any particular order within their categories. Nothing is sorted by size, alphabet, or anything else.

### Who is the primary audience for this tool?  Is this visualization effective for reaching that audience?

- I think this is for people who love a good visualization, who like to learn new things, and who love data. Maybe people who like to tell their friends at trivia night that 35% of the water in all organisms can be found in insects.
- The visualization comes from a book called “Knowledge is Beautiful” by David McCandless, a book apparently full of infographics and visualizations on many categories like science, power, money, health, space, art, thought, and dogs. Clearly it’s not for the everyday public. People seeing this design likely have a bit of experience viewing data visualizations already, which maybe forgives the initially confusing nature of the visualization a bit.
- McCandless certainly supports the thesis of the book that information is beautiful. However, I think his use of the data itself could be improved upon.

### What's wrong with the data?
Upon closer inspection, I found that the data is both wrong and misleading:

- The visualization says that 0.03% of freshwater is found in organisms, but the spreadsheet says it’s actually only 0.003%.
- Saltwater lakes are left completely off the visualization even though they account for a larger percentage of water than multiple other sources.
- The implication is that each colored layer adds up to 100% of the water source they stem from. None of them (with the exception of the largest, blue layer) do. Normally these rounding errors wouldn’t be completely egregious, except for the fact that some of the categories are as small as 0.01%. They are as follows:
1. Types of Freshwater: 100.36%
2. Water in Organisms: 101.6%
3. Water Used by Humans: 101%
- The organism and used by humans data are from separate data sets than the higher layers. Using multiple data sources isn't an issue except that the organism data set appears to be cobbled together from various incomparable sources and I simply can’t find the used by humans data set. The link doesn't work and I can’t find it online.
- It’s visually unclear if water used by humans is 0.03% of all freshwater, or just 0.3% of the combination of lakes, rivers, and groundwater. 

## A Sketch

<img src="Water World Sketch.jpg" align=left width="500"/>

This was my first draft.
- I decided to change the visualization form to a Sankey Diagram with the hope of eliminating some of the original visual confusion. I still really like it because it does a good job of showing scale.
- I ran into a huge challenge with the data, given all the data clean-up that needed to be done on the provided data spreadsheets. This sketch has my attempt to fix things with the organisms data, but it still didn't feel right. I also decided to eliminate the "Used by Humans" section because it didn't add to my story. 

<br clear="left"/>

## Testing the Sketch

I asked a couple people to critique my sketch, asking the questions below. Here are their responses:

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
| Can you describe to me what this is telling you? | It's about where water can be found throughout the world. |The percent makeup of water in different categories.|
| Is there anything you find surprising or confusing?| The title is long and worded confusingly. |Surprising: just how little water is found in humans and how much is salt water. |
| What elements do you like? |The color choice is nice, I like how the scale gives perspective, and the labels are lined up neatly. |I like that the human one is red, it calls it to attention and I can compare it to everything else immediately.|
| Is there anything you would change or do differently? |Change the title, maybe to "Where is the World's Water?"|Maybe rotate 90 degrees clockwise, so it flows down like water.|
| Do you think it's an improvement from the previous visualization?|Definitely, it was confusingly laid out and  didn't tell a story. |Yes, it's much more clear, easy to follow, and takes up less space.|

Not much of the feedback from the two sources was similar although they both agreed that it was formatted well and the coloring was good. I decided to change the title but not to what was suggested.

## The Final Form

This is the final form of my water data visualization. A couple notes:
- I still prefer my sketch concept. I think it more clearly demonstrates the story I'm trying to tell about scale. Unfortunately I wasn't able to find software that would bring my vision to life sufficiently in the time I had. That being said, I think the new visualization isn't terrible and I think the title is better than it was before.
- I spent a long time with McCandless' data and simply couldn't get it to make sense. Consequently, I would like to make it clear that I don't trust the "Organisms" data set and with more time, would have found a different one.

<div class='tableauPlaceholder' id='viz1744053046448' style='position: relative'><noscript><a href='#'><img alt='Humans only make up 0.00225% of Earth&#39;s water ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ea&#47;EarthsWater&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='EarthsWater&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ea&#47;EarthsWater&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>               
<script type='text/javascript'>                   
  var divElement = document.getElementById('viz1744053046448');                
  var vizElement = divElement.getElementsByTagName('object')[0];                   
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1277px';}                 
  var scriptElement = document.createElement('script');               
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                
  vizElement.parentNode.insertBefore(scriptElement, vizElement);        
</script>

#### Source: McCandless, David. “Water World.” Information is Beautiful. Accessed April 2, 2025. [https://informationisbeautiful.net](https://informationisbeautiful.net). 

#### AI Acknowledgements: N/A
