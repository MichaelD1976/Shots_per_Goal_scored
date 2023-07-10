### Shots_per_Goal_scored

This analysis examines how pre-match supremacy affects the rate of Home and Away shots on target per home and away goal scored and if teams who have a 'high' or 'low' % chance of winning a match have a different rate.

Data is taken from football-data.co.uk with a preprocessed sample of 153k UK and European football matches used.

Findings:

The rate of home and away SOT per home and away goal does vary non-linearly given initial pre-match supremacy and can be expressed as:

HST/H_Goal scored = -0.038.(Sup ^2) + 0.174.Sup + 3.348

AST/A_Goal scored = -0.032.(Sup ^2) - 0.084.Sup + 3.229


