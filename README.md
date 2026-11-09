# Email Inbox Assistant

An AI-powered assistant that helps users quickly see which emails matter and what to do about them — surfacing priority and a short summary for each message instead of making users open and read every email one by one.

This project is being built as part of **CSED402 (Human-Computer Interaction)** at POSTECH, by team **Notification Phobias**.

## Team

- Minseo CHO (CSE)
- Joonyong SUNG (CSE)
- Junho Yun (CSE)
- Juyeon CHOI (IME / CSE)

## Problem

Email users need to easily see which emails are important, because they don't rely on existing organizational features and receive too many emails to track manually.

Every message lands in the same inbox, sorted by time regardless of urgency, and the sheer volume of email makes it hard to manually keep track of what still needs attention. Users end up opening emails one at a time just to figure out what's urgent and what can wait.

## Goal

Rather than asking "is this feature effective or not," this project aims to find out **under which conditions** AI-driven prioritization and summarization actually help — for example, depending on email type, inbox size, or how much a user already relies on manual sorting.

## Status

🚧 **Early stage — ideation complete, concept consolidation in progress.**

Three candidate directions came out of our ideation phase and are being narrowed down into the feature set this repo will implement:

| Idea | Description |
|---|---|
| **Email-Based To-Do Board** | Turns action items inside emails into trackable tasks (not started / in progress / done), each linked back to its source email. |
| **Conversational Email Assistant** | Lets users ask natural-language questions about their inbox (e.g. "What do I need to do this week?") and get a deadline-ordered summary with links to source emails. |
| **Priority Inbox** | Surfaces each email's required action, deadline, and reason for its priority, with a suggested processing order the user can rearrange. |

The implemented prototype will connect to a **real email account** (Gmail and/or Outlook, via OAuth) rather than mock data, so the final scope and tech stack are still being finalized.

## Roadmap

1. **Prototype** — connect to a real inbox via OAuth and implement the core priority/summary feature(s) chosen from the three candidate ideas above.
2. **User study** — evaluate the prototype with participants, comparing behavior/performance with and without the assistant (completion time, accuracy, cognitive load, etc.).
3. **Analysis & write-up** — determine under which conditions the assistant actually helps, and present findings.

## Course Context

This repository supports a **Human-Computer Interaction (CSED356)** course project.\
**Prof.** Sungahn Ko \
**Semester** 2026 Fall
