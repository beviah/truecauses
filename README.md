# True Causes

**Free online root cause analysis for groups.** Stop voting on symptoms. Find the causes.

[truecauses.org](https://truecauses.org) · [Try it in five minutes](https://truecauses.org/about) · [See it at scale](https://truecauses.org/zoom) · [Why it works](https://truecauses.org/why)

![A causal map built by several rooms on one question](https://truecauses.org/d/59eaba9/map.svg)

*A live map from a demonstration room: deepest causes on the left, roots outlined in green.*

**We are looking for pilot partners:** municipalities, unions, schools, hospitals and organisations with a problem that keeps coming back. [Jump to pilots ↓](#run-a-pilot)

---

## The problem

Ask a group what is wrong and then vote on what matters most, and the winner is almost always the thing everyone can see: the waiting times, the outages, the complaints. Those are consequences. The causes sit further back, spread across people who each saw a different part of the problem.

Researchers call this the **erroneous priorities effect**: the problems a group ranks highest are reliably the ones furthest downstream. Fixing them is why the same problem keeps coming back.

## What True Causes does

It lets the people who live with a problem find its causes together, online, in seven stages:

1. **Generate:** everyone writes causes alone, before reading anyone else's.
2. **Clarify:** authors say what they meant. Nobody judges merit yet.
3. **Cluster:** similar ideas are grouped, to make the wall easier to read.
4. **Select:** five votes each on what matters most, with a few places kept for overlooked ideas backed by a source.
5. **Structure:** one question at a time: *does this cause significantly influence that one?* A link counts only when three quarters agree.
6. **Map:** the causes, deepest first, with every disagreement kept on the map.
7. **Actions:** each proposed action is judged against each root cause: does it reduce it, make it worse, or neither?

Nobody is named inside a room, so a junior nurse can write what a consultant would not. Many rooms can take the same question and their maps fold into one: causes found independently in several places stand out.

It is a web implementation of **Structured Democratic Dialogue** (Warfield, Christakis, Laouris), a method with fifty years and more than a hundred documented dialogues behind it.

---

## Run a pilot

### Who it suits

| You are | A good first question |
|---|---|
| A **municipality** or public body | Why do residents stop using a service? Why does a neighbourhood keep losing young families? |
| A **union** or workforce | Why do the same safety incidents recur? Why is turnover high on one site? |
| A **school** or university | Why do students disengage in the second year? Why do good teachers leave? |
| A **hospital** or care service | Why do waits keep growing? Why do medication errors happen despite the checks? |
| Any **organisation** | Why does the same kind of project keep running late? |

The best pilot question is a problem people have already tried to fix, more than once, and that everyone involved sees from a different angle.

### Three shapes a pilot can take

- **One room.** 12 to 100 people who all know the problem. The simplest start.
- **Several rooms, one question.** Different sites, wards, departments or neighbourhoods each run their own room on the same question, and their maps merge. This shows which causes everyone found and which are local.
- **A public question.** You publish the question and residents or members open their own rooms on it. The merged map can be published and embedded on your own site.

### What it asks of people

Everyone takes part in their own time, from a phone or a computer, over one to three weeks. Nobody has to be online at the same moment; if a group wants to talk, each group can have a built-in video call (Jitsi: no accounts, nothing recorded).

Most of a participant's time goes into **Structure**: answering one question at a time about pairs of causes, about twenty seconds each. For a large wall that can add up to an hour, which people can split across several sittings. Everything else takes minutes per stage. Members get a reminder when their part is waiting, if they ask for one.

### What you get

- **A map of causes** your people certified themselves, deepest first, with every disagreement kept on it.
- **Actions judged against the roots**: which proposed actions would reduce each root cause, and which would make one worse.
- **The record behind it**: every claim has its own page, and every judged pair with its vote counts can be downloaded as a spreadsheet (CSV).
- **Something you can share**: embed the live map on your own site, or use it as a picture in a report. Published results credit True Causes with a link to the room.

### What it costs

| | |
|---|---|
| Rooms of up to 100 people | **Free** |
| Registered nonprofits and charities | **Free** Organisation plan (rooms of up to 1,000), on approval |
| One large dialogue, up to 2,000 people, 60 days | $749 once |
| Recurring use in an organisation | from $75 a month · [all plans](https://truecauses.org/pricing) |

A pilot on the free plan needs no contract and no card.

### How to start

1. **Try it yourself first**, in five minutes, with simulated members: [truecauses.org/about](https://truecauses.org/about).
2. **Open an issue in this repository** or use *Ask about a pilot* on [truecauses.org/zoom](https://truecauses.org/zoom). Tell us the problem, who is affected, and roughly how many people. We will help you word the question: it is the part that matters most.
3. **Open your room** at [truecauses.org](https://truecauses.org/?register=1) and invite people with a link.

After your pilot, we would like to hear what worked and what did not. With your permission, a short case study helps the next group decide.

---

## Take part as a participant

You do not need to run anything to try it with real people. [Open questions](https://truecauses.org/questions) lists questions anyone can take up by opening their own room, and any settled map there can be read without an account.

## Compared with

[Pol.is](https://truecauses.org/compare/polis) · [Stanford Online Deliberation Platform](https://truecauses.org/compare/stanford) · [Frankly (Harvard)](https://truecauses.org/compare/frankly) · [Kialo](https://truecauses.org/compare/kialo) · [Loomio](https://truecauses.org/compare/loomio) · [Decidim](https://truecauses.org/compare/decidim) · [Miro](https://truecauses.org/compare/miro)

## Open results

True Causes is hosted, not open source. The results are open: a public room's map, every claim and every judged pair can be read and downloaded without an account.

```bash
curl https://truecauses.org/api/questions                # published questions
curl https://truecauses.org/c/59eaba9/0be6b79.json        # one claim, with what the room certified around it
curl -O https://truecauses.org/d/59eaba9/pairs.csv        # every pair a public room judged, with vote counts
```

## Built on

- John N. Warfield, *A Handbook of Interactive Management* (1994)
- Alexander N. Christakis and Kenneth C. Bausch, *How People Harness Their Collective Wisdom and Power* (2006)
- Yiannis Laouris and Mariana Metcalf, "Assessing the viability of virtual Structured Democratic Dialogue", *Systems Research and Behavioral Science* (2024), doi:10.1002/sres.3006

[Sources and references in full](https://truecauses.org/notes/lineage) · Cite as: *True Causes, Inverudio Inc, https://truecauses.org, 2026.*
