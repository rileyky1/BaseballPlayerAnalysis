# BaseballPlayerAnalysis

## Overview

The purpose of this analysis is to provide information on two new pitchers for the coaches to review. The raw pitch data is provided in a excel file in CSV format, loaded into Python Jupyter Notebook, explored using pandas dataframes and visualized using matplotlib.


## Player A

Player A is working with an arsenal of six pitches. His go-to pitch is a 93.3 MPH four-seam fastball that he throws at a 39.8% frequency. He has a good distribution off-speed pitches primarily consisting of a slider, curveball and changeup thrown at a frequency of 25.2%, 19.7% and 10.3%, repectively. Player A will also mix in a cutter and sinker at a low frequency of 4.5% and 0.6%, respectively. 

![PlayerA_PitchCount](Analysis/PlayerA_PitchCount.png)

![PlayerA_PitchSummary](Analysis/PlayerA_PitchSummary.png)


## Player B

Player B is working with an arsenal of four pitches. His go-to pitch is a 93.5 MPH four-seam fastball that he throws at a 49.3% frequency. Off-speed pitches primarily consisting of a slider and changeup thrown at a frequency of 31.9% and 14.8%, repectively. Player B will also mix in a curveball at a low frequency of 4%. 

![PlayerB_PitchCount](Analysis/PlayerB_PitchCount.png)

![PlayerB_PitchSummary](Analysis/PlayerB_PitchSummary.png)


## Recommendation
Based on the information I provided in this analysis I would say Player A has the better weapons in his pitching arsenal over Player B. For example, both players have similar four-seam fastballs in terms of velocity, but Player A has a higher spin rate and more break. For how much Player B utilizes the fastball at nearly 50% utilization, it would need to be more effective in terms of spin rate and break.


Additional analysis options to include:
There are a plethora of visuals I could create with the pitch data CSV. A few things I would implement in the future would be Ball%, Called%, Foul%, Swinging% and InPlay% based on pitch type. I would also love to graph each pitch based on pitch type and even try to immplement the result of those pitches when hit in play.
