# BloodBridge - Team Capacity and Story Sizing

Team 8. Prepared for Module 2: Determine Team Capacity and Size User Stories.

## Sprint schedule

The roadmap reserves weeks 1-2 (Sep 8 to Sep 19) for planning. Development runs in
two-week sprints from Sep 22 to Dec 12.

| Sprint | Dates | Roadmap phase |
|--------|-------|---------------|
| 1 | Sep 22 - Oct 3 | Phase 2: Accounts and cloud backend |
| 2 | Oct 6 - Oct 17 | Phase 2 / Phase 3 |
| 3 | Oct 20 - Oct 31 | Phase 3: Donor and receiver forms |
| 4 | Nov 3 - Nov 14 | Phase 4: Hospital side and matching |
| 5 | Nov 17 - Nov 28 | Phase 4 (Thanksgiving week, reduced capacity) |
| 6 | Dec 1 - Dec 12 | Phase 5: Testing and final demo |

## Team capacity

Hours per week are a starting assumption of 6 for everyone. Each member should
replace their row with a realistic number before Sprint Planning.

| Member | Hours / week | Hours / sprint (2 weeks) |
|--------|-------------:|-------------------------:|
| Aarju KC | 6 | 12 |
| Balkrishna KC | 6 | 12 |
| Dinesh Saud | 6 | 12 |
| Dipesh Chamlagain | 6 | 12 |
| Suvash Bhusal | 6 | 12 |
| Yujan Shrestha | 6 | 12 |
| **Total** | **36** | **72** |

Focus factor: 0.7. Class time, meetings, and context switching take the rest.

Effective capacity per sprint: 72 x 0.7 = **50 hours**.

## Relative sizing

Stories are sized in story points using a Fibonacci scale.

| Points | Meaning | Rough effort |
|-------:|---------|--------------|
| 1 | Trivial, well understood, one small change | up to 2 hours |
| 2 | Small, clear scope | half a day |
| 3 | Medium, a few moving parts | about a day |
| 5 | Large, touches several parts or has unknowns | 2 days or more |

Anything that feels bigger than 5 is split into smaller stories.

Calibration: 1 point is about 2 hours of focused work, so 50 hours of capacity
means a **target velocity of about 25 points per sprint**. We will adjust this
after Sprint 1 based on how many points actually get done.

## Backlog against capacity

| Item | Value |
|------|------:|
| Stories in backlog | 60 |
| Total story points (draft) | 156 |
| Sprints available | 6 |
| Points needed per sprint to finish everything | 26 |
| Target velocity | 25 |

The whole backlog fits the semester only if velocity holds at 25. Sprint 5 is
shorter because of Thanksgiving, so Low priority stories are the first to be cut
if we fall behind. High priority stories (21 stories, 65 points) are the minimum
for a working final demo and take about 2.5 sprints on their own.

Points by priority:

| Priority | Stories | Points |
|----------|--------:|-------:|
| High | 21 | 65 |
| Medium | 28 | 64 |
| Low | 11 | 27 |

## Sprint 1 candidates (Ready column)

Ten High priority stories that establish the backend and accounts, 24 points in
total, within the 25 point target.

| Story | Title | Points |
|-------|-------|-------:|
| US-01 | Railway project with web service and Postgres database | 3 |
| US-02 | Auto-deploy from the main branch | 2 |
| US-03 | Secrets in Railway environment variables | 1 |
| US-11 | Sign up with email and password | 3 |
| US-12 | Log in and stay logged in | 3 |
| US-13 | Choose Donor or Receiver at sign-up | 2 |
| US-15 | Hospital accounts created by the team | 3 |
| US-42 | Migrations that create the tables | 3 |
| US-43 | Users table with a role field | 1 |
| US-44 | Location stored on donors, requests, and hospitals | 3 |

These are moved to the Ready column on the project board. Owners are assigned at
Sprint Planning.
