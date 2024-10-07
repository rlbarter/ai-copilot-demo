# Code like a pro with AI and GitHub Copilot


This repo contains the materials for my "Code like a pro with AI and GitHub Copilot" workshop for R Ladies Philly, October 9, 2024.


## Getting set up

Most of the things I cover in this demo require some setup. Note that GitHub Copilot is not free and you will need a subscription to use it. You do not need to have a subscription to attend the demo though! I will also mention a *free* alternative to Copilot, called *Codium*.

If you do want to get set up to use GitHub Copilot yourself, here's what you need to do to get started.



### GitHub Copilot (requires github account with copilot enabled subscription)

**Cost** (for an individual): [$10 USD per calendar month or $100 USD per year.](https://docs.github.com/en/copilot/about-github-copilot/subscription-plans-for-github-copilot)

**Instructions**:

1. [Sign up for a GitHub account](www.github.com)

2. [Sign up for GitHub Copilot](https://copilot.github.com/) (you will probably want to sign up for an individual account)

[Note that GitHub Copilot is free for verified students, teachers.](https://github.com/education/students)

Also note that your company or institution may have a business or enterprise account.



### R and RStudio

**Cost**: free/open source

**Instructions**: To get started with R and RStudio, you'll need to install both. You can download both by clicking on the links on the [posit website](https://posit.co/download/rstudio-desktop/).

#### Setting up GitHub Copilot in RStudio

In RStudio, you will need to enable GitHub Copilot (*note:* You will need an active Copilot subscription for this to work--see above). To do this:

1. Navigate to Tools > Global Options > Copilot.

2. Check the box to “Enable GitHub Copilot”.

3. Download and install the Copilot Agent components.

4. Click the “Sign In” button.

5. In the “GitHub Copilot: Sign in” dialog, copy the Verification Code.

For more instructions [click here](https://docs.posit.co/ide/user/ide/guide/tools/copilot.html)

### R and VS Code 

**Cost**: free/open source

**Instructions**: Since GitHub Copilot has limited functionality in RStudio, I will also showing the expanded functionalities of copilot that are available only in VS Code. 

You can download VS Code from the [VS Code website](https://code.visualstudio.com/).

#### Setting up GitHub Copilot in RStudio

Inside VS Code, to use R and GitHub Copilot, you will need to install the following extensions:

- GitHub Copilot (this will also install the GitHub Copilot Chat extension)

- R extension for VS Code

For instructions on installing extensions in VS Code, [click here](https://code.visualstudio.com/docs/editor/extension-marketplace).



### Free alternative to Copilot: Codeium

**Cost**: free/open source

**Instructions**: Codeium is an alternative to GitHub Copilot that is free. Like Copilot, Codeium is typically used in VS Code.

To get started with Codeium, you will need to 

1. Make a Codeium account at [codeium.com](https://codeium.com/)

2. Install the Codeium extension in VS Code.

## Data source

In this demo, I will be using the publicly available 2021 Hospital Provider Cost Report from CMS. 

This data is gathered from the hospital annual cost report information maintained in the Healthcare Provider Cost Reporting Information System (HCRIS). The data does not contain all measures reported in the HCRIS, but rather includes a subset of commonly used measures.  

The data was downloaded from https://data.cms.gov/provider-compliance/cost-report/hospital-provider-cost-report (see website for more information on the data).