Assignment 1: Visualization Design by Pascal Brandt (psbrandt)
--------------------------------------------------------------

The task that this visualization attempts to assist with is that of gaining an
understanding of how the various age groups grew during the given 100 year
period. To assist in this process, I transformed the data so that each plotted
element is the proportion that the given age group grew during the period. This
takes the raw data and computes the value that we are actually interested in.
Each of these values is then plotted as a simple rectangle, enabling size by
side comparison of individual groups, as well as between genders.

I chose to use a form similar to that of the a traditional population pyramid.
This has the benefit of being familiar to viewers, which should remove any
cognitive effort required in understanding a new kind of visualization. However,
since I am plotting proportions instead of actual numbers, viewers may be
misled, since they may be used to seeing proportions of the whole population and
not growth. I've tried to address with issue in two ways. First I use the word
grew/growth repeatedly to emphasize the point. I also shown how much each group
has grown using the familiar 99x notation. The attempt at a humorous title
counteracts these efforts, but I decided to keep it for effect (considering the
audience).

While the data are quantitative, the specific values are less import than the
value of any one group relative to the others. For this reason I think the bars
used in the traditional population pyramid work well, since they use size to
encode the data, which has been shown to be one of the most effective encodings.
Further, gender stereotypes aside, the chosen colors are well understood, both
by the general public, as well as by those viewers familiar with population
pyramids. On the whole, ignoring the title, the question at hand is easily
answered using the generated visualization, which is both expressive and
effective.

I didn't end up incorporating external data sources. I did have some ideas, but
I decided to take this opportunity to learn some of the tooling that will
hopefully be helpful for the rest of this course and in the future. I used d3 to
bind my data to DOM elements, and I used SVG for plotting. All my work is
available in the live Observable notebook here: https://psb.re/cse512-a1.
