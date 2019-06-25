{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Title\n",
    "# The Effect of an Earthquake Generated Tsunami on Damage Numbers"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Could you please put these charts side by side?\n",
    "On the left:\n",
    "Title is:\n",
    "## Damage from Earthquakes that Generate a Tsunami\n",
    "<iframe width=\"900\" height=\"800\" frameborder=\"0\" scrolling=\"no\" src=\"//plot.ly/~dlromanoff/135.embed\"></iframe>\n",
    "\n",
    "## Damage from Earthquakes with no Tsunami Generated\n",
    "On the right:\n",
    "<iframe width=\"900\" height=\"800\" frameborder=\"0\" scrolling=\"no\" src=\"//plot.ly/~dlromanoff/133.embed\"></iframe>"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "I'll add explanations to this file within the next day."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.8"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

**Below the graphs:**

The graphs here give us some idea of the relationship between the damage caused by an earthquake that generates a tsunami, and one that doesn't. We can see only so much in the graphs. So, in addition to the graphs, below are some t-tests and p-values for each of the categories in the graphs above.

**Insert t-tests here**
T-Tests.png

In the order in which they appear, the t-tests above were comparing the relationship between an occurrance of a tsuanmi or not, and 1. Magnitude, 2. Deaths, 3. Missing, 4. Injuries, 5. Cost of Damage, 6. Houses Damaged, and 7. Houses Destroyed.

The null hypothesis: There is no significant difference between the damage caused by an earthquake that generated a tsunami and one with no associated tsunami.
 
 The p-value in all the tests except the first are greater than 0.05 which would lead us to not reject our null hypothesis. Deaths was the only one even close to 0.05 but still gave us a greater value.

 However, the first t-test gave us a significant result. The p-value was so small it would lead us to reject our null hypothesis and conclude there is a significance between magnitude and tsunamis occurring.

 The graph below shows the spread of the magnitude with and without a tsunami. 

 **Insert graph here**
 test_figure.jpeg