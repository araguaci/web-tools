
# 5 Dev Tools To Look Out For In 2022

## Deepsource, Appsmith, and more


![](https://miro.medium.com/max/1400/1*pkAZQPLM-OSCoxHYmfaHxw.png)

Image by the author

Can you believe that the past two years have shaken up the way we work? The beginnings were tough, but now, with the end of 2021 right around the corner, we are already used to remote working environments and expect the market to catch up with the new normal.

The demand for innovation and collaboration improvements for remote teams (and dev teams in particular) is probably one of the strongest trends we can currently observe in the industry.

In this short post I rounded up 5 relatively new dev tools that have recently been on my radar and I believe have the potential to improve our daily workflows.

[GitLive](https://marketplace.visualstudio.com/items?itemName=TeamHub.teamhub)
==============================================================================

🤕 **Pain:** Lack of communication tools designed specifically for developers

💡 **Solution:** GitLive — extend your IDE with real-time collaborative superpowers

Assuming your team uses Git then GitLive is a no-brainer enhancement of your IDE’s built-in Git functionality. Once installed it adds a team view showing all work in progress for each collaborator from your Git repository. Any non-stale branch ahead of master/main is considered work in progress and you can inspect diffs of the files changed as well as view the associated issue or pull request.

But my favourite feature is probably the automatic merge conflict detection. The difference between your local changes and the work in progress of your teammates is shown for your current open file in the gutter of your editor. It shows you the type of change (addition, deletion, modification or conflict) and you can inspect it to see the diff, what branch it’s from and even cherry-pick into your local file.

GitLive can be very useful for larger teams and especially useful for open or inner source projects as these features even work across forks. What’s also cool is as the data comes straight from Git, there’s no manual entry required to keep it up-to-date.

![](https://miro.medium.com/max/1400/0*bfo-uEOAcZCSGek0.png)

GitLive

[CodeSee Maps](https://www.codesee.io/)
=======================================

🤕 **Pain:** Sophisticated and dense codebases and a lack of shared understanding of how all the code and functionality map to each other.

💡 **Solution:** CodeSee Maps — a tool for developers to visually map their codebase.

CodeSee Maps provides auto-generated, self-updating code diagrams. They sync your codebase as code evolves so that you can quickly identify cross-code dependencies and navigate between files and folders. It can really improve your understanding of the codebase and guide onboarding, planning, and reviews. The tool is mainly targeted at developers, but it’s of great value for anyone who interacts with the team.

To get started using CodeSee Maps, you will need to authorize CodeSee on your GitHub user account, then install and authorize the CodeSee Architecture Diagrams GitHub action on the repositories you’d like to create maps for. At the moment they only support GitHub, but BitBucket and GitLab are both on the roadmap.

![](https://miro.medium.com/max/1400/0*mIzpRQA1DtkILkI3.png)

CodeSee Maps

[DeepSource](https://deepsource.io/)
====================================

🤕 **Pain:** Time-consuming code-reviews prone to a human mistake

💡 **Solution:** DeepSource — fast and reliable static analysis platform

DeepSource is a static code analyser that can help you with automating the code reviews and save your team a lot of time. It can find issues in the codebase and automatically submit PRs to fix them (and even evaluate incoming code in PRs and fix them too). Supported analyzers include, among others, Docker, Java, JavaScript, Go, Python, Ruby as well as PHP and SQL currently in beta. It integrates with GitHub, GitLab, and Bitbucket (self-hosted is also available).

There is also a possibility to deploy on-premise. How can it improve the way your team works? Their website states that using the tool can save 3.8 hours on an average per developer every week, so you do the math!

![](https://miro.medium.com/max/1400/0*BkC0dD4UqwIqx_6N.png)

[Appsmith](https://www.appsmith.com/about-us)
=============================================

🤕 **Pain:** The need for numerous CRUD apps within an organisation, which turns out to be a repetitive and often time-consuming task.

💡 **Solution:** Appsmith — an open-source framework to build internal tools.

Appsmith describes themselves as “The UI Tool for Busy Developers” and it really is that! It’s great for teams that build a lot of internal apps that are hosted inside their own infrastructure and firewall. You can easily build great-looking admin panels, workflows, and dashboards, by dragging and dropping pre-made, customizable widgets. You can integrate with any REST or GraphQL API and use JS or a library to create logic for your app.

![](https://miro.medium.com/max/1400/0*BXt7SwzJUsrG18zM.gif)

Appsmith

[WayScript](https://wayscript.com/)
===================================

🤕 **Pain:** Setting up internal tooling and applications is time-consuming and keeps developers from the actual problems they are trying to solve.

💡 **Solution:** WayScript — the fastest way to turn your local code into a hosted app.

WayScript is a development hub for internal tools. It provides pre-configured containers that you can build into so that the code works with your team’s existing infrastructure. You can quickly set up APIs (which traditionally is a long task, but also a must for technical customers), servers, cron tasks, custom inpoints, interfaces, and more. When the tool is ready you can deploy it with one click and send it to your team. You can use it by downloading the local app or via the web application.

![](https://miro.medium.com/max/1366/0*X-_ZnZBK6RDDbF8y.png)

WayScript

We can’t be sure what 2022 will bring, but I am positive that trends we’ve seen evolving in the past months will continue to grow. I hope some of the tools I proposed in this article will help improve your workflows and make a transition to a remote working setup smoother.

[Thanks toAnupam Chugh](https://betterprogramming.pub/5-dev-tools-to-look-out-for-in-2022-713f94c0f3cf)
