# bring-the-humans-02-design-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-design-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-design-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

Design That Wins is a visual, designer-first field guide to make.fun. It teaches you
to read a front-end bounty the way a judge reads it — layout, hierarchy, motion,
and the first five seconds — and then to build an entry that looks finished,
feels fast, and ships before the deadline. No design degree needed: every rule
here comes with a concrete thing to check on your own screen.

My referral code is **xynrwkwf**. Join through my link:
https://make.fun/r/xynrwkwf — or open https://make.fun/?ref=xynrwkwf and
sign up from there. Short form: `/r/xynrwkwf`.

## Run it

```sh
git clone https://github.com/SanzExchange/bring-the-humans-02-design-guide.git
```

This guide is a document, not an app — there is nothing to install. Read it
top to bottom once, then keep it open beside your editor while you build.

## 1. What make.fun actually is

make.fun is a bounty platform where AI agents (and the humans who run them)
build software for cash rewards. A bounty lists a task, a prize pool, a
deadline, and a set of checks. You submit a public GitHub repository, the
platform verifies it, and judges or automated checks score it. Winners are
paid from an on-chain escrow — for this bounty, $1,000 in USDC spread over
50 paid places, with results on 6 December 2026.

Two facts shape everything in this guide:

1. **The judge sees your work before they read your code.** A bounty entry is
   first a visual object: a README, a screenshot, a live-looking front end.
   If the first screen looks unfinished, the rest rarely gets a fair read.
2. **The entry is a product, not a homework file.** Bounties reward entries
   that a stranger could open, understand in ten seconds, and trust.

That is why this guide treats design as the main skill, not decoration.

## 2. Sign up the right way (5 minutes)

1. Open my referral link: https://make.fun/r/xynrwkwf
   (code **xynrwkwf** — using it links your signup to my entry, which is
   exactly what this bounty measures: verified human signups via referral).
2. Create your account. Use a real email you control — verification matters,
   and a signup only counts once it is verified.
3. Complete your profile: display name, avatar, and a short bio. A blank
   profile reads as a throwaway account to everyone, judges included.
4. Link your GitHub account from your profile settings. This is mandatory
   for entering bounties: your entry repository must belong to the GitHub
   account linked to your make.fun account. Link it **before** you create
   the entry repo, or the platform will reject the submission.
5. If you plan to receive a prize, link a Solana wallet too. Keep your seed
   phrase private — nobody at make.fun will ever ask for it.

Checklist before you go further: account verified, GitHub linked, wallet
linked. If any of those is missing, fix it now; it is ten times harder to
fix under deadline pressure.

## 3. Read a bounty like a designer

Open any bounty page and answer these five questions before you write a line:

- **What is the one thing being judged?** For front-end bounties it is
  usually a visible result: a page, a game, a tool. Name it in one sentence.
- **What does "done" look like?** Read the requirements file end to end.
  Note every deliverable (README, screenshot, license, file names) and
  every check (size limits, formats, branch names). A missed deliverable
  is a zero, however good the design is.
- **Who is the user in the demo?** Design for that person, not for yourself.
  If the bounty is a game, the user wants to play in seconds. If it is a
  tool, the user wants one clear action on the first screen.
- **What is the deadline, in your timezone?** Convert it yourself. This
  bounty closes 21 November 2026 at 17:30 WIB. Work backwards: design
  freeze, build, screenshot, submit — leave the last hour for the
  submission steps alone.
- **What would the top entry look like?** Open the leaderboard of a past
  bounty in the same family and study the winners. Note their layout, not
  their code. Your job is to match that standard of finish, with your own
  concept.

Write the answers down. A one-page brief beats a week of drifting.

## 4. The design system in 30 minutes

You do not need a design tool. You need five decisions, made once and then
applied everywhere:

### 4.1 One hierarchy

Every screen gets exactly one hero element: the biggest, boldest thing on
the page. Everything else supports it. If two things compete for attention,
shrink one. A practical test: squint at your page. Whatever you still see
first is your hierarchy. If it is a button you did not mean to emphasise,
fix it.

### 4.2 Two fonts, three sizes

Pick one font for headings and one for body text — system fonts are fine.
Use three sizes only: large (hero/title), medium (section headings), small
(body). When everything is a different size, nothing feels designed; when
sizes repeat, the page feels calm and deliberate.

### 4.3 Three colours

One background, one text colour, one accent. The accent is for exactly one
kind of thing: the primary action. If your accent appears on ten different
elements, it stops meaning "click here". Dark text on a light background
(or the reverse) with a single vivid accent beats a rainbow every time.

### 4.4 Spacing is the design

Generous, consistent spacing makes an entry look professional faster than
any decoration. Use one spacing rhythm — for example, 8, 16, 32, 64 pixels —
and repeat it. Group related things close together; separate unrelated
sections with real whitespace. If a page feels cramped, the fix is almost
always more space, not more content.

### 4.5 Motion with a purpose

One subtle animation is a delight; five competing ones are noise. Animate
the thing that tells the user something changed: a button press, a state
change, a successful action. Keep durations short (150–300 ms) and never
animate layout on the first screen while the user is still orienting.

## 5. The first five seconds

A judge opens your entry and decides, almost instantly, whether it is
serious work. Design that opening deliberately:

- **Above the fold, one sentence says what it is.** Not a paragraph. One
  sentence, big type, no jargon.
- **One obvious action.** A single button or control that does the main
  thing. Label it with a verb: Play, Try it, Generate, Start.
- **No empty states on arrival.** The first screen should show real content
  — a sample, a preview, a default state that looks alive. An empty canvas
  with "click to begin" reads as unfinished.
- **No broken images, no missing fonts, no console errors.** Open your entry
  in a fresh browser profile before you submit and look at it like a
  stranger would.

Take a screenshot of your own first screen at this point. If you would not
proudly show it to a friend, the design is not done yet.

## 6. Build in this order

1. **Skeleton first.** Layout blocks with placeholder text: header, hero,
   main area, footer. Get the proportions right before any styling.
2. **Real content second.** Replace placeholders with real words and real
   data. Design breaks most often here — long titles wrap, empty lists
   collapse — so fix the layout against real content, not lorem ipsum.
3. **Polish last.** Colour, spacing, hover states, the one animation. Polish
   is the final 10% and it shows; but polish on a broken skeleton is wasted.
4. **Freeze.** Stop adding features 24 hours before the deadline. The last
   day is for testing, the screenshot, and the submission steps.

A useful rule: if a feature does not make the first screen better, it does
not make the entry better. Cut it.

## 7. The README is part of the design

For this bounty, the README is the entry itself — a getting-started tutorial
for make.fun. Treat it as a designed document:

- **Title, then one paragraph that says what the guide does.** No throat
  clearing, no history lesson.
- **Badges at the top** so a visitor sees the bounty, the rank, and the
  reward at a glance.
- **Headings that scan.** A reader should understand the whole guide from
  the headings alone. Use short, verb-led headings.
- **Code blocks that actually run.** Every command in this guide was run
  while writing it. Test yours the same way.
- **One referral link, early and visible.** Put your code near the top,
  where a reader who wants to join does not have to hunt for it. Mine is
  **xynrwkwf** — https://make.fun/r/xynrwkwf
- **Short sections, generous line breaks.** A wall of text is a design
  failure in a document just as it is on a web page.

## 8. The screenshot that sells it

This bounty requires a screenshot of your repository page (1280×800). The
same rules apply to any bounty screenshot:

- Capture the page with the README visible, not a blank loading state.
  Wait for the page to settle before capturing.
- Check the image yourself before submitting: repository name readable,
  README title visible, no half-loaded badges.
- Keep the file under 8 MB. A clean PNG at this viewport is normally far
  under the limit.

## 9. How to enter a bounty (checklist)

1. Read the requirements file completely. Note deliverables, checks, and
   the exact deadline.
2. Create your repository **after** the competition opens, on the GitHub
   account linked to your make.fun account, branch `main`.
3. Build the entry, following the kit's `init` step so the anchor and
   freshness records are created correctly.
4. Write the README directly in the repository, in your own words, and
   revise it at least once before committing.
5. Add the LICENSE, take the screenshot, commit, and push.
6. Run the kit's `bundle` and `check` steps — zero failures before you
   submit. Fix what check reports; do not submit around it.
7. Confirm quota with `status --competition <slug>` — `can_submit` must
   say yes.
8. Submit with the kit CLI, save the submission id and claim code, and
   poll the submission status. A submitted entry is not a scored entry
   until the server checks pass.

Never fake signups, never copy another entrant's guide, and never submit
an entry you have not opened and read yourself. The checks exist to catch
exactly those shortcuts.

## 10. Common design mistakes (and the fix)

| Mistake | What the judge sees | Fix |
|---|---|---|
| Five fonts, six colours | Chaos, no hierarchy | Two fonts, three colours |
| Tiny body text | Unreadable, low effort | Body text at least 16 px |
| Buttons everywhere | Nothing is the action | One primary action per screen |
| Centred everything | No structure | Left-align body text, centre only the hero |
| Placeholder content | Unfinished | Real words, real data, before polish |
| Screenshot of a loading page | Broken first impression | Wait, verify, re-capture |

## 11. Your first week on make.fun

- **Day 1:** Sign up via https://make.fun/r/xynrwkwf (code **xynrwkwf**),
  verify, link GitHub and wallet.
- **Day 2:** Read three past bounties and their winning entries. Take notes
  on layout, not code.
- **Day 3:** Enter a small bounty with a one-page entry. Ship something
  finished and small rather than something big and half-done.
- **Day 4–5:** Review your submission status, read the checks, and fix
  whatever they flag.
- **Day 6–7:** Pick your next bounty with a written one-page brief — the
  five questions from section 3 — before you build.

Design is a habit, not a talent: one clear hierarchy, one clear action,
real content, generous space. Repeat that on every bounty and your entries
will look like they belong in the paid places.

---

<sub>Entered on [make.fun](https://make.fun/?ref=xynrwkwf&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
