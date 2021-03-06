

<h1>
  Create a Tableau Story Write-Up
</h1>
<p>
  Created by Richard James Lopez for the Udacity Data Analyst Nanodegree Program. The presentations can be found here: https://public.tableau.com/profile/richard.lopez#!/
</p>
<h2>
  Summary:
</h2>
  <p>
    This Tableau story visualizes the available market data available for the Cryptoasset AirSwap Token. AST is a relatively new Cryptoasset, but it does have price dynamics that were worth looking into.
  </p>
<h2>
  Design:
</h2>
  <p>
    The story lays out 4 core themes that can be gleamed from vanilla pricing data.
    <li> Price
    <li> Market Cap
    <li> Volatility
    <li> Spread
    </li>
    <br>
    These themes are conceptually very similarly, and so there was a need to use different chart types for themes. For example, the Volatility and Spread are depicted by Scatterplots and Heat Maps respectively. Also, they have different time intervals (months vs. weeks) to differentiate the message and slides.
  </p>  
<h2>
  Feedback:
</h2>
  <p>
    The feedback I received was to rethink the color scheme. The comment was laid out as such:
  </p>
  <p>
    <li> "I can't gather why some months are red and another green from looking at your Volatility slide"
  </p>

  <p>
     Originally, the Volatility slide (Dashboard 3) had a shared color scheme with the other slides (Red to Green spectrum). This uniform color scheme generally makes sense as it relates to negative to positive performance. However, for the Volatility slide, the colors were differentiated by time as opposed to performance. It was confusing for the viewer to see red and green by month as they thought it had to do with positive vs. negative performing months. I changed this to a blue spectrum color scheme for the 2nd version of this Tableau Story.
  </p>
  <p>
    Typically for price charts, a normal line graph will explain most of the information. However, in order to tell a more thorough story, the ability to utilize other charts superimposed on a line graph is helpful. For example, for the 'Market Cap' chart, I overlay the area chart for 'Volume' over the line chart for 'Market Cap'. This condenses the message of two graphs into one and allows the User to quickly contrast their reciprocal and then eventual diverging behavior.
  </p>
  <p>
    Also, for the Range slide, combining the power of shapes and colors can emphasize certain contrasting behavior. For the size charts that describe the 'Price Range by Week', it was important to reinforce the message that certain weeks of activity had a much wider range of price. By having the message be conveyed with the size of the bubbles as well as the colors of them - the message is unequivocal. Here the large bubble and the bright green shows that there was a very that is very different from the others and that there is a large range. The color scheme may have implicit messages (large ranges can lead to more trading profits, and hence green may be representative), but at least the contrast of green to red makes it known that certain weeks were different. A similar dynamic is in place for the next heat map for 'Average Price by Week (pre-December)' as you can see a lead up to what ended up being December when the price eventually skyrocketed. Aside from the first week in November when there was a slow start, the average price had a gradual price increase that is represented by kind of steps that are represented by size of blocks and shades of the color green. This represents a steady buildup of price into the Holiday Season.
  </p>
  <p>
    Ultimately, there were about 10 different visualizations that I tried out before culling and then grouping them into 4 slides. Once a message per slide was put in place, I thought about the pairs of charts and how they could complement each other and where text would support either one or both of them. The design component informed the organization and supporting information that followed.
  </p>

<h2>  
Resources:
</h2>
  <p>
    <li>https://github.com/jhogan4288/coinmarketcap-history
    <li>https://github.com/tableau/document-api-python
    <li>http://onlinehelp.tableau.com/current/pro/desktop/en-us/publish_workbooks_tableaupublic.html
    </li>
  </p>
