---
title: Contributing to OpenCogData
date: 2023-12-03 00:00:00
---

Contributions to OpenCogData are welcome! All of the code is managed through the [GitHub repository](https://github.com/nimh-dsst/opencogdata).

<h2 style="margin: 1em 0em 0.5em 0em">How to submit a dataset</h2>
There are three main ways you can submit a dataset for entry to OpenCogData, which are described in turn below. Note that they are ranked in order of preference, from most preferred to least preferred, by the maintainers of OpenCogData.

<h3 style="margin: 1.33em 0em 0.5em 0em">1. Fill out the Google form</h3>
Have a dataset to submit? Fill out this form: <a href="https://forms.gle/N87Dqhs73vbfoPec8" target="_blank">https://forms.gle/N87Dqhs73vbfoPec8</a>

<h3 style="margin: 1.33em 0em 0.5em 0em">2. Submit a pull request</h3>
To directly add a dataset yourself, you can open a pull request on Github. First you should fork the OpenCogData library via GitHub and make modifications on your fork. The OpenCogData database is written in <a href="https://www.markdownguide.org/cheat-sheet/" target="_blank">markdown</a> using a standardized, easy-to-copy <a href="https://github.com/nimh-dsst/opencogdata/blob/docs/templates/post.md" target="_blank">template</a>. To add a dataset, add a markdown file named with the format `{firs_authors_last_name.lower()}{year}.md` to the `source/contribute` directory. Once your modification is complete, submit a pull request to merge your changes into the docs branch of OpenCogData. Pull requests will be reviewed by the maintainers.

<h3 style="margin: 1.33em 0em 0.5em 0em">3. Open an issue</h3>
To flag a dataset for entry into the database, you can open a <a href="https://www.github.com/nimh-dsst/opencogdata/issues/new" target="_blank">new issue via GitHub</a>. Please provide a link to a repository for the data and, if available, a link to a corresponding manuscript describing the data.
