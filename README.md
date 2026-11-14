# SideQuest

**Campus involvement, individualized to each student's ambitions.**

Georgia Tech has hundreds of clubs, labs, and campus jobs spread across different sites, and students have no easy way to tell which ones fit their goals, their schedule, or their budget. SideQuest ranks those opportunities for one student at a time, shows what it takes to join, and helps them plan a week they can keep up with.

## What it does

| Feature | What the student gets |
| --- | --- |
| **Find my fit** | Clubs, labs, and campus jobs in separate tabs, each ranked by a match score built from the student's goals, major, free hours, and budget. Every result explains why it matched. |
| **Filters** | Application status (open now, rolling, opens soon, closed), no dues, and no schedule conflicts, plus search. |
| **My plan** | A weekly calendar that totals hours against the student's limit, flags overlapping meetings, and tracks each application from interested to joined. |
| **Class conflicts** | Import a calendar file (.ics) from Google, Apple, or Outlook Calendar, or add class times by hand. |
| **My history** | Students log past experiences and rate each out of 10. Low ratings lower the score of similar options and high ratings raise it. |
| **Alumni like you** | Alumni whose early path overlaps with the student's, and what they did next. |
| **Navigator** | A 3D model of five campus buildings that draws the route to the room where an organization meets. |

## How matching works

1. **Goals.** Each opportunity is tagged with the goals it serves (career, research, community, leadership, service). Overlap with the student's goals is the largest part of the score.
2. **Fit.** Relevance to the student's major adds to the score. Needing more hours than the student has free lowers it.
3. **History.** Ratings of past experiences shift the score of anything on the same topic.
4. **Hard limits.** Budget, application status, and schedule conflicts remove results instead of lowering them.

## Run it

The whole app is one file. Download `index.html` and open it in a browser. There is nothing to install and no server.

## Data

**All data in this prototype is sample data.** Organizations, dues, meeting rooms and times, application details, and every student and alumni profile are illustrative and are not real or official. Room positions in the Navigator are approximate.

Planned sources for real data:

- Organization details from Georgia Tech's Engage directory, with permission
- Student and alumni paths from an opt-in survey
- Dues, time commitment, and application details confirmed by club officers

## Roadmap

- [ ] Replace sample organizations with real directory data
- [ ] Collect opt-in student and alumni paths
- [ ] One-click calendar sync
- [ ] Officer portal for keeping listings current
- [ ] Split the single file into separate page, style, script, and data files

## Contributing

1. Create a branch for your change.
2. Upload or edit `index.html` on that branch.
3. Open a pull request and describe what changed.
4. A teammate reviews and merges it.

Use short commit messages that say what changed, for example `Add application status filter`.

## Team

Built for a Georgia Tech case competition.

## Disclaimer

SideQuest is a student project. It is not affiliated with or endorsed by Georgia Tech, and it does not collect data from LinkedIn.
