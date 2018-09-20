# 👷🏽‍♀️ How we work

This document describes how humans can work on GitHub.
This is work in progress.
This document is supposed to change a bunch in further cycles.

One of the biggest reasons for some peculiarities in this document is because
workers of the lab typically work part-time and in a mix of remote and coworking.

## 👶🏽 Prereqs

Before reading this document, make sure you’ve read [onboarding.md](onboarding.md).

## 🏃🏽‍♀️ Sprint

*   We work in sprints, in 1 or 2 weeks, where we do something.
    Sprints are typically shorter at the start and end of a project,
    and longer in the middle
*   At the start of a week, we briefly look back on last week, and look forward
    to what we’re working on this week (sprint planning).
    It’s important that everyone attends.
    The plan is filled out in a Kanban-style board on GitHub.
*   Every day (Monday through Friday) at 9 a.m. you get a message from StatusHero
    on Slack or Email, that acts as a daily scrum meeting.
    If you’re “absent” (not working on the lab, remotely or physically), there’s
    a button for that
*   At the end of a week, we review what we did, this may happen remotely,
    but if we’re able to do it physically we like to do something fun afterwards

## 🍱 Kanban-style board

We’re using GitHub [project boards](https://help.github.com/articles/about-project-boards/) to track work.
Things typically start in **backlog**, the left-most column, as a “note” (some text, something that may be done).
A note can be upgraded to an issue, if it’s actionable.
Issues can have labels (e.g., research, design, tech), and are assigned to team members.
At the start of a sprint, we decide which cards move to the **this week** column.
At this point, the card should be described, labelled, and assigned.

If a card could be broken up into independent cards, it’s probably too big.
For example, prefer “Set-up meeting room” and “Document onboarding” separately over
“Tuesday tasks”.
If breaking up a card would be confusing, use one card and in the description place a task list:

```markdown
* [ ] Mail Anna
* [ ] Mail Anton
```

…these items can be checked off to signal progress on a card.

When a card is done, move it to the **done** column.

At the end of a sprint, all the cards in the **done** column are archived.

## 📚 Documentation

Most documents can be placed on GitHub, and should be written in Markdown.
If documents are private, or don’t easily work on GitHub (such as PDFs or Slides),
places them in Google Drive instead.
