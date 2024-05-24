# DX Workshop Guide

The DX Workshop is designed to assist teams in pinpointing specific issues their developers encounter with the most problematic drivers, as highlighted in their most recent Developer Experience surveys.

The structure of the Workshop ensures that every developer within a team, regardless of seniority or influence, has an equal opportunity to voice their concerns and propose solutions.

The goal is to help establish a collaborative continuous improvement environment inside each team, where concrete issues affecting Developer Experience are surfaced, and solutions are given the space to be implemented.

## Before Workshop

### Identify Workshop Drivers

Check your team’s latest snapshot detail page in DX and identify the:

- Top 3 Drivers with Lowest Sentiment
- Top 3 Drivers with Highest Priority

At minimum you will identify 3 workshop drivers (if there’s a complete overlap in both low sentiment and priority) and at most 6, if the none of the drivers across sentiment and priority overlap.

As you can see in the example below for _Example Team_, 4 drivers were identified for the workshop: Deep Work, Documentation, Test Efficiency and Codebase Experience.

### Prepare Workshop File

Clone the [DX Workshop File](https://lucid.app/lucidspark/0e330442-36f7-485f-85cd-69df81ff45fb/edit?viewport_loc=-35%2C-2053%2C5874%2C4874%2C0_0&invitationId=inv_3f01b3cc-74f5-4f5b-91a3-d99c73d58730) and then:

- **In DX**:
  - Take screenshots of DX Heatmap for your tribe for:
    - Sentiment (compared to none)
    - Sentiment (compared to previous snapshot)
    - Sentiment (compared to pipedrive average)
- **In the Cloned Workshop File**:
  - Add the screenshots of the DX Heatmaps into the corresponding frames
  - Add the identified higher priorities and lowest sentiment to the priority/sentiment frame
    - Make sure to set a unique color for each driver
    - Make sure to set the sentiment value after the driver name
  - Modify the lanes in the “Problem Identification” and “Solution Ideation” frames to equal the identified drivers and colors
    - Make sure to add the correct descriptions in the “Problem Identification” frame lanes to match the drivers, as documented in the Driver descriptions table.
   
### Driver Problem Identification Questions

The following table contains the questions to be placed to developers in the problem identification phase of the workshop for each driver. The questions should be phrased to prompt developers to identify actionable problems.

| Driver | Question |
| --- | --- |
| [Codebase Experience](https://app.getdx.com/atlas/codebase-experience) | What concrete services or libraries have you had to work with that you find it painful to work with and why? |
| [Cross-team Colaboration](https://app.getdx.com/atlas/cross-team-collaboration) | What concrete teams, initiatives or things have you had to work with beyond the context of Sails that have left you feeling frustrated? |
| [Deep Work](https://app.getdx.com/atlas/deep-work) | What's making you to feel that you are unable to do deep work? List concrete things that prevent you from focusing. |
| [Documentation](https://app.getdx.com/atlas/documentation) | When and where have you felt the need for documentation and it was missing, or simply not good enough? |
| [Incident Response](https://app.getdx.com/atlas/incident-response) | What situations or things have frustrated you during incident response? |
| [Managing Tech Debt](https://app.getdx.com/atlas/balancing-tech-debt) | What concrete services, libraries or things you've worked on that make you feel we're not handling tech debt well and why? |
| [On Call Experience](https://app.getdx.com/atlas/on-call-experience) | What concrete things are making your on call experience suffer? |
| [Production Debugging](https://app.getdx.com/atlas/production-debugging) | What concrete things you needed when debugging an issue in production that you felt were lacking? |
| [Test Efficiency](https://app.getdx.com/atlas/test-efficiency) | What concrete services, libraries and flows are making you feel the test efficiency isn't good and where. |
| [Clear Direction](https://app.getdx.com/atlas/clear-direction) | What areas or initiatives do you feel lack clear vision, goals or priorities, and made you feel there isn't a clear sense of direction or alignment? |
| [Experimentation](https://app.getdx.com/atlas/experimentation) | What situations have you encountered where you felt restricted or unsupported in experimenting with new ideas, technologies, or approaches in your work? |

<sup>This list will be updated as required. If the driver you need is not yet covered in this table, please request it.</sup>

### Schedule the Workshop

1. **Book a 1 hour event in the calendar:**
    - Title:
        - Format: TEAM_NAME DX Workshop QUARTER YEAR
        - Example: Sails DX Workshop Q3 2024
    - When:
        - First thing in the morning, or just after lunch (i.e.: not tired and/or hungry)
        - Ideally within 2 weeks of the last DX survey
    - Attendees:
        - Engineering Manager
        - Developers

2. **Send a message in the teams's private channel:** telling them that you're doing a DX Workshop on date and time X to look at the exact Developer Experiences issues affecting them as highlighted by the last survey and come up with ideas to fix them.

## During Workshop

### Agenda & Guidelines

#### Introduction (~10m)

- **EM:** welcome and brief explanation on motivation for the Workshop (3m)
- **EM:** brief overview of DX results as per Heatmaps (5m)
    - Offer your interpretation (as neutral and factual as possible) of the data on the Heatmap, e.g. identify the drivers whose sentiment degraded or improved, and what are, on your point of view the causes that led to such.
- **EM:** explain how the Workshop is structured (2m)

#### Problem Identification (~21m)

- **Developers:** identify problems (~15m)
    - **EM:** maintain silence throughout the exercise, and only intervene to ask more details if a problem in a sticky note is not concrete enough
- **Developers:** cluster similar problems (2m)
- **Developers:** vote on clustered problems (2m)
    - **EM:** start a voting session, and configure it to only allow voting in sticky notes, give developers a vote for each driver (lane) and one additional vote to pick whichever they feel is the most important problem across all lanes, even if they vote twice in it.
    - **Developers:** vote in one of the solutions per driver, and then once on the most important problem across all drivers.
- **EM:** read aloud the voted clusters and their total vote count (2m)

#### Solution Ideation (~21m)

- **Developers:** propose solutions (~15m)
    - **EM:** maintain silence throughout the exercise, and only intervene to ask more details if a solution in a sticky note is not clear enough
- **Developers:** cluster similar solutions (2m)
- **Developers:** vote on clustered solutions (2m)
    - **EM:** start a voting session, and configure it to only allow voting in sticky notes, give developers a vote for each driver (lane) and one additional vote to pick whichever they feel is the most important solution across all lanes, even if they vote twice in it.
    - **Developers:** vote in one of the solutions per driver, and then once on the most important solution across all drivers.
- **EM:** read aloud the voted solutions and their total vote count (2m)

#### Wrap Up (~8m)

- **EM:** thank developers for participating and for their ideas
- **EM:** explain what will happen after the workshop
- **Developers:** questions & answers

## After Workshop

### Create a Workshop Summary

Create a Workshop Summary document with the same structure and logic used in [link to DX Workshop Summary template] and add it as a child page of [link to DX Workshop area].

The Workshop Summary document should have the following structure:

#### Survey Results

##### Observations and Interpretation

- Screenshot of Sentiment Heatmap (compared to last survey)
- Statement about the important changes (+-15) that can be perceived from last survey
- Screenshot of Sentiment Headmap (absolute values)
- Statement about the state of the team when looking solely at absolute numbers (e.g. team might have degraded/improved greatly in some drivers but still be mostly positive/negative)
- Screenshot of Sentiment Headmap (compared with company team's average)
- Statement about the state of the team when comparing with the average (e.g. some drivers might be negative, but aligned with other tribes or considerably better than other tribes). Offer a neutral and reasonable explanation why the team sentiment might have changed in some drivers or across the board, or haven't, despite or because actions in the past quarter.

#### Identified Problems

##### [DRIVER 1..N]

- Table with a list of problems that had at least one vote, including total vote count

#### Proposed Solutions

##### [DRIVER 1..N]

- Table with a list of solutions that had at least one vote, including total vote count

#### Next Steps

- Checklist of actions to be done post workshop to get to a better state

#### Workshop

- Link to Lucidspark Workshop Document

### Solution Execution Planning

The Engineering Manager should come up with a reasonable action plan, based on the outcomes of the workshop, to address the problems identified by the team, ideally following the solutions proposed by them.

The Engineering Manager should also ensure that the team feels their problems were heard, and, will be addressed. Specifically, the Engineering Manager should ensure that quick wins are implemented in the current quarter and that complex problems are acknowledged and realistically scheduled to be worked at a later date. Failure to do so, will make the team mistrust the exercise, the manager, and won't engage adequately with it again.

## FAQ

### How often should I run this workshop?

No more than twice a year. Usually the amount of problems and ideas that come out of the workshop are quite a few and these aren't usually solvable in a single quarter.

Ideally this workshop should be run every two quarters, and in the quarter in between the team should have a meeting to go over the DX Survey results for that quarter and check the status of problems and initiatives that were triggered as part of the last workshop.
