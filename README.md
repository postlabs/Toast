<div align="center">

<img src="https://raw.githubusercontent.com/postlabs/Toast/main/.github/icon.png" width="120" alt="Toast">

# Toast

## Superpower your agent

**The Claude, ChatGPT or Gemini you already use becomes a superagent.
Ask it anything. Put it to work on anything.**

[![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)](https://claude.ai/code)
[![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=flat-square&logo=openai&logoColor=white)](https://openai.com)
[![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)](https://gemini.google.com)
&nbsp;
[![Chrome](https://img.shields.io/badge/Chrome-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://google.com/chrome)
[![Edge](https://img.shields.io/badge/Edge-0078D7?style=flat-square&logo=microsoftedge&logoColor=white)](https://microsoft.com/edge)
&nbsp;
[![Windows](https://img.shields.io/badge/Windows%2010%2B-0078D6?style=flat-square&logo=windows&logoColor=white)](https://github.com/postlabs/Toast/releases/latest)
[![Free](https://img.shields.io/badge/no%20bill%20from%20us-2EA043?style=flat-square)](#it-is-free)

### [⬇ Download for Windows](https://github.com/postlabs/Toast/releases/latest) &nbsp;·&nbsp; [postlab.ai](https://postlab.ai)

</div>

---

Ask your agent for something real and it tells you what it *would* do. Then you
go and do it. You open the site. You sign in. You copy the page back into the
chat. You paste its answer into the cart.

Every useful thing your agent has ever done for you, **you carried across
yourself.** You are the bridge between it and the world, every single time.

Nobody likes this, so everybody has tried to fix it: an MCP server, a fistful of
API keys, a skills folder, a lost afternoon. What you get back is **constant
management for a marginal gain** — one more thing to maintain, re-approve and
re-explain, so that you can ask it for a summary maybe twice and then go back to
carrying things yourself.

**Toast is that bridge.** Your agent stops describing the job and does it.

```
   Claude   ──┐                                        ┌──  live sites, signed in as you
   ChatGPT  ──┼──▶  reach · canvas · standing duty  ──▶┼──  mail · calendar · drive
   Gemini   ──┘                                        └──  shops · banks · boards
```

## Ask for the whole job

> **"Okinawa in March, two of us, with baggage."**
>
> It reads the booking sites side by side, folds together the same flight sold by
> five sellers, adds the bag fee you would have met at the gate, and lays out who
> is actually cheapest — next to the photos travellers posted from that trip.

> **"Running shoes, wide feet, under ₩150,000."**
>
> Fit reports, video tests, and the Reddit replies that contradict them. Matched
> on width *before* price, down to the exact variant that is in stock.

> **"How are my holdings doing, and what are people saying?"**
>
> Positions with sparklines and today's move, the factors behind each one, and
> the stock-board reaction underneath — arguments left intact, not averaged into
> a sentiment score.

> **"Pull my documents and draft the handoff."**
>
> Through the phone authentication, out as readable pages and an email draft with
> the attachments already named.

> **"Dad wants the usual order."**
>
> Reads the message, matches what he bought last time, fills the cart, totals it,
> and pings your phone before anything is paid for.

It crosses as you, not as a demo. It navigates, reads, compares and decides, and
it gets past what gets in the way — the login wall, the consent banner, the
verification code that lands on your phone. **Real accounts, real prices, real
money:** the totals are what you will be charged, the stock is what is actually
in stock, and the cart is sitting in your own account when it hands back.

That is real power, which is why it is yours to grant: it reaches the accounts
and sites you connect, and nothing else.

None of these is a prompt you have to engineer. They are **baskets** — small apps
built from doughs — and they ship with the app or come from people who published
theirs.

## Reach

**The real web, signed in as you.** Not a scrape and not a search summary. Toast
drives a real browser — Chrome or Edge — carrying your own session, then reads the
JSON the page fetched for itself: every row behind a listing, with the counts,
scores and IDs the rendered card leaves out. A read that works once is promoted
into a **dough** you can run again tomorrow.

**Your accounts, connected once.** Mail, calendar, drive, messaging, the shops and
banks and boards you use — each one a **kit**: a small, declared integration with
its own auth, tools and doughs. Connect what you want reached and nothing else.

**One yes, not a thousand.** Say yes once and your agent runs the task end to end,
with no pop-up per step. That is real power, so connect only what you actually
want it to touch.

## A canvas, not a chat log

Answers land on a **living canvas** beside the conversation — tables, charts,
cards, documents, rendered by **spreads**, a declarative layout grammar rather
than screenshots or markdown.

The agent keeps working on them. It mounts a result, then re-renders, reorders and
updates it **across turns** as the picture fills in. The canvas is append-only:
every edit is a new version, nothing is overwritten, and you can step back through
how the work got here.

Your canvas *is* the conversation — still there tomorrow, still filling in.

## Work that continues without you

Put an agent on **standing duty**. It wakes on a schedule or on a message, does
the work while you are away, and reports back to the room that asked — watching a
price, a listing, an inbox, a filing.

What it works out once becomes a portable artifact: readable YAML you can re-run,
fork, or hand to someone else. Not a transcript, and not a recorded click-path
that breaks the day a button moves.

## It is free

Toast is a new kind of agentic framework for your AI, and there is no bill from
us. Every run spends the Claude, ChatGPT or Gemini plan you already have.

It hyperscales through its community: people build **doughs** and publish them,
and the next person installs one instead of paying the tokens to work it out
again. Take one, change it, publish your own.

## Your data goes to your AI, not to us

Your chats and what the agent works on go to the servers of the AI you chose —
exactly as they do today. Nothing routes through us.

Passwords and sensitive data are double-encrypted and stored on this computer,
never exposed to the agent or to any server. Revealing one needs Windows Hello:
a human has to be present, and software cannot answer for itself.

Each account gets its own isolated profile — its own data, history and
connections. Nothing leaks between them.

## Install

```
  ToastSetup.exe   ~1 MB       one file, and it asks before anything lands
        │
        ├─ runtime            Electron · Node · CPython · uv
        ├─ engine             the backend and its natives
        └─ app                the interface, kits, spreads, baskets
                              ↳ every later update fetches only what changed
```

If a release ever misbehaves it restores the last version that worked, by itself,
with no download.

Windows 10 (64-bit) or later. macOS and Linux are in progress.

## Status

Toast is in active development and ships often. Expect rough edges — and tell us
where they are.

---

<div align="center">

[⬇ Download](https://github.com/postlabs/Toast/releases/latest) &nbsp;·&nbsp; [Website](https://postlab.ai) &nbsp;·&nbsp; [Privacy](https://postlab.ai/privacy)

<sub>© Postlab Inc.</sub>

</div>
