# Getting Started with Positron: A Next-Generation IDE for data science

This repo hosts materials for a half-day introduction to Positron for Python and R users at SDSS 2026 in Milwaukee, WI.

## Abstract

Positron is a next-generation data science IDE built by Posit PBC that combines the best features of RStudio and Visual Studio Code. This tutorial will introduce Python and R users to Positron’s core capabilities, with a special emphasis on helping RStudio and VS Code users while highlighting its seamless integration with the respective language ecosystems. For R programmers coming from RStudio, Positron delivers a familiar yet enhanced environment for data analysis and package development, while offering a path to Python when needed. For Python programmers coming from VS Code, Positron offers data science specific enhanced capabilities for exploring and analyzing data, authoring, and publishing. Unlike traditional software-development oriented IDEs, Positron provides first-class support for data science-specific workflows through its native support for R and Python, along with designated, integrated UI for exploring for Variables (Environment), Connections, Plots, Help, and more.

Participants will learn how to set up Positron for their data science work and navigate its interface. They will gain practical experience with Positron’s data-focused tools including the Variables pane, Data Explorer, and Plot viewer. They will also get to try Positron’s AI powered tools such as the built-in Positron Assistant and the Databot extension. By the end of the tutorial, participants will be able to customize Positron to maintain their familiar RStudio and VS Code workflow patterns while gaining access to new capabilities and understand how to effectively transition their R or Python-based data science projects to this new environment.

## Prerequisites

* Required: Experience with R and/or Python
* Nice to have: Experience with RStudio and/or VS Code

## Acknowledgement

Much of the materials for this workshop are based on the half-day Positron workshop developed by Jenny Bryan, Mine Çetinkaya-Rundel Julia Silge, Charlotte Wickham, and Hadley Wickham.

## Workflow

Preview the website locally with:

```bash
quarto preview
```

Modules need a landing page in `modules/` and a slide deck in `slides/`---these files should have the same slug. 
Use the `include` shortcode to include the slide deck on the landing page:

```markdown
{{< include _slides.md >}}
```

The rest of the landing page can be used for links, code, or other content you want easily accessible to participants.
