+++
author = "Vedant Bhutra"
shortauthor = "Vedant Bhutra"
jobtitle = "MS student @ IISER Bhopal"
affiliation = ""
affiliation_link = ""
twitter_user = "https://twitter.com/v_bhutra"
github_user = "https://github.com/vedant-bhutra"
linkedin_user "https://www.linkedin.com/in/vedant-bhutra-9512a91a5"

mintoclevel = 2
ignore = ["node_modules/", "franklin", "franklin.pub"]

prepath = ""

hasplotly = false
hasmermaid = false

# Set global variable `dateformat` to `"post"`, `"yearmonth"`, or `"year"`
# The expected file structures are
# - `"yearmonth"`: posts/YYYY/MM/name-of-post.md
# - `"year"`: posts/YYYY/name-of-post.md
# - `"post"`: posts/name-of-post.md
dateformat = "yearmonth"
# RSS setup
website_title = "Vedant Bhutra | Homepage"
website_descr = "Personal homepage of Vedant Bhutra."
website_url   = "https://vedant-bhutra.github.io/"
+++

\newcommand{\callout}[1]{~~~<div class="alert alert-note"><div>~~~#1~~~</div></div>~~~}

\newcommand{\icon}[1]{~~~<i class="fas fa-~~~!#1~~~"></i>~~~}

\newcommand{\style}[2]{~~~<span style="!#1">!#2</span>~~~}

\newcommand{\twosidebox}[1]{
    ~~~
    <div style="
            border-style: hidden hidden hidden solid;
            border-image: 
                linear-gradient(
                    to bottom, 
                    var(--tertiary-color), 
                    rgba(0, 0, 0, 0)
                ) 1 100%;
            padding: 1em;
            margin-top: 0.5em;">
        !#1
    </div>
    ~~~
}