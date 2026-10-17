# AIAP Day 1 instructor script: Vishwas, India

Version 4 handoff draft, 17 October 2026. Vishwas delivers the India session. Slides are deferred.

For Vishwas: the spoken lines are a starting point written in Dileep's cadence. Say them your way and change the wording freely. Keep the sequence, the prompts and the checks. Swap in your own examples wherever you have them.

## Session at a glance

The main session is 150 minutes before breakout, including a 5-minute break. The host runs a 15-minute context-setting slot before this. That slot is outside the 150 minutes, so do not repeat the host's logistics in the opening.

Everything in the main session is instructor led. Learners practise in the final breakout. Keep chat and Q&A open during the demos.

| Time | Section | Minutes |
| --- | --- | ---: |
| 00:00-00:40 | 1. Ambition, the business review and personal instructions | 40 |
| 00:40-01:00 | 2. Connectors, MCP and Skills | 20 |
| 01:00-01:10 | 3. Browser automation inside a paid research site | 10 |
| 01:10-01:15 | Break | 5 |
| 01:15-01:55 | 4. Content: voice, brand and a few named skills | 40 |
| 01:55-02:25 | 5. Spreadsheet analysis and dashboard | 30 |
| 02:25-02:30 | 6. Review the outputs and brief the breakout | 5 |
| From 02:30 | 7. Final breakout | Duration to set |

Tools:

- ChatGPT for the opening, personal instructions, connectors, copy drafting and data analysis.
- A prepared local agent environment for frontend-slides and human-review.
- ChatGPT's browser (agent mode or Atlas) for the login-based demo.

Sign-ins, installs and connections happen before the session, not during it.

## Demo ground rules

- Show real output. If you show a prepared output, say it is prepared.
- Do not stage a failure. If the live answer is fine, say so and move on.
- A named skill counts as used only when the account shows it selected. Otherwise call it manual application.
- In every demo, check one thing against the source on screen.
- Troubleshooting limit: 2 minutes, then switch to the fallback. This limit is proposed. Confirm it in rehearsal.

## Preparation

None of this is done yet.

| Block | Prepare before delivery | Success check | Fallback |
| --- | --- | --- | --- |
| Business review | Small fictional notes file, the underlying figures and last week's review. Use IST. | One-page review. A decision and one figure trace back to the inputs. | Prepared output and source check |
| Personal instructions | [Template](https://docs.google.com/document/d/1H-bkjfVwOnsG9odmEsZp6GTcbHsO2C3eNdz2EMHltlY/edit?tab=t.0), your own answers, the settings path in your account, one "quiz me" line in your saved instructions | Draft reflects your answers. Uncovered sections stay visible. | Prepared settings screenshot |
| Connectors | Authorised channel or folder, date range, the permissions screen for that connector | Retrieved items match the scope. The saved skill runs on a second small input. | Dated export, labelled as prepared |
| Browser | A login-based site of your choice (paid subscription, X or similar), ChatGPT's browser signed in, topic, dates, empty reading log | Brief traces to an opened article. Repeat run skips the logged article. | Recording and source list |
| Content | Prepared Vishwas Voice skill (from your sent email or custom instructions), Outskill Slides installed, event brief, no-ai-slop and human-review installed | Copy and HTML slides follow the brief and the brand. A human-review edit survives a reload. | Prepared deck and recorded review loop |
| Data | Fictional support-ticket spreadsheet, data dictionary, independently checked answer sheet, Outskill Slides installed for the brand | Dashboard figures reconcile to source rows | Prepared dashboard and calculation walkthrough |

Preparation details are in the [setup notes](../resources/setup-notes.md). Links to every article and study are in [references](../resources/references.md).

Skills: each mentor builds and demos their own skills. This kit does not ship skill files. The scripts name the skills used in each demo and link the public originals.

## 1. Ambition, the business review and personal instructions

Time: 00:00-00:40, 40 minutes.

Task: a Monday business review from supplied notes and figures. No connectors yet.

Sources:

- [Felix Rieseberg, "How to be more ambitious", 13 October 2026](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/)
- [Miles Cranmer's talk on avoiding AI brain rot, 16 October 2026](https://x.com/MilesCranmer/status/2111105654211608847).
- [Mike Taylor, Every, 16 October 2026](https://every.to/also-true-for-humans/why-i-start-a-new-thread-in-claude-every-time)

### 1.1 Welcome and why default use is not enough

00:00-00:04, 4 minutes.

Say:

Hi everyone. I am Vishwas. Welcome to day one.

Today you will see how to brief AI properly, how to make it know you, how to connect it to your apps, and then how to use skills for content and data. By the end we will have a business review, a branded deck and a dashboard on screen. You will build your own version in the breakout.

So one thing I want you to understand first. Everybody has AI now. A couple of years back, using AI made you stand out. Now everyone has the same tools. Miles Cranmer, an assistant professor who works on AI for science, made this point in a talk recently. If you use AI the default way, your work gets better, but it starts looking like everyone else's. He said this year all the student presentations he assessed looked the same, down to the font and the colours.

There is research behind this. In one study, writers who got story ideas from AI wrote stories that were rated more novel. But the stories also became more similar to each other. Better on average, but the same.

So today is about using it beyond the default. For that I will use an article by Felix Rieseberg, who works at Anthropic. He gives four words: speed, altitude, depth and range. I will point to each one as we go.

Watch what I ask, what comes back and what I check. Questions go in the Q&A.

Facilitator note: Cranmer introduces himself as an assistant professor in the talk. It does not name his university, so neither does this line. Verify the story-study numbers before quoting any figure. The study is Doshi and Hauser, Science Advances, 2024 ([dataset](https://datadryad.org/dataset/doi:10.5061/dryad.qfttdz0pm)). The script deliberately quotes no number.

### 1.2 Altitude: what should the review help decide

00:04-00:12, 8 minutes.

Say:

Let me start the way most of us start on a Monday. I have notes, some figures and last week's review. I just ask for the review.

```text
Prepare my Monday business review using the supplied notes and figures.
```

Do: let it finish. Point to what it contains and what the manager still needs. Do not call it a failure before you read it.

Say:

Okay, this is a decent first draft. Speed asks how I do the same review faster. Altitude asks a different question. What should my manager decide after reading this? And should the review even look like this?

Think of a doctor. A good doctor does not prescribe from one line. They read the case file: your history, your allergies, what you have tried already. And they ask you questions. So I will move from a prompt to a brief. Who reads this, what they need to decide, and last week's review as the format.

```text
Use the supplied notes and figures to prepare a one-page review for my manager.

Identify important changes, unfinished commitments and decisions needing attention. Separate recorded facts from possible explanations. For each decision, show the practical options, relevant evidence and missing information.

Use the previous review as a format reference. Keep dates and figures accurate. Ask about gaps that would materially change the work; otherwise state your assumptions and proceed.
```

Do: compare the two outputs against the same source files. Point to the section that now asks the manager for a decision.

Say:

Same notes, same figures. The only thing that changed is what I asked for. One more thought. Could a weekly check catch these issues before Monday? I think it is worth testing. We will not build that today.

### 1.3 Depth: check the work like an expert would

00:12-00:22, 10 minutes.

Say:

Depth is about doing the work the way an expert would. An analyst would not trust the summary notes. They would open the figures. So let me check one conclusion against the numbers.

Do: open the underlying figures. Check one conclusion. If the data does not support it, say so.

Say:

See, why do I bother? Cranmer put it simply. You are 100% responsible for anything AI generates. AI cannot go to jail. If I send this to my manager and the number is wrong, the mistake is mine.

He had a story on this. He let an AI agent run on a research task for 14 hours. It came back and said every goal was met. He looked at the output and it was garbage. The agent was very confident. Only someone who knew the area could tell.

So before I ask for more, I want AI to tell me what analysis is missing and how I would check it. Then I decide if it is worth doing.

```text
Before revising this brief, identify any analysis the recipient needs that the request omits. Specify the source material required, the operations you would perform, and how I could independently check the result. Then propose the smallest useful revision to the brief. Do not expand the task without explaining why.
```

Do: point to the method it proposes. Say when a simple comparison is enough and when the question needs more data. Naming a role like "analyst" does not mean the analysis happened.

Context check, about 3 minutes.

Say:

One quick habit. When a conversation keeps going back to an old mistake, or the task has changed a lot, start a fresh chat. Mike Taylor at Every wrote that he starts a new thread every time. I would not make that a rule, but the idea is right. Old instructions and old mistakes stay in the thread and pull the answer back. So I ask for a handoff, I read it, and I start fresh.

```text
Prepare a handoff for this business review: current goal, agreed requirements, confirmed figures with source references, decisions and open questions. Flag conflicts and exclude superseded requests. I will check it against the source files before using it in a fresh chat.
```

Do: show the handoff. If the live thread is fine, use a prepared example of a drifting thread and say it is prepared.

### 1.4 Range: borrow checks from other fields

00:22-00:26, 4 minutes.

Say:

Range means borrowing from other fields. On the same review, I want an analyst to check the figures, a journalist to question the evidence behind each explanation, and an editor to make the ask clear. I am not asking for three writing styles. I want three different checks. Then we see which ones actually help.

```text
Review this draft three ways. As an analyst, check every figure against the supplied numbers. As a journalist, question the evidence behind each explanation. As an editor, make the decision request to my manager clear. List each issue with the line it relates to. Do not rewrite the draft yet.
```

Do: accept one useful change. Reject one the evidence does not support. Check the revised line against the source.

### 1.5 Personal instructions with the template

00:26-00:38, 12 minutes.

Say:

Now you might be wondering, how do I make AI know me, so I do not repeat all this every time? That is custom instructions. Dileep, who built this template, took almost 9 months of iteration to get his instructions to this point. You do not need 9 months. Here is a very simple recipe.

Do: show your saved instructions for a few seconds. Add this line to them before the session. Point to it:

```text
When I am learning something new, quiz me one question at a time. Give hints when I am stuck. Do not give me the answer unless I ask.
```

Say:

This line is there for a reason. There is a study from Turkey with about a thousand high school maths students. The group with plain ChatGPT did much better on practice problems. Then AI was taken away for the exam, and they did 17% worse than students who never had it. A second group had a version that gave only hints. They did about the same as the no-AI group on the exam. Anthropic found something similar with engineers learning a new coding library. The ones who asked AI to explain things scored much better on the quiz than the ones who just asked it for the code.

So when the output is the point, let AI do the work. When learning is the point, make it quiz you. You are in a 14-day program. Learning is the point.

Sources: [Bastani et al., PNAS 2025, via Knowledge at Wharton](https://knowledge.wharton.upenn.edu/article/without-guardrails-generative-ai-can-harm-education) and [Anthropic, 29 January 2026](https://www.anthropic.com/research/AI-assistance-coding-skills). Use these figures, not the ones quoted in Cranmer's talk.

Say:

This is the operating instructions template. It has 12 sections. You do not fill it by hand. You paste it into a new chat and AI interviews you, one section at a time. Priya in the filled example is fictional. Your answers are what make it yours.

Do:

1. Share the [template link](https://docs.google.com/document/d/1H-bkjfVwOnsG9odmEsZp6GTcbHsO2C3eNdz2EMHltlY/edit?tab=t.0).
2. Copy everything from "Interview prompt" to the end into a new chat.
3. Answer two rounds as yourself. After each round, point to how AI summarises what it has learned.
4. Stop early:

```text
Stop here. Based on what you have so far, give me the copy-and-paste instructions as one block.
```

Say:

Before I save this, I read it. Did it capture what I said? Did it add something I never said? I will correct those. Anything about this week's review stays in this week's brief. Instructions are for things that stay true for months.

Do: correct one unsupported detail. Show where to save it in ChatGPT, saying the menu path aloud. If settings cannot be reached, show the prepared screenshot and say saving is unfinished.

Say:

Try these for two weeks. Change a section when something keeps annoying you. Revisit every quarter, or when your role changes. You can finish the full interview in the breakout.

### 1.6 Recap

00:38-00:40, 2 minutes.

Say:

Quick recap. One, start from what the reader needs to decide, not from the task. Two, check one thing against the source before you trust it, because you own the output. Three, what stays true about you goes into instructions. What belongs to this task stays in the brief.

Next, we give AI tools.

## 2. Connectors, MCP and Skills

Time: 00:40-01:00, 20 minutes.

Task: pull a week of team updates from one channel or folder and turn them into a checked brief, then save that process as a skill. This adapts a demo from an earlier Day 1.

### 2.1 The chef: tools and recipes

00:40-00:44, 4 minutes.

Say:

So think about this. I am in a restaurant, I have a chef. The chef needs tools: an oven, a wok, a stove. And the chef needs recipes, the instructions to prepare a dish.

Now the chef has tools but no recipe. What happens? Put it in the chat.

Do: read two or three chat answers.

Say:

Now the opposite. A recipe but no tools. Nothing comes out. The chef comes back and says, I do not have an oven, but here is step 1, step 2, step 3. You have seen AI do this, right? "I cannot do this, but if you were to do it, here are the steps." That is a recipe with no tools.

For our AI, connectors are the tools. Skills are the recipes.

A connector lets AI talk to your applications: Gmail, Slack, Drive, Asana. MCP, Model Context Protocol, is the standard way these connections work. Think of it as one plug that fits many apps. You do not need to build anything today. You need to know what a connection can see and what it can do.

Do: show the connector controls in the account. Use the names the account shows.

### 2.2 Permissions: the library card

00:44-00:47, 3 minutes.

Say:

Now, is it safe to connect? Think of it like getting access to a library. A library card does not mean you read all the thousands of books. You ask for one book. The librarian checks. Do you have access? Can you take it home, or only read it there? Some books are only for lecturers, not students. If you touch a book that is locked for you, the librarian stops you right there.

Connectors work the same way. Each one has its own permissions. Look at what it can read and what it can change. When you start, approve each action yourself. Use it once, twice, thrice. Get confidence. Then slowly allow reads. Keep write access in your control.

One more thing. If an email or a web page has instructions written inside it, that is content, not your instruction. AI should not act on it.

Do: open the permissions screen for the connector you will use. Point to read access and to the actions that need approval.

### 2.3 Retrieve and check

00:47-00:53, 6 minutes.

Say:

I will start small. One channel, one week. I want a brief my team lead can use, with a link back to each message. Then we open one message and check.

```text
Use the connected [application] to read updates in [channel or folder] from [start date and time] to [end date and time], in IST.

Prepare a short brief for the team lead. Include decisions, blockers and actions explicitly recorded in that period. Link each point to its source. If an owner or date is missing, say so. Identify what you could access and any gaps.

Keep this as a draft for review.
```

Do: open one source item from the brief. Check whether the summary added a decision or an owner the source does not have.

Say:

This point is in the source. This one is an interpretation, so I will label it or remove it. If something did not come back, the fix is access or the input. Asking the same thing again will not fix missing access.

### 2.4 When to build a skill, then build one

00:53-00:59, 6 minutes.

Say:

Now, when do you build a skill? If it is a one-time task, a brief is enough. Somebody walks into your restaurant and wants a special dish. You do not write a recipe for that. You just make it.

When you do the same task 3 to 4 times, the process becomes clear. You know where the information comes from, what happens to it and what the output should look like. You have given feedback a few times and the output is consistent. That is when you say, build me the skill.

Cranmer adds one test I like. Can you explain and defend the output without the AI? Can you find its mistakes? If yes, delegate freely. If no, you are not ready to hand it over.

Today I will save this after one run so you can see how. In your own work, run it 3 to 4 times first.

Here is an example from Dileep's own setup. When he built a newsletter digest skill, the first run picked old issues and gave him two separate decks. He wanted the latest issues in one deck. That feedback went into the skill, not into the chat. Same method here.

```text
Create a skill called Team Update Brief from the process we just reviewed.

Use it when I ask for a brief from team updates. Require the source, date range and time zone. Read the relevant items, extract recorded decisions, blockers and actions, and retain source links. Flag missing owners and dates. Produce one draft brief for the stated reader.

Include the source checks we performed. If access is missing or retrieval is partial, report that limitation before drawing conclusions. Show me the instructions before saving them.
```

Do: read the generated instructions. Remove anything that belongs only to today. Save it. Start a fresh small request and select the skill explicitly. If the account cannot save or select it, paste the instructions and call it manual application.

### 2.5 Transition

00:59-01:00, 1 minute.

Say:

Connectors are the tools. Skills are the recipes. Next, a case where there is no connector at all: a site you have to log into.

## 3. Browser automation behind a login

Time: 01:00-01:10, 10 minutes.

Task: use ChatGPT's browser (agent mode or Atlas, whichever your account has) on a site that needs your login. Pick any site you already use and can show on screen. It does not have to be Dileep's example. The flow stays the same whatever the site: find a few items, read them, save a short brief and a log, then repeat to check the log works.

Pick one and rehearse it:

| Site type | Example task |
| --- | --- |
| A paid news or research subscription you have | Two articles on a topic, with a reading brief |
| X (Twitter), signed in as you | A few posts on a topic from a list or accounts you follow, with a short brief |
| Any other login-only site you use for work | Two saved items or reports, with a short brief |

Rules for whichever you pick:

- Read only. No posting, liking, following, messaging or buying.
- Use your own account. Do not show login details on screen.
- If a login, captcha or OTP appears, the agent pauses and you complete it.
- Check the site's terms on automated access. X restricts automation and scraping, so keep it to a small read-only demo on your own account, or pick another site.

General preparation is in the [setup notes](../resources/setup-notes.md#browser-demo).

### 3.1 When the browser is the right route

01:00-01:02, 2 minutes.

Say:

Some work sits behind a login. When I am signed in to [site], I can see it. But a normal AI search only sees what is public. So here I will use ChatGPT's browser with my signed-in session.

Same library rule as before. It uses my login, so it can see what I can see. I will stop it before it posts, submits or buys anything. And if a feed or a connector gives me the same material, I would use that for a regular job. The browser is for when the work needs the site itself.

Do: show one item that is only visible when signed in.

### 3.2 Run the reading workflow

01:02-01:07, 5 minutes.

Say:

Topic, dates, at most two items. A useful point from each and a link I can check. And a reading log, so the next run knows what is already done.

```text
Use ChatGPT's browser and my signed-in account on [site]. Read only. Do not post, like, follow, message or buy anything.

Find up to two [articles or posts] about [topic], published between [start date] and [end date], using IST for the date boundary. Use the site's search or browse controls and check dates yourself if there is no filter.

Open each item. Record title or author, publication date and link. Write a short note for each with one practical point and any limit in the evidence. Keep the author's claims separate from established facts.

Check the existing reading log and skip links already completed. Add the new entries and give me one short brief. Report what you read and anything you could not access. If a login, captcha or OTP needs my action, pause there.
```

Do: watch the navigation. If only a preview was readable, say so.

### 3.3 Check and repeat

01:07-01:10, 3 minutes.

Say:

I will open one link from the brief and check the date and the point it took. Then I will run a small repeat. It should skip the item it already logged. If it reads the same item again, the log handling needs fixing.

Do: verify one source point. Run the small repeat and show the skip.

Fallback: show the prepared recording and source list, and say which steps were prepared. If access is not back within 2 minutes, go to the break.

## Break

Time: 01:10-01:15, 5 minutes.

Say:

Five minutes. When we come back, we use skills for two kinds of work: content and data.

Do: have the voice skill, Outskill Slides and the agent environment open before resuming.

## 4. Content: voice, brand and a few named skills

Time: 01:15-01:55, 40 minutes.

Task: an Outskill AI office-hour invitation for professionals in India, a short message, and a three-slide HTML briefing in the Outskill brand. Pick the event facts during preparation.

Prepared by the mentor before the session:

- **Vishwas Voice**, built from your own sent emails through the Gmail connector, or from your custom instructions. Steps in 4.2.
- **Outskill Slides**, built before the session by combining Zara Zhang's frontend-slides skill with the Outskill website as the reference. Installed as `outskill-frontend-slides`. In class, demonstrate that process, then use the finished skill. Steps in 4.4.
- no-ai-slop and human-review installed.

In class, show how each prepared skill was made, then use the finished skill. Do not rebuild them live.

### 4.1 Skills are everywhere: skills.sh and the one-line install

01:15-01:19, 4 minutes.

Say:

So far we made our own skill. But you do not have to make every skill yourself. There is a directory called skills.sh with a lot of skills people have already built and shared. Writing, slides, design, coding, all kinds of things.

Today I will show you only a few. We will come back to skills in later sessions: how to pick them, how to adapt them, how to build your own properly.

Installing one can be as simple as this. Copy the link, paste it into your agent, and say "Install this skill." That is it.

Do: open [skills.sh](https://skills.sh) and scroll for a few seconds. Then, in the prepared agent environment, paste the line below and show the skill appear. Install it before class as well, in case this step is slow.

```text
Install this skill: https://github.com/petergyang/no-ai-slop
```

Note: skills.sh is run by Vercel. Its own install route is a command line. The paste route works in agents that can install from a link. In ChatGPT, use the account's Skills route.

### 4.2 Vishwas Voice: show how it was made, then the prepared skill

01:19-01:29, 10 minutes.

Prep: build this before the session. Use your own email or instructions, not Dileep's. Do not run the email version live on your real inbox, because the screen would show private emails. Show the prompt, then the prepared result.

Say:

Now I want the writing to sound like me. I have already built a skill for that, called Vishwas Voice. Let me show you how I made it, because you can do the same with your own email.

I connected Gmail, the same way we connected an app earlier. Then I asked it to read my sent emails, only the ones I wrote, and find how I write. How I open, how I explain a decision, how I close, which words I use and which I never use.

```text
Use my connected Gmail. Read the last 20 emails in my Sent folder that I wrote myself. Skip forwards, auto-replies, calendar responses and any text quoted from other people.

Build a voice profile: how I open, explain a point or decision, ask for something and close; sentence length; words and phrases I use often and ones I never use; how I write differently to my team, clients and senior people. Quote a short line as evidence for each point. Do not guess my personality or add a biography.

Show me the profile and wait for my corrections. Then save it as a skill called Vishwas Voice. The skill should read this profile, keep the facts of each task, adapt to the reader, and never invent personal stories, numbers or promises.
```

Say:

If you do not want to connect your email, there is another route. Your custom instructions from this morning already say a lot about how you like to write. You can start from those.

```text
Use my custom instructions as the starting point for a voice profile. Pull out everything about how I write and how I like things written for me. Mark what is missing that only real writing samples would show. Then show me the profile, wait for my corrections, and save it as a skill called Vishwas Voice.
```

Do: open the prepared profile. Read two lines aloud and point to the email line behind each. Point to one thing you corrected before saving. Use a real correction.

Say:

I read the first version before saving. Where it got me wrong, I corrected it. Always read the profile before you save it.

ChatGPT also has its own writing-style setting that learns from your connected apps. It does a similar job. The difference is that a skill is a file you can open, read and correct.

Do: show where the setting sits and say the path aloud. See the [writing-style setup notes](../resources/setup-notes.md#chatgpt-writing-style). Plan availability for this control is not confirmed.

### 4.3 Draft, then edit with no-ai-slop

01:29-01:35, 6 minutes.

Say:

I will draft the invitation and the slide copy with my voice skill. Then I will run Peter Yang's no-ai-slop skill on it. I want to see what it changes. If it cuts something useful or makes it sound less like me, I put that back.

```text
Use Vishwas Voice.

Draft an Outskill AI office-hour invitation and copy for a short HTML briefing for the audience in the supplied brief. Use the actual event facts and agenda. Flag missing details.

Then use Peter Yang's no-ai-slop skill to edit the copy. Make the minimum useful changes. Preserve facts, meaning and natural cadence. Check the revision against the skill's evaluation checklist and show a short note on what changed.
```

Do: compare one passage before and after.

### 4.4 Outskill Slides: show how it was made, then use it

01:35-01:49, 14 minutes.

This runs in the prepared agent environment, not a normal chat window.

Facilitator note: Build Outskill Slides before the session. Combine Zara Zhang's frontend-slides skill with the Outskill website as the reference, and install the result as `outskill-frontend-slides`. In class, demonstrate that process as well. Open the original skill, cue the Outskill website as the reference you built from, and show how the two were combined. Then use the skill you already built. Do not leave the build until the live session.

Say:

Remember Cranmer's point about every presentation looking the same. This is how we avoid it.

Outskill Slides is built by combining two things. The first is Zara Zhang's frontend-slides skill. It makes good HTML slides, but it does not know our brand. The second is the Outskill website. I use that site as the reference, and I build the skill from there: logo, colours, fonts, image style and tone. I pasted the skill link, I pasted the website, and I asked it to combine them. That is all it took.

Do: demonstrate the process on screen. Open Zara Zhang's [frontend-slides repository](https://github.com/zarazhangrui/frontend-slides), then cue the [Outskill website](https://www.outskill.com) and point to the brand details the skill should take. Show the prompt you already ran. Do not start a new build.

```text
Here is a skill: https://github.com/zarazhangrui/frontend-slides
Here is a brand website: https://www.outskill.com

Adapt the skill to this brand. Read the website and pick up the logo, colours, fonts, image style and tone. Keep the original skill's slide structure, navigation and checks, and keep its attribution. Create a new skill called Outskill Slides that combines the two. Do it in whatever way works here.

Tell me what you took from the website, and mark anything you guessed, such as a font name, as a guess.
```

Say:

To save time, I made this before the session. Here is the skill it created.

Do: open the installed Outskill Slides skill (`outskill-frontend-slides`). Point to its brand section: colours, fonts, logo. Check one colour against the website.

Say:

Adapting skills properly, with full brand guidelines and assets, we will take up in a later session. For now, let me use it.

```text
Use Outskill Slides to create a three-slide HTML briefing from the edited copy.

One purpose per slide: introduce the office hour, explain the agenda, and show how to join. Use only facts from the brief. Keep my wording.

Open the result, test navigation and check every slide for readability, clipping and missing assets.
```

Do: click through all three slides. Compare one slide with the website. Keep a prepared deck ready in case generation runs long.

### 4.5 Review it with human-review

01:49-01:55, 6 minutes.

Say:

Now I review the deck like I would review my team's work. I change one line directly and leave a comment on something that needs work. Then I send it back. The agent has to keep my exact edit and apply the comment to the source, so the change survives the next build.

Do: use [human-review](https://github.com/petergyang/human-review), installed before class. Make one text edit and one real comment. Select Send, retrieve the batch and apply it. Reload the deck and show the change.

Success check: the deck follows the brief and the brand, navigation works, and the edit survives a reload.

Fallback: prepared deck and the recorded review loop, labelled as prepared.

## 5. Analyse a spreadsheet and prepare a dashboard

Time: 01:55-02:25, 30 minutes.

Task: a fictional support-ticket spreadsheet. The team lead wants to know where workload is building up and where resolution is slow.

Skill: your own data-analysis skill, built and installed before the session.

Inputs: ticket ID, team, request type, opened time, resolved time, status, plus a data dictionary and an answer sheet calculated separately. Define any service target in the dictionary. Do not introduce a target live.

### 5.1 Start from the decision, then inspect the file

01:55-02:01, 6 minutes.

Say:

Same rule as the business review. Start from the decision. The team lead wants to know where requests are piling up and where they take longer.

Before any chart, I open the file. What is one row? Which period? What does "resolved" mean? These decide the calculations.

```text
Use Data Analysis to inspect this support-operations spreadsheet.

The decision is where the team lead should investigate workload and resolution delays. Start by describing the sheets, what one row represents, identifiers, dates, units and relevant definitions.

Check missing values, duplicates, inconsistent categories and invalid dates. Explain which issues affect the analysis. Preserve the original data. Show the proposed cleaning decisions and metric definitions before building the dashboard.
```

Do: open the workbook and the dictionary. Show the skill's steps, then select the skill.

### 5.2 Review the cleaning and define the metrics

02:01-02:08, 7 minutes.

Say:

I check what it wants to change. A duplicate ticket ID needs a look. A blank resolved time may just mean the ticket is still open. We should not fill it with an average to make the column look complete.

```text
Apply the cleaning decisions we approved and record them.

Calculate incoming tickets, resolved tickets and open tickets for the defined period using the agreed definitions. For resolution time, state the eligible population and exclusions. If a service target is supplied, define the denominator before calculating the rate.

Compare the relevant teams or request types. Distinguish observed differences from possible explanations. Keep unresolved and missing-data limits visible.
```

Do: check that each metric is supported by the workbook. Drop any metric the data cannot support, and say why.

### 5.3 Check with a chart before you trust it

02:08-02:13, 5 minutes.

Say:

Before the dashboard, I check. Cranmer has a habit I like. He does not read the long explanation. He asks for a plot, because you can see a problem in a chart much faster than in an essay.

```text
Before building the dashboard, show me one simple chart of resolution time by team from the cleaned rows, with the number of tickets behind each bar. Do not summarise it. I will read the chart.
```

Do: look for anything odd in the chart. Then reproduce one count from the source rows against the prepared answer sheet. If they disagree, find out why before moving on.

Say:

The skill saying it checked the data is not a check. I just checked it.

### 5.4 Build and inspect the dashboard

02:13-02:23, 10 minutes.

Say:

The dashboard should help the lead decide where to look next. Agreed figures, the comparisons that matter, and the limits of the data. Filters only where they help.

And I will use the same Outskill brand skill. I built it for slides, but the colours, fonts and logo inside it work for a dashboard too. So everything we make today looks like Outskill, not like default AI.

```text
Build a dashboard from the checked results for the support team lead. Use the brand rules in Outskill Slides for colours, fonts and logo.

Show the decision question, reporting period, metric definitions and units. Include the headline figures and the team or request-type comparisons that help locate workload and delays. Keep unresolved tickets and missing-data limits visible.

Add useful filters if the format supports them. Reconcile the headline figures to the analysis. Check that each filter changes the relevant metrics and charts consistently.

Deliver the dashboard with a short note on findings, possible explanations to investigate, cleaning decisions and checks performed. Do not claim the data establishes a cause.
```

Do: open the dashboard. Check one brand colour against the deck. Use one filter, compare with the source subset, and reset it. If the format is static, call it a static dashboard.

Say:

This tells me where to look. Why the delay happened needs information that is not in this file. I keep that as an open question.

Fallback: prepared dashboard with the same source checks.

### 5.5 Transition

02:23-02:25, 2 minutes.

Say:

We used different inputs for different work: a brand and my writing for content, a spreadsheet for analysis. The habit was the same in both. Brief properly, check against the source, then save what works.

## 6. Review the outputs and brief the breakout

Time: 02:25-02:30, 5 minutes.

Say:

Let me put everything back on screen. The business review, where we checked a conclusion against the figures. The team brief, where we opened a source message. The login-based site, where we checked an item and the log. The deck, where my edit survived the reload. The dashboard, where we matched a count to the source rows. Both in the Outskill brand, from one skill.

Your personal instructions hold what stays true about you. A voice profile holds how you write. A skill is a recipe for a type of work. A connector is a tool that gives access.

In the breakout, pick one small task. Bring back four things: your input, your request, the result, and the check you did. If something failed, show the failure and what you would try next.

Optional close, if there is time:

One last thing from Cranmer. He said it is better to be 50% comfortable with the newest tool than 90% comfortable with one from two years ago. That is why we keep moving fast in this program.

## 7. Final breakout

Starts at 02:30. Set the duration with the delivery schedule. This is the only learner activity block.

| Route | Learner work | Bring back | Success check |
| --- | --- | --- | --- |
| Business review | Brief their own weekly report using the four ideas | First and improved brief, plus one check | One figure traces to the source |
| Personal instructions | Continue the template interview. Add a "quiz me" line if they want one. | Instructions plus one correction | Facts match their answers. Uncovered sections stay visible. |
| Content and voice | Use their own writing sample and a factual brief. Edit with no-ai-slop if available. | Voice observations and revised copy | Facts and voice survive the edit |
| Data | Supplied practice spreadsheet, one decision question | A checked metric and a chart | Result reconciles to source rows |
| Browser | Only if browser access is already set up: a small read-only task on a site they log into | Source-linked brief and reading log | One point traces to an opened source |

Facilitator: ask learners to pick a scope they can finish in the breakout window.

Closing line:

Keep the correction you made today. If it applies again, put it into your instructions or your skill, then try it on another input.

## Completion notes

Done in this version: 150-minute structure, Claude Motion removed, first two sections merged, Cranmer points added, spoken lines written in Dileep's cadence as a starting point for Vishwas.

Not done: source packs, writing samples, brand rules, account installs, subscriber access, rehearsal and slides. Record actual timings in rehearsal, and update this folder after delivery.
