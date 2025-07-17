# Share Data Through the Art of Visualization

## Frameworks for organizing your thoughts about visualization   

- **Information**: the data with which you’re working 
- **Story**: a clear and compelling narrative or concept
- **Goal**: a specific objective or function for the visual
- **Visual form**: an effective use of metaphor or visual expression

## Pre-attentive attributes

### Marks

Marks are basic visual objects such as points, lines, and shapes. Every mark can be broken down into four qualities:

1.  **Position:** Where is a specific mark in space relative to a scale or to other marks?

    For example, if you’re looking at two different trends, position allows you to compare the pattern of one element relative to another.

    *A simple line chart with two lines. One is red and one is blue, and there is obvious space between them.*

2.  **Size:** How big, small, long, or tall is a mark?

    The comparison of object sizes can be an easy visual interpretation for humans. This can be very useful for conveying the relationship between categories or data points. However, this also presents a potential problem: The human eye can inadvertently interpret comparisons that aren’t intended to convey meaning. For example, sometimes objects that appear to be the same size when they are not. Controlling the scale of a visual is important even when comparative sizes are not intended to offer information.

    *A plot with points that are different sizes.*

3.  **Shape:** Does the shape of a specific object communicate something about it?

    Rather than using simple dots or lines, a bit of creativity can enhance how quickly people are able to interpret a visual by using shapes that align with a given application. In the example below, it is immediately obvious that numbers of people are represented because the bars are person-shaped.

    *A horizontal bar chart, but the bars are made of icons shaped like people.*

4.  **Color:** What color is a mark?

    Colors can be used both as a simple differentiator of groupings or as a way to communicate other concepts such as profitable versus unprofitable, or hot versus cold.

    *A bar chart with a red, green, yellow, grey, and blue bar.*

### Channels

Channels are visual aspects or variables that represent characteristics of the data in a visualization. They are basically specialized marks that have been used to visualize data. It’s important to understand that channels vary in terms of how effective they are at communicating data based on three elements:

1.  **Accuracy:** Are the channels helpful in accurately estimating the values being represented?

    For example, color is very accurate when communicating categorical differences, such as apples and oranges. But it is much less effective when distinguishing quantitative data, such as 5 from 5.5.

    *A plot with apples and oranges representing the data points.*

2.  **Popout:** How easy is it to distinguish certain values from others?

    There are many ways of drawing attention to specific parts of a visual, and lots of them leverage pre-attentive attributes including line length, size, line width, shape, enclosure, hue, and intensity.

    *A line chart with three blue lines of different shades, and one red line.*

3.  **Grouping:** How effective is a channel at communicating groups that exist in the data?

    Consider the proximity, similarity, enclosure, connectedness, and continuity of the channel.

    *A bar chart with four groups of bars. In each group, there is a red bar and a blue bar.*

> But, remember: The more you emphasize one single thing, the more that counts. Emphasis diminishes with each item you emphasize because the items begin to compete with one another.   


## The beauty of visualizing  
**Correlation** is a statistical measure of the degree to which two variables move in relationship to each other.   
- Positive Correlation: Both variables move in the same direction. For example, as the temperature rises, ice cream sales also rise.
- Negative (or Inverse) Correlation: The variables move in opposite directions. For example, as one variable goes up, the other goes down.
- No Correlation: A change in one variable does not correspond to any change in the other.

**Causation** refers to the idea that an event leads to a specific outcome. For example, when lightning strikes, we hear the thunder (sound wave) caused by the air heating and cooling from the lightning strike. Lightning causes thunder.  

Mistaking correlation for causation can lead to incorrect and potentially harmful conclusions in data analysis, especially when the stakes are high. While correlation shows a relationship between two variables, it does not prove that one causes the other.   
To illustrate this, the passage provides two key examples:

### Cause of Disease (Pellagra)

*   **Observed Correlation:** In the early 1900s, it was observed that people with the disease pellagra often lived in unsanitary conditions.
*   **Incorrect Assumption (Causation):** People wrongly concluded that unsanitary conditions caused the disease.
*   **Actual Cause:** Further investigation revealed the true cause was a niacin (Vitamin B3) deficiency. The correlation existed because poverty was the underlying factor: people who couldn't afford niacin-rich foods also couldn't afford sanitary living conditions. Acting on the correlation alone would not have solved the health crisis.

### Distribution of Aid (SNAP Benefits)

*   **Observed Correlation:** Website analytics show that people who qualify for SNAP benefits visit the official website but leave without signing up.
*   **The Limitation:** While analytics provide clues (correlations) like repeat visits or quick exits, they don't explain *why* people aren't signing up.
*   **The Necessary Step:** To truly solve the problem and increase sign-ups, the agency must investigate the actual cause by collecting more data (e.g., through surveys) rather than just guessing based on the observed correlation.   


the difference between static and dynamic visualizations, highlighting their characteristics, use cases, and the key trade-offs an analyst must consider.

#### Static Visualizations
*   **Definition:** Visualizations that do not change unless they are manually edited.
*   **Use Case:** They are useful when you want to maintain complete control over the data and the specific story you are telling.
*   **Examples:** Any chart printed on paper or a basic graph created in a spreadsheet that requires manual data changes to update.

#### Dynamic Visualizations
*   **Definition:** Visualizations that are interactive or change over time, giving the user some control over what they see.
*   -**Use Case:** They are helpful when you want to allow stakeholders to explore the data, adjust views, or see real-time information.
*   **Examples:** A Tableau dashboard with interactive filters or sliders (like the happiness map example), or a graph that automatically updates with new data by the second, minute, or day.

#### The Key Trade-Off
*   There is a critical balance between user interactivity and narrative control. The more power and interactivity you give to the user with a dynamic visualization, the less control you have over the specific story the data tells.

#### How to Choose
*   The decision to use a static or dynamic visualization depends on three main factors:
    1.  The nature of the **data** you are visualizing.
    2.  The needs of the **audience** you are presenting to.
    3.  The method or format of your **presentation**.   


### The art of visualization  

**Nine Basic Principles of Design for Data Visualization**

The following principles guide data analysts in creating effective and engaging visualizations. The first six are key considerations during the creation process, while the final three are useful for reviewing the completed design.

**Principles for Creating Visualizations**

1.  **Balance:** Key visual elements like color, shape, and space are distributed evenly across the visualization. This creates a sense of stability and prevents one area from overpowering another, even without perfect symmetry.

2.  **Emphasis:** A clear focal point is created to guide the audience's attention to the most important data first. This is often achieved using contrasting colors, sizes, or value intensity to make specific elements stand out.

3.  **Movement:** The visualization guides the viewer's eye along a logical path, often mimicking natural reading patterns (e.g., left to right). This can be achieved through the use of lines, animations, or the strategic placement of elements.

4.  **Pattern:** Similar shapes, colors, or arrangements are used to create a recognizable structure. Patterns help highlight similarities in the data or can be intentionally broken to draw emphasis to a specific point.

5.  **Repetition:** Repeating elements like chart types, shapes, or color schemes for the same categories adds to the visualization's effectiveness. It helps the audience understand that different elements belong to distinct but related sets of data.

6.  **Proportion:** The size and scale of visual elements are used to demonstrate the relative importance of the data. For example, making one chart in a dashboard larger than others signals that it is the main focal point.

**Principles for Reviewing Visualizations**

7.  **Rhythm:** The final design has a natural sense of movement and flow that guides the viewer smoothly through the information. It is closely tied to the principle of movement.

8.  **Variety:** The visualization includes a mix of chart types, shapes, and colors to keep the audience engaged. However, it's important to find a balance, as too much variety can become confusing and overwhelming.

9.  **Unity:** All the individual elements and components of the visualization work together to form a single, cohesive, and understandable whole. The final product should not feel disjointed or disorganized.


#### Visualization impact  
the primary goal of data visualization is to make complex information easy for an audience to understand. The choice of visualization should be driven by the specific analytical task and the audience's needs.

---

**Choosing the Right Chart for Your Data**

Different charts are suited for different analytical purposes:

*   **To Compare Data Over Time:**
    *   Line Graphs
    *   Bar Graphs
    *   Stacked Bar Graphs
    *   Area Charts

*   **To Compare Distinct Objects:**
    *   Ordered Bar Graphs
    *   Grouped Bar Graphs
    *   Ordered Column Charts

*   **To Show Parts of a Whole (Data Composition):**
    *   Stacked Bar Charts
    *   Donut Charts
    *   Stacked Area Charts
    *   Pie Charts
    *   Tree Maps

*   **To Show Relationships Between Variables:**
    *   Scatterplots
    *   Bubble Charts
    *   Column/Line Combination Charts
    *   Heatmaps

---

**Three Essential Elements of Effective Visuals**

Drawing on principles from visual journalist Dona Wong, the passage highlights three key elements for creating powerful visualizations that align with how the human brain processes information:

1.  **Clear Meaning:** The visualization should communicate its main insight clearly and unambiguously.
2.  **Sophisticated Use of Contrast:** Visual contrast should be used to make the most important data stand out from the rest.
3.  **Refined Execution:** The design must show a high level of attention to detail, thoughtfully using visual elements such as lines, shapes, colors, and spacing.   

#### Design thinking for visualization improvement

1. **Empathize**: Thinking about the emotions and needs of the target audience for the data visualization 
2. **Define**: Figuring out exactly what your audience needs from the data
3. **Ideate**: Generating ideas for data visualization
4. **Prototype**: Putting visualizations together for testing and feedback
5. **Test**: Showing prototype visualizations to people before stakeholders see them.   

### Storytelling and sharing time in visualization

- **Prep (5 min)**: Create the mental and physical space necessary for an environment of comprehensive thinking. This means allowing yourself room to brainstorm how you want your data to appear while considering the amount and type of data that you have.
- **Talk and listen (15 min)**: Identify the object of your work by getting to the “ask behind the ask” and establishing expectations. Ask questions and really concentrate on feedback from stakeholders regarding your projects to help you hone how to lay out your data. 
- **Sketch and design (20 min)**: Draft your approach to the problem. Define the timing and output of your work to get a clear and concise idea of what you are crafting.
- **Prototype and improve (20 min)**: Generate a visual solution and gauge its effectiveness at accurately communicating your data. Take your time and repeat the process until a final visual is produced. It is alright if you go through several visuals until you find the perfect fit.   

## Data Storytelling  
This analysis breaks down three different visualizations from a data-driven article on noise complaints, evaluating their effectiveness at each stage of the narrative: setting context, analyzing data, and drawing conclusions.

---

### Tour Stop 1: Combo Table and Bar Chart
*   **Purpose:** Setting context by defining "noise."
*   **Evaluation:**
    *   **How it helps the story:** The chart effectively summarizes noise complaints by category, answering the question, "What is noise?" The choice of a combo table and bar chart is more elegant and readable for 11 categories than a pie chart would be.
    *   **Data Clarity:** The visualization causes minor confusion because the percentages add up to 98% instead of 100%, likely due to rounding. This highlights the importance of ensuring numbers are accurate.
    *   **Best Practice Demonstrated:** It functions like a "companion table," presenting the data in both table and chart format to accommodate audience preference.

---

### Tour Stop 2: Stacked Area Chart
*   **Purpose:** Analyzing the distribution of noise complaints by time of day.
*   **Evaluation:**
    *   **How it helps the story:** The chart performs well against the "five-second rule," quickly showing that complaints about loud music and barking dogs peak late at night. The alignment of the legend with the chart's color-coded layers enhances readability.
    *   **Data Clarity:** Unlike the first chart, this one is clear, and its percentages correctly add up to 100%.
    *   **Best Practice Demonstrated:** It uses creative labeling by including units (`%`, `A.M.`, `P.M.`) directly on the axis ticks. This makes separate axis titles unnecessary and results in a cleaner, more streamlined design.

---

### Tour Stop 3: Neighborhood Map
*   **Purpose:** Drawing conclusions about the noisiest neighborhoods.
*   **Evaluation:**
    *   **How it helps the story:** The map effectively emphasizes the journalist's key observation that a very noisy neighborhood is located right next to a very quiet one, using strong color contrast to make the point visually.
    *   **Data Clarity:** It clearly classifies the data by neighborhood, allowing the audience to easily follow the journalist's focus on specific areas.
    *   **Best Practice Demonstrated:** It uses direct labeling for each neighborhood, which eliminates the need for a separate legend and makes the map easier to interpret quickly.   


### Live versus Static

Identifying whether data is live or static depends on certain factors:

*   How old is the data?
*   How long until the insights are stale or no longer valid to make decisions?
*   Does this data or analysis need updating on a regular basis to remain valuable?

---

#### Static data

Static data involves providing screenshots or snapshots in presentations or building dashboards using snapshots of data. There are pros and cons to static data.

**PROS**
*   Can tightly control a point-in-time narrative of the data and insight.
*   Allows for complex analysis to be explained in-depth to a larger audience.

**CONS**
*   Insight immediately begins to lose value and continues to do so the longer the data remains in a static state.
*   Snapshots can't keep up with the pace of data change.

---

#### Live data

Live data means that you can build dashboards, reports, and views connected to automatically updated data.

**PROS**
*   Dashboards can be built to be more dynamic and scalable.
*   Gives the most up-to-date data to the people who need it at the time when they need it.
*   Allows for up-to-date curated views into data with the ability to build a scalable “single source of truth” for various use cases.
*   Allows for immediate action to be taken on data that changes frequently.
*   Alleviates time/resources spent on processes for every analysis.

**CONS**
*   Can take engineering resources to keep pipelines live and scalable, which may be outside the scope of some companies' data resource allocation.
*   Without the ability to interpret data, you can lose control of the narrative, which can cause data chaos (i.e., teams coming to conflicting conclusions based on the same data).
*   Can potentially cause a lack of trust if the data isn’t handled properly.


### Share Data Stories

To ensure your stakeholders understand your data and stay engaged, structure your presentation as a compelling story. A strong narrative makes your key messages clear and memorable.

---

**The Five Elements of a Data Story**

Use these five basic storytelling elements to outline your presentation and organize your findings.

1.  **The Characters**
    *   Identify the people affected by your story—stakeholders, customers, or clients. This adds a human context and explains why the audience should care about the results.

2.  **The Setting**
    *   Describe the background of your project and the current situation. This provides the necessary context for your audience to understand what's happening and why.

3.  **The Plot (The Conflict)**
    *   Introduce the challenge, business problem, or opportunity that creates tension. This is the central conflict that your data analysis aims to solve and is what drives the need for action.

4.  **The Big Reveal (The Resolution)**
    *   Present the solution that your data has uncovered. This is where you show *how* the problem can be solved or the goal can be achieved, based on your analysis.

5.  **The "Aha Moment"**
    *   Share your final, actionable recommendations. Clearly explain what steps should be taken and why you believe these actions will lead to success. (Pro-tip: This is often a great place to start when planning your presentation.)   

After outlining these five parts, pair your narrative with interesting and persuasive visuals to effectively communicate your story.   


Once you have the key elements of your data story (character, setting, plot, reveal, aha moment), the next step is to build a professional slideshow that effectively communicates your findings.   

1. Design for Professionalism and Consistency
*   **Use Themes:** A presentation theme controls colors, fonts, and formatting to create a consistent and professional look. Choose a theme that matches the tone of your information and supports your narrative.

---

2. Structure Your Slides for Clarity
*   **Title Slide:**
    *   Include a clear title and subtitle.
    *   Always add the date of the presentation, especially if the data is likely to change over time.

*   **Content and Text:**
    *   **The 5/25 Rule:** Keep text to less than **five lines** and no more than **25 words** per slide.
    *   **Guide, Don't Script:** Your slides should support what you are saying, not repeat it verbatim. The audience should be listening to you, not reading your slides.
    *   **Use Clear Language:** Avoid slang, abbreviations, and regional jargon that your audience may not know.

---

3. Use Visuals to Support Your Story
*   **Focus on a Single Point:** Ask yourself, "What is the single most important thing I want my audience to learn from this visual?" Choose data points that directly support your key message.
*   **Avoid Clutter:** If you have several important points, create a new visual for each one instead of cramming them onto a single slide.
*   **Direct Your Audience's Attention:** Use arrows, call-outs, or highlighting to guide viewers to the most critical part of your chart or graph.
*   **Make Your "Aha Moment" Shine:** Your visuals for the big reveal and final recommendations should be exceptionally clear and impactful to convey their importance and excitement.

---

4. Understand How to Add Visuals to Your Slideshow

The method you use to add a visual determines where it is stored and how it is updated.

*   **Copy and Paste:**
    *   Creates an independent, static copy of the visual in your presentation.
    *   It **will not** update if the original data source changes.

*   **Link:**
    *   Connects your presentation to the original source file via a URL.
    *   The visual **will automatically update** in your slideshow if the source file is changed. This is ideal for live or frequently changing data.

*   **Embed:**
    *   Places a copy of the visual in your presentation that is independent of the source.
    *   It **will not** automatically update if the source file changes.   


### Strategic Framework for Data Presentations
A strategic framework is essential for making your data presentations accessible and ensuring your audience understands the key takeaways. This framework involves consistently connecting your findings back to the **business task** and the **business metrics**.

---
1. Frame Everything with the Business Task

The business task is the core question or problem your analysis addresses. It provides the necessary context for your data.

*   **State the Task Upfront:** Begin your presentation by clearly defining the business task.
*   **Outline Your Presentation:** Create an early slide that lists the presentation's goals and explicitly connects each one back to the business task. This provides a narrative roadmap for your audience.
    *   *Example Goal:* "Examine seasonal trends in online avocado searches."
    *   *Connection:* "Understanding these trends can help forecast stocking needs and inform planning."
*   **Frame Each Visualization:** When presenting a chart, explain how it helps solve the business task. Use speaker notes to script these connections.
    *   *Example:* "This graph shows the months with the most online searches last year, so we can expect similar interest this year."

---
2. Explain Your Business Metrics

Clearly explaining your metrics helps the audience understand the impact of your findings and how you arrived at them.

*   **Define Your Metrics:** Explicitly state the metrics used in your analysis.
*   **Add Context to Visuals:** Include key metric details directly on your slides to help the audience interpret your visuals correctly.
    *   **Time Period:** "Our data shows Google search queries from 2004 to 2018."
    *   **Geography:** "Search queries are limited to the United States only."
    *   **Scale of Measurement:** "Google Trends scores are normalized at 100."

By using this framework, you keep your presentation focused, provide your audience with clear context, and ensure your data story is both understandable and impactful.   


### Setting the Stage for Your Data

To effectively integrate data into your presentation, you must first set the stage for your audience and then use a structured method to explain your visuals.  

1.  **Explain What Data Was Used:**
    *   Describe the scope of the data collected (e.g., "all searches containing the word 'avocado'").
    *   Clarify its limitations to manage audience expectations about what questions the data can answer.

2.  **Establish Your Initial Hypothesis:**
    *   State the theory you were trying to prove or disprove with your analysis early on.
    *   This gives your audience a framework to understand the results you are about to present.

---

**The McCandless Method: A 5-Step Guide to Presenting Visuals**

This method provides a clear, step-by-step process for explaining data visualizations, moving from general context to specific details.

1.  **Introduce the Graphic by Name**
    *   Start by clearly stating the title of the chart to direct your audience's focus.
    *   *Example:* "This graph is titled 'Yearly Avocado Search Trends.'"

2.  **Answer Obvious Questions Before They're Asked**
    *   Proactively explain how to read the chart, where the data came from, the time period it covers, and how it's measured. This prevents confusion.
    *   *Example:* "This circular chart shows time running from winter at the top to summer at the bottom. The farther a point is from the center, the more searches there were."

3.  **State the Insight Your Data Provides**
    *   Clearly and concisely share the main takeaway from the visual before diving into details.
    *   *Example:* "This data shows a consistent seasonal trend year over year, with searches peaking in January and February, despite avocados being a summer fruit."

4.  **Call Out Data to Support That Insight**
    *   Provide specific examples from the chart to prove your point and make your findings more impactful.
    *   *Example:* "During the week of November 25th, the search score was 49, but by February 4th, it jumped to 90, showing a clear surge in interest."

5.  **Tell Them Why It Matters (The "So What?")**
    *   Connect the insight directly to business impact and provide clear, actionable recommendations for your stakeholders.
    *   *Example:*
        *   "Prepare for the Super Bowl surge in avocado interest in late January."
        *   "Account for lower interest between October and December."
        *   "Optimize stocking practices during spring and summer."

> **Final Tip:** Before adding any data or chart to your presentation, always ask yourself: "Does this support the main point I want people to walk away with?"   


### slide presentation

- **Include a title, subtitle, and date**: Making sure that your slide deck presentation has a title, subtitle, and date makes sure that your audience knows exactly what you are presenting and when the information was from. That way they know it’s relevant and current to them!
- **Use a logical sequence of slides**: Organizing your slides in an order that makes sense guides your audience through your narrative, building understanding step by step.
- **Provide an agenda with a timeline**: An agenda offers a roadmap of your presentation, allowing your audience to follow along and anticipate key topics.
- **Limit the amount of text on slides**: Keeping text brief ensures clarity and retains the audience’s attention; aim for your audience to scan it within 5 seconds.
- **Start with the business task**: By immediately relating the content to the business task at hand, you contextualize your information, making it relevant and actionable.
- **Establish the initial hypothesis**: Presenting an initial hypothesis gives your audience a starting point for what to expect and frames the subsequent analysis.
- **Show what business metrics you used**: Clarifying which metrics you're analyzing validates your arguments and helps the audience gauge your presentation's relevance to business outcomes.
- **Use visualizations**: Visual aids can illustrate complex data more effectively than text alone, making your message more accessible.
- **Introduce the graphic by name**: A brief introduction to each graphic aids in understanding and retaining information.
- **Provide a title for each graph**: Titles act as signposts, helping the audience quickly grasp the meaning of each visual.
- **Go from the general to the specific**: Starting with a broad overview before diving into details ensures that all audience members are on the same page.
- **Use speaker notes to help you remember talking points**: Notes act as your cue cards, enabling a smoother delivery and ensuring no critical point is missed.
- **Include key takeaways**: Summarizing the main points at the end of your presentation reinforces the message and ensures the audience leaves with the intended takeaways.   


### Critique of a presentation
| Messy Data Presentation | Good Data Presentation |
| :--- | :--- |
| No story or logical flow | Has a clear flow or table of contents |
| No titles for slides or charts | Includes a title and date the presentation was last updated |
| Too much text on slides | Uses concise, animated bullet points |
| Inconsistent format with no theme | Uses a consistent, repeated theme |
| Visuals are hard to understand and lack introduction | Introduces visuals and uses annotations to clarify them |
| No recommendation or conclusion at the end | Has clear logic, progression, and conclusions |
| Leaves the audience lost and confused | Logically guides the audience through the data |
| Lacks smooth transitions | Uses transition slides between sections |
| Fails to address data limitations | Explains limitations and caveats of the data |   

### Share data findings

1. Tip 1: Know Your Flow

A good data story, like any story, needs a clear structure. This structure depends on understanding your audience and the purpose of your presentation.

**Who is my audience?**
*   **Executives (C-Suite):** Keep the presentation high-level and brief. Focus on the results and recommendations that encourage action.
*   **Stakeholders:** Be prepared for more data-specific questions about your analysis and how you reached your conclusions.
*   **Analysts and Peers:** You have the most freedom to go into deep detail about the data, processes, and methodologies.

**What is the purpose of my presentation?**
*   **To Make a Request (like a sales pitch):** Each slide should logically build toward the final recommendations.
*   **To Focus on Results:** Each slide should act as a "breadcrumb," showing the analytical path you took to arrive at the findings.
*   **To Report on Data:** The slides should clearly summarize the key data and findings, letting the data itself be the focus.

---

2. Tip 2: Prepare Talking Points and Limit Text on Slides

Slides should support your narrative, not contain the entire script.

*   Prepare **talking points** (or speaker notes) for what you will say for each slide. This helps create a natural flow and avoids awkward pauses.
*   Keep slides visually focused and **limit the amount of text**. If your audience is busy reading, they aren't listening to you.
*   Follow the **five-second rule**: your audience should be able to understand the main point of a slide within five seconds.

---

3. Tip 3: End with Your Recommendations

The recommendations are the ultimate goal of your presentation—the "mountaintop."

*   Dedicate **one clear and concise slide** at the end for your recommendations.
*   If you are recommending an action, outline the **next steps** and describe what a successful outcome would look like.

---

4. Tip 4: Allow Enough Time for the Presentation and Questions

Respect your audience's time by being efficient and prepared.

*   Keep your presentation as **short and on-topic** as possible.
*   Ensure every slide tells a **unique and important part** of your data story. Combine slides if they aren't distinct.
*   Save **enough time for questions**, either by building it in throughout the presentation or by having a dedicated Q&A session at the end.