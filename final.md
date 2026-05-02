# Management & Leadership in CS: Final Initiative

## Initiative: Goal-Aligned Task Tracking for the Lizard Classification Research Team

---

### Scope

This initiative focused on improving alignment between weekly project progress and research deliverables for the Lizard Classification team at HAAG. The team was building the Florida Anole Classifier (LizardLens), a private web application for Dr. James Stroud's "Lizards on the Loose" community science program. The app uses an ML pipeline to suggest one of five common anole species from student-submitted photographs, with mandatory human review before any observation is uploaded to iNaturalist.

As the project manager, I was responsible for a team of four researchers (Le Yang Loh, WenHan Chia, Anqi Zheng, and Niral Verma), a computational advisor (Ilia Jahanshahi), and coordination with the team point of contact (Charles R Clark) and principal investigator (Dr. Stroud).

The core problem this initiative addressed was a lack of structured visibility into whether individual researcher tasks were actually moving the team closer to its publication goal. Researchers were active and productive, but without goal-aligned tracking, it was difficult to tell whether effort was being directed toward the right deliverables at the right time. The initiative introduced a system of clear weekly task ownership, structured progress tracking through deliverables, early blocker identification, and alignment between figures and the manuscript narrative.

---

### Evidence of Alignment with HAAG's Goals

This initiative aligns with HAAG's emphasis on visibility, progress monitoring, and structured coordination across research teams.

Throughout the semester, several observations reinforced the need for this approach:

- **Duplicate datasets caused retraining delays.** Midway through the semester, the team discovered that duplicate datasets (lizard_10000_v4 vs florida_five_anole_10000_v4) had been used in training. This required a full retraining cycle and delayed progress on the Results section. Structured goal-level tracking helped surface this issue and coordinate the cleanup across Le Yang (retraining) and WenHan (updating the Results section to reflect corrected metrics).

- **Additional training data did not improve performance as expected.** An experiment involving additional public training data produced minimal improvement in bounding box accuracy. Without clear tracking, this negative result could have stalled progress. Instead, the team was able to document the finding, incorporate it into the manuscript narrative, and move on.

- **Async communication slowed alignment.** The team relied heavily on Slack and document comments for coordination. Limited real-time communication with the faculty advisor meant that feedback cycles were longer than ideal. The tracking system helped ensure that when feedback did arrive, it could be quickly mapped to specific tasks and assigned to the right researcher.

- **Dependency on faculty feedback created bottlenecks.** Several deliverables, particularly the confusion matrix approach, dataset counts, and model justification, required Dr. Stroud's input before the team could finalize them. Tracking these as explicit blockers improved visibility and helped the team work on unblocked tasks in the meantime.

Semi-weekly syncs with the lead researcher were used to review goal progress, close completed tasks, and identify risks. The operations tracker (maintained as a weekly Excel spreadsheet) served as the primary record of task assignments, focus areas, and status for each researcher across the full semester.

---

### Procedures Generated

This report contains one procedure: the **Goal-Aligned Task Tracking Procedure** for research team project managers. The purpose of this procedure is to provide a repeatable, lightweight framework for assigning weekly tasks, tracking progress against research deliverables, identifying blockers early, and maintaining alignment between individual work and team-level goals.

The full procedure follows below.

---
---

# Procedure: Goal-Aligned Task Tracking for Research Team Project Managers

**Document Type:** Standard Operating Procedure (SOP)  
**Intended Audience:** Research Team Project Managers at HAAG  
**Version:** 1.0  
**Date:** April 2026

---

## Purpose

This procedure gives research team project managers a step-by-step guide to implement and maintain goal-aligned task tracking across a semester-long research project. The system ensures that weekly task assignments are directly tied to research deliverables, blockers are surfaced early, and the team maintains consistent forward momentum toward publication or other initiative-level goals.

---

## Background

In research teams, individual researchers are often productive without the team as a whole making clear progress toward its goals. A researcher may be busy refining a figure while a critical manuscript section sits unwritten, or a dataset issue may go unnoticed for weeks because no one is tracking whether training results actually align with what the paper claims.

This procedure addresses that gap by making deliverable alignment the primary focus of weekly task assignment. The PM does not micromanage individual work. Instead, the PM ensures that every researcher's weekly focus connects to a concrete deliverable that moves the project closer to its goal.

---

## Key Concepts

### Work Hierarchy

All work is organized into three levels:

**Initiative → Deliverables → Weekly Tasks**

- **Initiative** is the team's overarching goal for the semester. For the Lizard Classification team, this was: publish the Florida Anole Classifier paper and finalize the LizardLens web application.

- **Deliverables** are the concrete outputs that must be completed to achieve the initiative. Examples from this project: completed Methods section, finalized Grad-CAM figures, cleaned training dataset, fully integrated iNaturalist upload feature, citation-ready manuscript.

- **Weekly Tasks** are specific assignments given to individual researchers that move a deliverable forward. Each task should be scoped to roughly one week of work and should have a clear definition of done.

### Core Principle

**Track deliverables, not activity.** Assume researchers are doing their work. The PM's job is to ensure that the work being done is the right work at the right time.

---

## Tools Required

- **Slack** for team communication and async updates
- **Spreadsheet (Excel or Google Sheets)** for the weekly operations tracker
- **Document comments** (Google Docs or Word) for manuscript-level feedback

No additional tools or software are required. Everything runs within infrastructure the team is already using.

---

## Procedure

### Phase 1: Initial Setup (First Week)

**Estimated time:** 1 to 2 hours

#### Step 1: Define the Initiative

Meet with the lead researcher, computational advisor, and/or PI to identify the team's primary goal for the semester.

- Ask: "What does this team need to deliver by the end of the semester?"
- Write down a single, clear initiative statement.
- Example: "Publish the Florida Anole Classifier paper and finalize LizardLens for classroom use."

#### Step 2: Identify Deliverables

Break the initiative into the concrete outputs that must be completed. For each deliverable, identify who is best positioned to own it.

Example deliverables and ownership from this project:

| Deliverable | Primary Owner |
|---|---|
| Web app with iNaturalist integration | Le Yang Loh |
| Model training, experiments, and Methods writing | WenHan Chia |
| Grad-CAM interpretability analysis and figures | Anqi Zheng |
| Manuscript accuracy, citations, and figure QA | Niral Verma |

#### Step 3: Create the Operations Tracker

Create a spreadsheet with one tab per week. Each tab should have the following columns:

| Column | Purpose |
|---|---|
| **Researcher** | Name of the assigned researcher |
| **Focus** | The deliverable area for the week (short phrase) |
| **Tasks** | Specific numbered tasks for the week (2 to 4 per researcher) |
| **Status via Lead** | Current status as reported by the lead researcher or in syncs |

#### Step 4: Introduce the System to the Team

Hold a brief kickoff meeting to:

- Walk through the initiative and deliverables.
- Explain that weekly tasks will be assigned based on what the project needs, not just what each researcher wants to work on.
- Clarify that researchers are expected to flag blockers as soon as they arise, not wait for the next sync.
- Explain that the operations tracker will serve as the team's record of progress and will be used for reporting.

---

### Phase 2: Ongoing Operations (Weekly Cycle)

#### Weekly Task Assignment

At the beginning of each week (or during the prior week's sync), the PM:

1. Reviews the current state of each deliverable.
2. Identifies what needs to happen next to keep the project on track.
3. Assigns 2 to 4 specific tasks per researcher, each tied to a deliverable.
4. Updates the operations tracker with the new week's assignments.

**Guidelines for writing good weekly tasks:**

- Each task should be completable within one week.
- Each task should have a clear output (a draft, a figure, a decision, a document).
- Tasks should be sequenced so that one researcher's output feeds into another's work the following week.

#### Sync Meetings

**Frequency:** Weekly or bi-weekly  
**Duration:** 15 to 30 minutes

**Agenda:**

1. **Blockers first.** Identify anything preventing progress and assign ownership of the resolution.
2. **Progress check.** For each researcher, briefly review whether their tasks from the prior week are complete. Update the tracker status.
3. **Next week preview.** Share upcoming task assignments and confirm priorities.

**What NOT to do:**

- Do not ask researchers to narrate everything they did. Focus on whether deliverables moved forward.
- Do not let the sync become a status report meeting. Keep it focused on blockers and next steps.

#### Async Board Maintenance

Between syncs, the PM is responsible for:

- Updating the tracker with information from Slack, document comments, and meetings.
- Watching for stalled deliverables. If a researcher's focus area has not moved in two weeks, flag it.
- Adjusting task assignments mid-week if priorities shift (e.g., faculty feedback arrives and needs to be incorporated immediately).

#### Researcher Expectations

Researchers are expected to:

- Complete their assigned weekly tasks or flag blockers early.
- Provide brief verbal updates during syncs.
- Move deliverables forward, not just complete tasks in isolation.

Researchers are NOT expected to:

- Maintain the operations tracker.
- Write separate progress reports for this system.

---

### Phase 3: Monthly Review and Adjustment

At least once per month, the PM should:

1. **Review the full tracker** with the lead researcher or computational advisor.
2. **Assess initiative progress.** Are completed tasks actually moving deliverables forward? Is effort going to the right places?
3. **Adjust deliverable ownership** if needed. As the project evolves, responsibilities may need to shift.
4. **Check pacing.** Is the team on track to meet the semester deadline? If not, identify what is slowing things down and re-prioritize.

---

## Handling Administrative Reporting

The operations tracker doubles as the basis for weekly reports to HAAG administration. Each week's tab provides a clear record of what each researcher was assigned, what their focus area was, and their status. This eliminates the need for researchers to produce separate documentation and ensures that reporting is derived from the same source of truth as the team's actual workflow.

---

## Success Metrics

| KPI | What It Measures | How to Track |
|---|---|---|
| **Deliverable Completion Rate** | Percentage of deliverables completed on time relative to the semester timeline | Count completed deliverables vs. total at end of semester |
| **Blocker Resolution Time** | How long blockers persist before resolution | Track when blockers are identified and when they are resolved |
| **Task-to-Deliverable Alignment** | Whether weekly tasks are consistently connected to active deliverables | Review tracker weekly for tasks that don't clearly map to a deliverable |
| **Researcher Sentiment** | How researchers feel about the tracking system and task clarity | Brief informal check-in or feedback at end of semester |

---

## Integration with HAAG's Existing Structure

This system works within HAAG's existing tools and workflows:

- **Slack** is already the primary communication tool. Blocker identification and async updates happen in existing channels.
- **Weekly meetings** already happen. The sync agenda replaces or supplements the existing meeting format without adding a new meeting.
- **Administrative reporting** is derived from the operations tracker, reducing duplication of effort.
- **Other HAAG initiatives** (e.g., blocker escalation protocols, reporting standardization) complement this system. Blockers identified through tracking can feed directly into escalation workflows.

No new tools need to be installed. No new accounts need to be created.

---

## Quick Reference: PM Checklist

### First Week
- [ ] Meet with lead researcher/PI to define the initiative
- [ ] Break the initiative into deliverables and assign ownership
- [ ] Create the operations tracker spreadsheet
- [ ] Hold kickoff meeting to introduce the system

### Every Week
- [ ] Review deliverable progress and assign 2–4 tasks per researcher
- [ ] Update the operations tracker
- [ ] Run sync meeting focused on blockers and deliverable progress
- [ ] Watch for stalled deliverables or misaligned tasks
- [ ] Flag risks to initiative completion

### Monthly
- [ ] Review full tracker with lead researcher or advisor
- [ ] Assess whether tasks are driving deliverable progress
- [ ] Adjust ownership or priorities as needed
- [ ] Check pacing against semester deadlines

---

## Measuring Progress: Semester Summary

Over the course of Weeks 2 through 12, the tracking system supported the following outcomes:

- **Methods section:** Completed. WenHan drafted and iterated the full section across Weeks 5 through 7.
- **Results section:** Nearing completion. WenHan led drafting from Week 7 onward, with Le Yang providing validated metrics and Anqi integrating interpretability figures.
- **Grad-CAM interpretability:** Finalized. Anqi moved from sample size research to figure generation to final selection (one clear example per species) across the full semester.
- **Figure QA and citations:** Ongoing through final weeks. Niral maintained consistency checks, integrated Zotero citations, and prepared the manuscript for submission.
- **Web app (LizardLens):** Le Yang finalized iNaturalist direct upload integration and added a usage counter in the final weeks.
- **Dataset cleanup:** Resolved. Duplicate datasets were identified and removed in Weeks 6–7, and the model was retrained with corrected data.

**Challenges encountered:**

- Duplicate datasets caused a multi-week retraining delay.
- Additional training data did not improve detector performance, requiring the team to document the negative result rather than iterate further.
- Async communication and faculty feedback dependency created bottlenecks that were managed but not fully eliminated.

---

## AI Acknowledgment

Claude (Anthropic) was used as a writing assistant during the preparation of this document. It was used for drafting, editing, and structuring content based on the author's notes, operational records, and existing project documentation. All content was reviewed, revised, and approved by the author. The initiative methodology, observations, and conclusions are the author's own.
