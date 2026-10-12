# Product Backlog & Sprint Plan

## Hostel Management System (HMS) — Part-2

**Date:** 12 October 2026
**Team:** shashankv2303 (sole team member — repo has one collaborator)

---

## 1. Backlog Source

Every backlog item below is a GitHub Issue created directly from the Functional (FR) and Non-Functional (NFR) requirements in the [SRS](SRS.md), labeled `backlog`, `type: functional`/`type: non-functional`, and `points: N` for story points, assigned to a Sprint milestone, and assigned to the team member responsible. Browse the live backlog at:

- **Issues:** https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues
- **Milestones (Sprints):** https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/milestones

## 2. GitHub Project Board

A GitHub Projects (v2) board should be created and linked to this repository to visualize the backlog as a Kanban/table view (Deliverables Part-2, item 1a). **This one step needs to be done manually** — Projects v2 boards can only be created/configured through GitHub's GraphQL API or the web UI, and this session's GitHub access is REST-only (no GraphQL), so it could not be automated here.

**To finish linking it (≈2 minutes):**
1. Go to the repo → **Projects** tab → **New project** → choose **Board** or **Table** view.
2. In the new project, click **+ Add item** → **Add from repository**, select this repo, and add all 20 open issues (or use **Insights/Workflows → Auto-add** to automatically add new issues from this repo going forward).
3. Optionally add a **Story Points** (number) and **Sprint** (iteration, matching the two milestones below) custom field in the project view, and bulk-fill them from each issue's "Story Points"/"Sprint" line (already in every issue body).

## 3. Story-Point Scale

Fibonacci-like scale: **2** (small/isolated), **3** (standard CRUD/flow), **5** (multi-step, concurrency, or external integration).

## 4. Sprint Plan

| Sprint | Window | Milestone | Goal |
|---|---|---|---|
| Sprint 1 | 19–23 Oct 2026 | [Milestone #1](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/milestone/1) | Core auth, room allocation, complaint handling + baseline performance/portability/API-versioning NFRs |
| Sprint 2 | 26–30 Oct 2026 | [Milestone #2](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/milestone/2) | Leave/outpass, visitor logging, fee payment, notices, occupancy reporting + remaining reliability/scalability/usability NFRs; development freeze |

*(12–16 Oct is the sprint dry-run week per the course schedule; the backlog below may still change up to 19 Oct.)*

## 5. Sprint 1 Backlog (19–23 Oct) — 38 points

| Issue | Title | Points | Assignee |
|---|---|---|---|
| [#1](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/1) | FR-1: Student account registration | 3 | shashankv2303 |
| [#2](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/2) | FR-2: Login with account lockout | 5 | shashankv2303 |
| [#3](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/3) | FR-3: Room/bed allocation | 5 | shashankv2303 |
| [#4](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/4) | FR-4: View allocation and fee dues | 3 | shashankv2303 |
| [#5](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/5) | FR-5: Submit maintenance complaint | 3 | shashankv2303 |
| [#6](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/6) | FR-6: Warden complaint management | 3 | shashankv2303 |
| [#7](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/7) | NFR-1: Dashboard response time under load | 5 | shashankv2303 |
| [#8](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/8) | NFR-5: Backend unit test coverage ≥70% | 5 | shashankv2303 |
| [#9](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/9) | NFR-6: Cross-browser portability | 3 | shashankv2303 |
| [#10](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/10) | NFR-8: Versioned, documented REST API | 3 | shashankv2303 |

## 6. Sprint 2 Backlog (26–30 Oct) — 36 points

| Issue | Title | Points | Assignee |
|---|---|---|---|
| [#11](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/11) | FR-7: Leave/outpass request submission | 3 | shashankv2303 |
| [#12](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/12) | FR-8: Leave/outpass approval and notification | 5 | shashankv2303 |
| [#13](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/13) | FR-9: Visitor entry/exit logging | 3 | shashankv2303 |
| [#14](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/14) | FR-10: Fee payment recording and receipt | 5 | shashankv2303 |
| [#15](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/15) | FR-11: Post notices/announcements | 2 | shashankv2303 |
| [#16](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/16) | FR-12: Occupancy report generation | 5 | shashankv2303 |
| [#17](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/17) | NFR-2: 99% monthly availability | 3 | shashankv2303 |
| [#18](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/18) | NFR-3: First-time usability of complaint submission | 2 | shashankv2303 |
| [#19](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/19) | NFR-4: Scalability to 5,000 student accounts | 3 | shashankv2303 |
| [#20](https://github.com/shashankv2303/PES1UG24CS435-se-miniproject/issues/20) | NFR-7: No data loss on server restart | 5 | shashankv2303 |

## 7. Security Requirements Coverage

The security requirements (SEC-REQ-1..5) are not separate backlog items — they are embedded as acceptance criteria in the FR issues that implement the affected flow (e.g. SEC-REQ-1 password hashing and lockout ride with FR-2 / issue #2; SEC-REQ-2 RBAC rides with FR-4 / issue #4). This keeps security work from being deprioritized or dropped as a "nice to have."

## 8. Next Steps per Deliverables Part-2

- [x] Backlog created from SRS FR/NFR (20 issues, labeled, pointed, milestoned, assigned) — 12 Oct.
- [ ] Link a GitHub Project board (manual step, see Section 2) — before 19 Oct.
- [ ] Enable GitHub Actions for PR/commit automation — Sprint 1.
- [ ] Sprint 1 execution, PR review, 1-minute demo video uploaded to the repo — 19–23 Oct.
- [ ] Sprint 2 execution, 2-minute demo video, documentation freeze — 26–30 Oct.
- [ ] Document any deviations from SRS/SAD/Test Plan for the final demo.
