# Media Bias: How news shapes your perception

## Background and overview
Media Bias is a data visualization tool meant to help the user visualize the implicit bias of their news sources.

All news coverage is not created equal, news is written with the purpose to create and sell entertainment and information to its consumers and as such it is subject to the same market pressures as any other product. The danger however comes when we forget this and trust any single news outlet as our single source of truth.

Media Bias displays a live updated global map with a news API javascript program that populates the map with news stories from a specific news source. Users will see a heat map of news coverage from different media outlets and will thus be able to see how different news sources focus their attentions on different parts of the world.

## Functionality & MVP

In Media Bias users will be able to
* Select different news outlets from a drop down menu
* View a live heatmap of news coverage for that news outlet

### Bonus:
* Users will be able to see a full day news coverage sped up into 10 seconds to better visualize media coverage bias over a longer term.

## Wireframes

Media bias will consist of a single screen with the world map on display, a drop down menu, a description modal, and links to my GitHub and LinkedIn. Bonus features will include the ability to specify a timeline over which to view news updates.

![](./NYTimes-sample)
Sample visualization of New York Times media coverage

![](./BBC-sample)
Sample visualization of British Broadcasting Company media coverage

![](./LATimes-sample)
Sample visualization of Los Angeles Times media coverage

## Architecture and Technologies
Media bias will be implemented with:
* Vanilla Javascript
* HTML5 Canvas for DOM manipulation and rendering
* NewsAPI for media coverage data
* Webpack to bundle and serve scripts

## Implementation Timeline

#### Over the weekend
- [ ] Conceptualize project
- [ ] Build out Readme and wireframes
- [ ] Request API Key

#### Day 1
- [ ] Feasibility meeting
- [ ] Render the world map
- [ ] Test API calls

#### Day 2
- [ ] Display data to the worldmap

#### Day 3
- [ ] Include dropdown to switch sources

#### Day 4
- [ ] Include styling and improve user experience

### Bonus Features
- [ ] Change timeframe
- [ ] Implement other visualizations of the data
