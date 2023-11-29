---
Duration: ~~1 hour~~
Audience: Writers et al
Host: Write The Docs
Event: https://md.engineer/wtd-dc
---

# docs-as-code | Presentation

<details>

<summary>Context</summary>

## How I got to present to WTD Kenya community

1. A WTD Member called me (referred by a mutual friend)
2. We talked about Technical writing as a career
3. Mentioned `docs-as-code` was a knowledge gap for him and others
4. I get introduced to WTD Kenya community
5. We schedule a date
6. Event is postponed (I had an unforeseen commitment)
7. Event is held on Aug 1 2023, at 7PM EAT

</details>

## About Stan

![About](LinkedIN%20screenshot.png)

Contact: [md.engineer/contact](https://md.engineer/contact/)\
Web Profile: [md.engineer](https://md.engineer/)\
My writing: [md.engineer/writing](https://md.engineer/writing)

> Unfortunately I couldn't get a great excerpt from the recording to share. The notes here will have to do.

### Software Engineering and Digital Products professional

- 7+ years professional experience
- Software Engineering
  - Full-Stack
  - Team Lead
  - DevOps
- Digital Products
  - Product Management
  - Content (Docs and UX writing)

## Docs-as-code

[Docs-as-code (by WTD WriteTheDocs)](https://www.writethedocs.org/guide/docs-as-code/)\
**Philosophy where documentation is treated as code**\
Documentation as Code (Docs as Code) refers to a philosophy that you should be writing documentation with the same tools as code

For purposes of this session I'll handle three main areas; Markdown as a format, Git for version control, and GitHub as the platform.

## Table of Contents

- [Content format - Markdown](#markdown)
- [Version control - GIT](#git)
- [Platform - GitHub](#github)
- [Advanced](#advanced)

## Markdown

Syntax and Tool

- Syntax - Great formatting syntax for web-writers
  - a plain text formatting syntax for web-writers that's:
    - easy to write
    - readable and publishable as-is (like plain text, without being **marked up** with tags or formatting instructions)
    - easily converts to structurally valid HTML
  - First time using Markdown?
    - [Help](https://commonmark.org/help/)
    - [Tutorial](https://commonmark.org/help/tutorial/)
    - [Guide](https://www.markdownguide.org/)
    - Use [Dillinger](https://dillinger.io/) to show common
  - Note:
    - Some editors/markdown processors support [HTML](https://www.markdownguide.org/basic-syntax/#html) and other extended syntax
- Tool - Tools that support MarkDown:
  - [Dillinger](https://dillinger.io/)
  - [Docs to Markdown](https://workspace.google.com/marketplace/app/docs_to_markdown/700168918607) (Google Docs add-on)
  - [Obsidian](https://obsidian.md/)
  - Notion
  - Coda
  - Trello
  - Discord
  - Slack
  - Ghost
  - GitHub pages - Jekyll

  VS Code - Code editor (We'll use moving forward)

## GIT

[Version Control](https://www.atlassian.com/git/tutorials/what-is-version-control)

- Version Control
  - A case for 'versions'
  - Use Google Docs to show versions
  - A case for 'version control' - tracking and managing changes
  - git - a tool for controlling version

  In-depth content [about Git](https://git-scm.com/about).

- **git commits**

  _**commit** explained_ - You can play around, a time comes when you _commit_. git commit - commit a change/ version)

  [Getting started (Atlassian Tutorial)](https://www.atlassian.com/git/tutorials/setting-up-a-repository)\
  [VSCode inbuilt Source Control](https://code.visualstudio.com/docs/sourcecontrol/overview)

  - `git init`
  - `git add .`
  - `git commit -m <commit-message>`
  - `git log`

  In-depth content [about git commits](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository).

- git branches

  _**branches** explained_ - A tree grows as one trunk then at a point (commit), then a branch/ branches grow. But, in git, the branch can join the main branch/ trunk)

  A branch is a separate linear series of commits (oversimplified, at least that's usually the intention).
  - `git checkout -b <branch-name>` (check-out (as in a ) branch out)
  - Multiple branches
    - alias [`glogat`](https://github.com/NdagiStanley/dotfiles/blob/main/.aliases#L17) (To show one-line commits with timestamps and a graph showing branching visually)

  In-depth content [about Git branches](](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)).

- Tools:
  - GitHub desktop
  - VSCode (Source Control)

## GITHUB

[GitHub docs](https://docs.github.com/get-started)\
[GitHub Training Manual](https://githubtraining.github.io/training-manual/#/)\
[Collaborating - (Atlassian Tutorial)](https://www.atlassian.com/git/tutorials/syncing)

- Distributed Git
  - Remote Git repository - GitHub
    - Create repository on GitHub web

      Alternatively run `gh repo create <repository-name> --public`

      **gh** - [GitHub CLI](https://cli.github.com/)

  - **PUSH and PULL** _explained_
    - PUSH to GitHub
    - PULL to local
- PR - Pull Request
  - Request: "Please **pull** these changes into this branch"

  Alternative name: MR - Merge Request (on GitLab)
  - Request: "Please **merge** these changes into your branch"

## Advanced

> In my opinion, deliberate, slow explanation is needed to fully explain this.
>
> I touched on these during the recording. Despite having more than 1 hour to cover it, I felt that time was still short and I rushed through it.
>
> In retrospect, this section deserves another presentation should the team at WTD have me (for their community)

### On Docs-as-code

- [Fast facts about docs as code at GitLab](https://about.gitlab.com/blog/2022/10/12/five-fast-facts-about-docs-as-code-at-gitlab/)
- [CloudFlare's docs-as-code-approach](https://blog.cloudflare.com/our-docs-as-code-approach/)
- [docs-as-code article by opensource.com](https://opensource.com/article/22/10/docs-as-code)
- [docs-as-code article by I'd Rather Be Writing](https://idratherbewriting.com/learnapidoc/pubapis_docs_as_code.html)
- [docs-as-code article by grab's engineering team](https://engineering.grab.com/doc-as-code)
- [docs-as-code article by Nordic APIs](https://nordicapis.com/what-is-docs-as-code-and-why-does-it-matter/)
- <https://www.docslikecode.com/>
- [Some common references and introductory content on Docs as Code](https://cchesser.github.io/docs-as-code/)

### On Technical Docs

- <https://diataxis.fr/> - A systematic approach to technical documentation authoring

### On Markdown

- [History](https://daringfireball.net/projects/markdown/) Version 1.0.1 in 17 Dec 2004
- Standard variation - [CommonMark](https://commonmark.org/)
- Markdown is a [lightweight](https://en.wikipedia.org/wiki/Lightweight_markup_language) | [markup language](https://en.wikipedia.org/wiki/Markup_language) for creating formatted text using a plain-text editor.
- It's both syntax and tool:
  - a plain text formatting syntax for web-writers that's:
    - easy to write
    - readable and publishable as-is (like plain text, without being **marked up** with tags or formatting instructions)
    - easily converts to structurally valid HTML
    - File extensions
      - `.txt` - [plain text file](https://en.wikipedia.org/wiki/Text_file)
      - `.md` - markdown
      - `.html` - HTML (Standard markup language for documents designed to be displayed in a web browser. Defines the meaning and structure of web content)
  - a software tool, written in Perl, that converts the plain text formatting to HTML
    - Nowadays, a number of editors have the a markdown processor in-built
- [Extended syntax](https://www.markdownguide.org/extended-syntax/)
  - Highlights
  - StrikeThrough
  - Task Lists

### On GIT

GIT is a free and open source distributed version control system

- [Atomic commits](https://encyclopedia.pub/entry/33301#:~:text=In%20the%20field%20of%20computer,is%20said%20to%20have%20succeeded.)
- Rebasing branches
  - Merge conflicts
- [Others](https://www.atlassian.com/git/tutorials/advanced-overview)

### On GitHub

- PR (Pull Requests)
  - PR tags
  - PR reviewers
  - PR checks
  - PR deploys
  - PR reviews with commits
  - PR - code sandbox
- Workflows
  - Draft (your branch)
  - In review (PR)
  - Published (main branch)
- Deployments
- Example of Workflows and Deployments using a Minimalistic SSG (Static Site Generator)
  - [Repository](https://github.com/NdagiStanley/VueDN) with automated deploys
  - [Deployment](https://vuedn.netlify.app/)
- [Writing on GitHub - Starter](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
- [Writing on GitHub - Advanced](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting)
