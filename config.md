<!--
Add here global page variables to use throughout your
website.
The website_* must be defined for the RSS to work
-->
@def website_title = "Food in Society at Harvard"
@def website_descr = "Learn more about research and literature surrounding Food in Society at Harvard University."
@def website_url   = "https://projects.iq.harvard.edu/foodinsociety/"

@def author = "<a href='https://scholar.harvard.edu/logankilpatrick'>Logan Kilpatrick</a> and <a href='https://ancientstudies.harvard.edu/people/janling-fu'>Janling Fu</a>"

@def mintoclevel = 2

@def prepath = "FoodInSociety"

<!--
Add here files or directories that should be ignored by Franklin, otherwise
these files might be copied and, if markdown, processed by Franklin which
you might not want. Indicate directories by ending the name with a `/`.
-->
@def ignore = ["node_modules/", "franklin", "franklin.pub"]

<!--
Add here global latex commands to use throughout your
pages. It can be math commands but does not need to be.
For instance:
* \newcommand{\phrase}{This is a long phrase to copy.}
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
