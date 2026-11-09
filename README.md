# dhtutorial-portfolio
# Who Gets In?

**A data biography of a Karachi social club's sign-up form.**

[View the live page]((https://aimanafza.github.io/whogetsin/))

## What this is

Saturday Club is a small, vetted gathering held every Saturday somewhere in Karachi, Pakistan. To attend, you apply online, the host approves you by hand, and only then do you get the address. To apply, you hand over your national ID card (CNIC), a live selfie, your date of birth and your WhatsApp number.

I built the club's sign-up platform. This project steps back and reads that platform as a source, asking one question:

> How does a Karachi social club's 2026 sign-up system define a "safe" guest, and who does that data design include or leave out?

## What's on the page

- **The biography:** Heather Krause's four questions (where, who, how, why) asked of the club's own records.
- **The record:** all 14 stored fields, what each one is for, and what it assumes about the person filling it in.
- **Who sees what:** a table of which fields the applicant, the host, other guests and the public can see.
- **Lifespan:** when each piece of data is deleted, and what is never deleted.
- **The map:** a hex map of the Karachi neighbourhoods that have hosted events. It shows areas only, never venues, because the club keeps exact locations private.
- **A lighter form:** proposed changes that keep guests safe while collecting less.

## How it was made

- The findings come from an audit of the live codebase (Next.js, Supabase), done with Claude Code on October 31, 2026. The audit covered the database tables, access rules and scheduled deletion jobs.
- No real guest data is used. Sample values belong to an invented applicant, and the map shows neighbourhoods only.
- The club's host agreed to the club being named.
- The page is a single self-contained `index.html`, hosted on Vercel.

## Key readings

- Catherine D'Ignazio and Lauren F. Klein, *Data Feminism* (MIT Press, 2020)
- Johanna Drucker, "Humanities Approaches to Graphical Display," *Digital Humanities Quarterly* 5, no. 1 (2011)
- Heather Krause, "Data Biographies: Getting to Know Your Data," GIJN (2017)

## Context

Made by Aiman Afzal Arain for the Digital Humanities Tutorial at Minerva University, Fall 2026.
