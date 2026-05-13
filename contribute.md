---
layout: default
title: Contribute
permalink: /contribute/
description: How to submit a correction or contribute a missing detail to the UCI Beall Butterworth Competition historical archive.
---

<header class="page-header">
  <div class="wrap">
    <div class="page-header__eyebrow">Contribute</div>
    <h1>Found something off? Help fix it.</h1>
    <p class="page-header__lede">This is a community-maintained record. If a roster is missing a name, a link is broken or a year is incomplete, the easiest path forward is to send the fix.</p>
  </div>
</header>

<section class="section">
  <div class="narrow">

## The two-line version

Send corrections to the source data repo at <a href="https://github.com/BeallButterworthUCI/History">BeallButterworthUCI/History</a>. Open an issue or a pull request. The site you are reading rebuilds from that repo automatically.

## Who is this page for?

You are in the right place if any of these apply:

- You were on a BBComp team and your row on the year page is wrong or missing a teammate.
- You participated in 2010, 2011 or any pre-2014 cycle. Those years are mostly missing in the public record and your program booklet would help.
- You judged or mentored an early cycle and you remember names we have left out.
- You have a working URL for a press release we cited that has since 404'd.
- You spotted a typo, an em dash that slipped through or a stiff sentence we should soften.

## What we will accept

We try to keep the bar at "public, verifiable and useful." Concretely:

- **Yes**, please send: correct team rosters, prize amounts, project descriptions, official press releases, peer-reviewed publications, public LinkedIn-confirmed employer updates, university pages, conference bios.
- **No**, please do not send: personal contact information, internal company numbers that have not been disclosed, private acquisition rumors, anything you would not want a journalist to publish.

If a fact is true but only privately known, the archive will leave it out. If a fact is widely reported but not from a primary source, we mark it `UNVERIFIED` rather than asserting it.

## How to submit

### Option A: open an issue

The lowest-friction path. Useful if you do not want to edit Markdown.

1. Go to <a href="https://github.com/BeallButterworthUCI/History/issues/new">github.com/BeallButterworthUCI/History/issues/new</a>.
2. Describe what is wrong or what is missing. Include a URL or two pointing to a public source if you have one.
3. We will track and apply the fix.

### Option B: open a pull request

Faster to merge if you already know your way around Git.

1. Fork <a href="https://github.com/BeallButterworthUCI/History">BeallButterworthUCI/History</a>.
2. Find the relevant file. Most year-level edits live in <code>years/YYYY.md</code>. Founder-level updates go in <code>docs/where-are-they-now.md</code>. Cross-cycle pages live in <code>docs/</code>.
3. Make the edit, write a short commit message and open a PR against <code>main</code>.
4. Mention the source URL in the PR description.

### Option C: email a tip

If you are not on GitHub at all, that is fine too. The archive maintainer monitors issues regularly and will pull tips in from comments.

## What happens next

A maintainer reviews the change, runs the verification routine (a quick fetch of any cited URLs and a sanity-check against the primary source) and merges. The site you are reading rebuilds within a few minutes of the merge.

If your contribution turns into a new entry rather than a fix to an existing one, expect a short back-and-forth to confirm the source.

## Style notes for editors

A few light conventions, in case you are writing prose:

- Plain English. Short sentences are fine. Skip the em dash.
- One source per claim where possible. Cite the primary, not the aggregator.
- Use `UNVERIFIED` when a number comes from a single secondary source. Leave the number in if it is useful, but mark it.
- The site does not Oxford-comma. Lists join with "and" or "or" at the end.

## Thanks

The archive is more accurate every month because someone takes the time to send a correction. Two decades of student work is a lot to keep track of, and we are not finished.

  </div>
</section>
