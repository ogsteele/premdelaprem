---
title: tables
type: landing

sections:
  - block: markdown
    id: leaguetable
    content:
      title: League Table
      subtitle: Conferences A & B
      text: League Table below will be updated weekly following confirmation of points from Superbru. Green denotes qualification positions for the Championship Playoffs and red denotes qualification places for the Sacko Bracket <br />  <br />  ![screen reader text](leaguetable.png "League Table as of when i last updated it (usually monday night)")
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: datacharts
    content:
      title: Data Charts
      subtitle: 
      text: Below are a seriously of programmaticly generated plots that are automatically updated each week when the league table is updated, ie they're not curated, edited or fiddled with in any way - just data telling its own stories. They attempt to answer a couple of questions about the league. 
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: pointsscored
    content:
      title: Scoring Density
      subtitle: How much are players scoring?
      text: Density ridgelines depicting the distribution of points scored ranked by the sum of points scored <br />  <br />  ![screen reader text](ScoringDensity.png "Scoring Density Plot")
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: differences
    content:
      title: Points Difference
      subtitle: How do points difference compare across the league?
      text: Lollipop chart displaying the points difference grouped by conference <br />  <br />  ![screen reader text](DifferenceTab.png "Points Differences")
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: performance
    content:
      title: Relative Performance
      subtitle: What sort of matches have players had on average?
      text: A plot trying to graphically depict the story of each players season. Average points scored and conceded are illustrated by the dashed vertical and horizontal lines respectively. Best understood if you describe by the y axis first, then the x. For example, in the bottom left players quadrant have conceded less points than the average for the league, but also scored less - ie, even when conceding less than others, they still have not scored enough to win, hence missing their chances <br />  <br />  ![screen reader text](QuadrantPlot.png "Player Performance")
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: cumulativescoring
    content:
      title: Cumulative Scoring
      subtitle: How has the total number of points scored by each player grown over the course of the season?
      text: Very simplistic line plot illustrating the cumulative points scored total over the course of the season, round by round for each player <br />  <br />  ![screen reader text](CumulativeScoring.png "Cumulative Scoring")
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: historicalpositions
    content:
      title: Historical Positions
      subtitle: How have overall league points changed over the course of the season, irrespective of conference?
      text: Trailing dot plot of the league points scored after each week  <br />  <br />  ![screen reader text](HistoricalPositions.png "Points History")
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

---
