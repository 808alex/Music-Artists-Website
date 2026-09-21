# My Favourite Artists

A personal website showcasing my top 10 favourite music artists — built from scratch with plain HTML, CSS, and JavaScript, no frameworks.

## Why this project exists

I started this project for the sole reason of bringing my HTML, CSS, and JavaScript fundamentals back up to a sharp, after a long stretch spent focused on other languages, stacks and interests. Most of what I build day to day leans backend or AI-assisted development — this is the complete opposite, a front-end-only project built by hand, the long way.

It's also nice to have on my portfolio and a way too look at what music/artists I like.

## What it is

A catalogue of my top 10 favourite artists, each with their own dedicated page covering:

- Genre, years active, and origin — with a flag and an on-hover map pin
- A bio, and the story of how I found them
- Their top 5 career-defining songs in chronological order rather than personal ranking, telling the story of how the artist evolved — with a scroll-linked side timeline explaining why each song mattered (a first big single, a genre shift, a major feature, a turning point)
- A short music videos section
- A rank badge and a signature colour unique to that artist's page

Beyond the top 10, there's an honourable mentions page for artists I love who didn't make the cut, covered in less depth.

## Built with

Plain HTML, CSS, and JavaScript. No frameworks, no build tools — deliberately, since the point is refining the fundamentals themselves, not learning a framework on top of them.

The scroll-triggered timeline uses the Intersection Observer API to detect which era of an artist's career is in view and fade the previous one out as the next comes in.

## Status

Actively in progress, built in three passes: structure first (plain HTML across every page), then a single shared stylesheet, then JavaScript for the interactive pieces — hover map, scroll timeline, animations.

See [DEVLOG.md](./DEVLOG.md) for the full build process, sketches, and the ideas that didn't make it in.
