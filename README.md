# collegefootballregression_basic

Running regressions on different college football stats (offensive) and exploring their relationship to PPG.

The main goal of this mini-project was to determine what major offensive statistics are the best explanatory variables for points per game (PPG). The hypothesis was that the follow explanatory variables (in no particular order) would best predict PPG: 1) yards per play (YPP), 2) yards per play with penalty yards (Penalty YPP), 3) yards per play with penalty yards and penalties included as plays (Advanced YPP), 4) Pass YPP, 5) Rush YPP, and 6) First downs per play (FPP).

If you read through the code you'll notice a few things:
  1. YPP is the best sole explanatory variable.
  2. Penalty YPP has little predictive power, while Advanced YPP (which includes penalty yards and treats penalties as plays) has pretty decent predictive power.
  3. It seems that penalties are more the product of random chance than coaching or player skill/intelligence, since including penalty yards and/or penalties as plays doesn't add much if any explanatory power to YPP.
  4. FPP is a close second to YPP in explanatory power.
  5. YPP and FPP together are the best predictor of offensive success (explain 75.0% of the variance in PPG according to Adj R-Squared).
