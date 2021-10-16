## Women Who Code + Hacktoberfest 2021

**Website:** [https://womenwhocode.github.io/hacktoberfest21/](https://womenwhocode.github.io/hacktoberfest21/)

This repository contains the code for the website for resources and projects worked on by communities within [Women Who Code](https://www.womenwhocode.com/) for [Hacktoberfest 2021](https://hacktoberfest.digitalocean.com/).

Please refer to the [website](https://womenwhocode.github.io/hacktoberfest21/) for resources to contribute to open source, talks from people in the community around open source, and beginner projects to learn and practice for Hacktoberfest 2021.

This website has been built using [Jekyll](https://jekyllrb.com/) and hosted in [GitHub Pages](https://pages.github.com/).

### Contribution Guidelines

To contribute to this repository, please follow the steps below:
1. Fork the repository
2. Clone the repository to your local machine
3. Make the changes you would like to contribute.
4. Commit and push your changes to your fork.
5. Create a pull request to this repository with a description of what you have done.
6. One of the repository contributors will review and merge if we agree that we would like to include your changes.

### Areas to Contribute

You can help contribute in various ways:

1. Beginner Friendly Repositories:  For any of the technical stack, if you come across any repositories which you believe will be a great start for beginners, do add them to the respective tabs(Python, Cloud, Mobile, Frontend, Data Science, Blockchain). You can check if the repositories are beginner-friendly if:
    - They have a good structure for contribution. This means code is readable and it is ready for folks to start raising PRs
    - They are actively responding to issues and merging PRs
    - If they have a good issues raised

      If the repository is simple, but has good activity, it is perfect candidate
  
2. Blogs: Open Source Friendly: If you have written any blogs on open source contributions,do send them our way and we would love to feature them. If you want to directly add it to the repo,follow the steps:

      - go to _posts folder
      - Convert your blog to markdown 
      - Add the following on top:

        `  ---
          layout: post
          title:  "Your title"
          author: "Your name"
          ---`
      - Name your file as `date of publishing-name` for example "2021-10-07-beginners-checklist.md"
      - Add it to a separate branch
      - And don't forget to add the `hacktoberfest` tag

### Local setup

You will need to install Jekyll on your machine following the instructions on their [website](https://jekyllrb.com/docs/installation/).

Once it is installed, you can run Jekyll by executing the command:
`bundle exec jekyll serve`

Go to `http://localhost:4000/hacktoberfest21/` (don't forget that trailing `/` at the end!) to see what the website looks like as you make your changes.

