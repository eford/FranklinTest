<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Eric Ford"
prepath = "FranklinTest"
mintoclevel = 2
auto_code_path = true
hasplotly = false

# Code fore 
course_num    = "Astro 497"
semester      = "Fall 2022"
instructor    = "Eric Ford"
institution_abbr   = "PSU"
institution        = "Penn State"
institution_full   = "The Pennsylvania State University"
dept_abbr          = "Astro"
dept               = "Astronomy & Astrophysics"
dept_full          = "Department of Astronomy & Astrophysics"

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Data Science Applications to Exoplanets"
website_descr = institution * " " * course_num * " (" * semester * ")" # "Penn State Astro 497 (Fall 2022)"
website_url   = "https://eford.github.io/FranklinTest/"
website_repo  = "https://github.com/eford/FranklinTest"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
