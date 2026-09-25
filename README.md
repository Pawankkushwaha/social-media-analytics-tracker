# Centralized Analytics Dashboard

A Google Sheets system that consolidates my own content performance, across YouTube, my website, and LinkedIn, into one weekly-sprint dashboard, so there's one real answer to "is this actually working," instead of checking each platform's native analytics separately with no target to compare against.

## See it

[View the real dashboard](https://docs.google.com/spreadsheets/d/12z0gmeDnuh1RxwOOzegKX__n5IWUNXQqhhgN5E_Pwk8/edit?usp=sharing)

## The problem

Every platform reports its own numbers in isolation: YouTube Studio, website analytics, and LinkedIn's own stats each live in their own dashboard, on their own cadence, with no shared view across them and no running comparison against a target. Reviewing progress meant manually checking four places and doing the target-vs-actual math by hand, or not doing it at all.

## What it is

A structured system built entirely in Google Sheets, no code:

- **Per-platform tabs** (YouTube, Website, LinkedIn), each broken down Quarter → Month → Week, tracking that week's real output against a running weekly and yearly target
- **A consolidated "Main" dashboard** rolling every platform up onto the same weekly grain: weekly views (long-form video, Shorts, long-form text, short-form text), watch time, follower/subscriber gains split by platform, email list growth, and revenue by source
- **A "Major Updates" log column on every single week**, so a year of numbers is also a year of context, not just a trend line with no explanation for what actually happened

## Real results tracked

I used this system to track YouTube growth through all of 2024 against a 50,000-subscriber target: started the year at 5,525 subscribers, ended it at 43,208, with weekly views and Shorts output logged alongside every week of that growth. It's since being expanded to run the same weekly-sprint model across Website and LinkedIn for the current year.

## What building this involved

- **Deciding what to actually measure.** Leading indicators (views, uploads, content mix) sit right next to the lagging outcome (subscriber/follower count), so a bad week shows up before the subscriber number moves.
- **Designing one normalized weekly grain across every platform**, even though YouTube, a website, and LinkedIn each report on their own native cadence, so a "week" means the same thing everywhere in the sheet and cross-platform weeks are actually comparable.
- **Keeping the reasoning attached to the numbers.** A Major Updates column next to every week's data means a spike or a drop months later is still explainable, not just a line on a chart.
- **Scoping it to grow without a redesign.** Built single-platform for YouTube first in 2024, proven for a full year, then extended to Website and LinkedIn under the same structure rather than starting over.

This kind of system, deciding what to measure, building a consistent cadence to review it, and keeping the reasoning attached to the numbers, is the same operating discipline behind my Popular Recently Chrome extension and YouTube Goal Tracker: the skill set I look for chances to practice for an Associate Product Manager, Product Manager, or an early co-founder / founder's-office seat at a startup.

## Built with

Google Sheets, formulas only, no scripts or add-ons. The output here is the data model and the weekly review process, not code.

## About this repo

This repository describes a Google Sheets system, not a coded project. There's no source code here; the README and the linked sheet are the deliverable.
