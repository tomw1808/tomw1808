### Hi there 👋

I'm Thomas, a hands-on CTO for regulated fintech in Europe. More on [thomaswiesner.com](https://thomaswiesner.com).

🔭 I’m currently working on
 - [Assetera](https://assetera.com) as CTO: a MiFID II licensed investment firm for tokenized securities
 - [flash-agents](https://github.com/tomw1808/flash-agents): let Claude Code steer while cheap workers do the typing
 - [PrivateGoat](https://privategoat.app): a local-first meeting and Jira assistant for macOS
 - [Blockchain Courses](https://ethereum-blockchain-developer.com)

# 2026 - Regulated Fintech, Azure, and AI-native Engineering

It's October 2026, and the last four months were the most intense of my career.

In June I became CTO of [Assetera](https://assetera.com), a European investment firm licensed under MiFID II. In four months we rebuilt the complete stack: about 15 TypeScript services, six Next.js frontends, Keycloak for identity, KYC and compliance built into the product, and on-chain settlement of tokenized stocks on four chains. After years on AWS and CloudFormation, I moved a whole Azure estate into OpenTofu with keyless deploys, and wrote 44 architecture decision records along the way. DORA and MiFID II are now part of my daily vocabulary. I wrote the method down as an [execution playbook](https://thomaswiesner.com/playbook).

I merged more than 950 of my own pull requests in that time. That only works with AI agents doing the reading and the typing while I keep the architecture and review every diff. Out of that came [flash-agents](https://github.com/tomw1808/flash-agents), a Claude Code plugin that hands bounded tasks to a much cheaper model, runs each job in a disposable copy of the repo, and gives back a git patch instead of a story.

I also sit in a lot of meetings now. So I built [PrivateGoat](https://privategoat.app), a native macOS app that records and transcribes calls on the Mac with whisper.cpp, summarises them with a local model, and turns action items into Jira tasks. Your meeting audio never leaves the machine. It's a free beta via Homebrew.

After six years as CTO, I left Morpher in May 2026. Permissionless, the stablecoin project with the post-quantum privacy layer, is on ice for now. I'm still a co-founder.

# 2025 - More Blockchains, Markdown, Education and tools

It's May 2025 and the year is in full swing. I was so busy that I didn't find the time to update this brief overview, but that's changing right now. So what have we achieved so far?

A long standing issue of my learning platform ethereum-blockchain-developer.com was that its built on MkDocs-Material. It's awesome, but static. I am long time contemplating migrating it to nextjs, but its about 300 pages with very distinct syntax and features. That's why I started building a drop-in replacement in Nextjs: https://mkdocs-shadcn.org - However, at the end I decided to semi-abandon this project for nextra4. I am therefore focusing my efforts into making nextra4 a breeze to use including a [migration drop-in replacement script](https://www.mkdocs-shadcn.org/blog/20250420)

I am very busy working on a new kind of Stablecoin that balances algorithmic on-chain properties and hard off-chain promises. More on that a bit later.

We moved Morpher from our proprietary plasma sidechain to Base. Quite an undertaking.

In honor of the old Truffle Dashboard I sat down one weekend and coded an [alternative Foundry-Dashboard](https://www.npmjs.com/package/foundry-dashboard) that even decodes the transactions based on the ABI from the Foundry Build-Artifacts.

# 2024 - RAG+LLMs, Account Abstraction, (Swing) Trading
I started toying around with RAG+LLMs. My Masters Thesis included a lot of text processing, which comes in handy. I am currently playing with Jan.ai, Nitro and many more or less off-the-shelf products to summarize daily news to get actionale bullet points. 

I am also trying to get into Swing Trading. I always did trade based on fundamental news, but never tried to get entries and exits right. Currently reading Bob Volman -  Understanding Price Action.

I also finally read up on ERC4337 - Account Abstraction and made a [litte video](https://youtu.be/v_V4Wqcn7vE) about it. 

# 2023 - CloudFormation, NextJS
2023 was a big year for me. I finally got to fully learn Infrastructure as Code. The Morpher Infrastructure is now fully coded in yml files. 

Furthermore, I was trying to use Cloudformation in a special way: Building preview environments that clone production: RDS, ECS, Codepipelines with multi-arch builds, Fargate/Spot with EC2 in the mix, and many more. I am a big fan of Vercels previews. I am actively trying to bring them into my workflow with AWS CodePipeline and ECS.

I also started to use NextJS, Tailwind and Framer-Motion. I like those animations a lot.

💬 Ask me about anything, I'm always happy to help.

📫 How to reach me: me at [thomaswiesner.com](https://thomaswiesner.com)

⚡ Fun fact: The best place in the world to see rainbows is in Hawaii. But I have never been there.


### Languages

![Solidity](https://img.shields.io/badge/-Solidity-000?&logo=Solidity&style=flat-square)
![JavaScript](https://img.shields.io/badge/-JavaScript-000?&logo=JavaScript&style=flat-square)
![TypeScript](https://img.shields.io/badge/-TypeScript-000?&logo=TypeScript&style=flat-square)
![HTML](https://img.shields.io/badge/-HTML-000?&logo=HTML5&style=flat-square)
![Java](https://img.shields.io/badge/-Java-000?style=flat-square&color=000)
![SQL](https://img.shields.io/badge/-SQL-000?&logo=MySQL&style=flat-square)
![PHP](https://img.shields.io/badge/-PHP-000?&logo=PHP&style=flat-square)

### Technologies

![AWS](https://img.shields.io/badge/-AWS-000?&logo=Amazon-AWS&logoColor=FF9900)
![Docker](https://img.shields.io/badge/-Docker-000?&logo=Docker)
![ECS](https://img.shields.io/badge/-ECS-000?&logo=Amazon-ECS&logoColor=FF9900)
![Cloudformation](https://img.shields.io/badge/-Cloudformation-000?&logo=Amazon-Cloudformation&logoColor=FF9900)
![Linux](https://img.shields.io/badge/-Linux-000?&logo=Linux)
![Node.js](https://img.shields.io/badge/-Node.js-000?&logo=node.js)
![React](https://img.shields.io/badge/-React-000?&logo=React)
![Next.js](https://img.shields.io/badge/-Next.js-000?&logo=next.js)
![Redis](https://img.shields.io/badge/-Redis-000?&logo=Redis)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-000?&logo=RabbitMQ)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-000?&logo=PostgreSQL)
![Lucene](https://img.shields.io/badge/-Elasticsearch-000?&logo=Elasticsearch)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-000?&logo=Ubuntu)

### Tools and Platforms

![VSCode](https://img.shields.io/badge/-VSCode-000?&logo=Visual-Studio-Code&style=flat-square)
![Windows Terminal](https://img.shields.io/badge/-Terminal-000?&logo=Windows-Terminal&style=flat-square)
![Adobe Premiere](https://img.shields.io/badge/-Premiere-000?&logo=Adobe-Premiere-Pro&style=flat-square)
![Adobe Lightroom](https://img.shields.io/badge/-Lightroom-000?&logo=Adobe-Lightroom&style=flat-square)
![Adobe Photoshop](https://img.shields.io/badge/-Photoshop-000?&logo=Adobe-Photoshop&style=flat-square)
![Asana](https://img.shields.io/badge/-Asana-000?&logo=Asana&style=flat-square)
![Notion](https://img.shields.io/badge/-Notion-000?&logo=Notion&style=flat-square)
![Jira](https://img.shields.io/badge/-Jira-000?&logo=Jira&style=flat-square)
![Keybase](https://img.shields.io/badge/-Keybase-000?&logo=Keybase&style=flat-square)
![Zoom](https://img.shields.io/badge/-Zoom-000?&logo=Zoom&style=flat-square)
![Camtasia](https://img.shields.io/badge/-Camtasia-000?&logo=Camtasia&style=flat-square)
![Udemy](https://img.shields.io/badge/-Udemy-000?&logo=Udemy&style=flat-square)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-000?&logo=Cloudflare&style=flat-square)
![GitHub](https://img.shields.io/badge/-GitHub-000?&logo=GitHub&style=flat-square)
![Bitbucket](https://img.shields.io/badge/-Bitbucket-000?&logo=Bitbucket&style=flat-square)

