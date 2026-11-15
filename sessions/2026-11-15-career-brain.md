# 2026-11-15: a career brain instead of a pile of resumes

Hiree's first session. It started as "I should work on my resume" and became TOPC's go at unemployment. Kamal: "when I say improve hiring, I mean tackle unemployment and incur efficient employment as a TOPC idea."

## What we found

- Kamal's resumes were scattered: three versions from Jun 2025, Aug 2026 and Oct 2026, each out of date in a different way.
- His two earlier tries in this space, Hiree v0 and AskJobo, were both resume enhancers: upload a resume, get a nicer one. Neither kept a true record of the work or got it to the right opportunity.
- A search of Ideato's ideas on 15 Nov 2026 found none about hiring or resumes.

## What we decided

- **One brain, many resumes.** Every piece of work is stored once, as dated facts with a source, in a private Basic Memory project, using the same rules as TOPC's own brain. Resumes are written on the fly for each opportunity, never kept as master files.
- **Proof over claims.** Every number on a resume comes from a source: a repo's history, a read-only count, an old resume. When a number is unknown, it stays off. One of the open-source resume skills we tried estimates numbers when the real ones are unknown; we skip that part.
- **Public pages get less than private resumes.** A public profile leaves out client usage numbers and contact details that are fine on a resume you send to one person.
- **Contract work, judged against your own goals.** The first tool is a gig judge: paste any gig and it answers take, negotiate or skip, weighed against goals you set, not just the rate.

## What we built

- The task board and project: [topc-social/hiree-tasks](https://github.com/topc-social/hiree-tasks), [ideato.social/projects/hiree](https://www.ideato.social/projects/hiree).
- A career brain for Kamal (private), backed up hourly to a private repo.
- A research pass on open-source resume skills: Paramchoudhary/ResumeSkills (MIT) fits best; details in [hiree-tasks#3](https://github.com/topc-social/hiree-tasks/issues/3).
- The gig judge skill, `hiree-gig-judge`, in the TOPC repo ([hiree-tasks#6](https://github.com/topc-social/hiree-tasks/issues/6)).
- Two Formy fixes found along the way: sliders and drag dials, then comboboxes, blank-label radios and tile pickers. Job sites are full of these widgets.

## Dead ends and lessons

- A job board listed a gig as "$100/hr". The company's own page said $1,000 per accepted task, which isn't the same thing. Read the source, not the listing.
- One old resume had a stack fact wrong. We fixed it once in the brain, so no resume written from it repeats the mistake.
- A headline figure on an old resume undersold the work; a read-only count showed far more. Measure before you write.

## Open

- A gig finder that searches contract boards daily and sends only what passes the judge.
- The same brain and judge for anyone, not just Kamal.

Want to help? Pick an open task on [hiree-tasks](https://github.com/topc-social/hiree-tasks/issues).
