---
title: Projects as temporal structure notes
date: 2023-04-14
aliases:
tags:
  - concept
status: undeveloped
created: 2023-04-14T21:15:25+02:00
updated: 2023-04-16T15:37:43+02:00
public: true
---

> [!NOTE] Project structure notes
> Temporary organizational hubs that coordinate knowledge and tasks for specific, time-bound endeavors. Unlike permanent structure notes that organize evergreen knowledge domains, project notes have a **defined lifecycle** and are designed to be archived or deleted upon completion.

## Characteristics

### Temporal Nature

- **Fixed Timeline**: Have clear start and end dates
- **Outcome-Focused**: Organized around achieving specific deliverables
- **Progressive Evolution**: Content changes dramatically as project phases advance
- **Finite Lifespan**: Cease to be useful once the project concludes (this is not set in stone!)

### Organizational Function

- **Central Command**: Serves as mission control for all project-related information (MOC)
- [[context switching|Context Switching]]: Helps you rapidly re-enter project context after breaks
- **Resource Coordination**: Links to relevant permanent notes, external resources, and task lists
- **Progress Tracking**: Documents decisions, blockers, and milestone achievements

## Implementation Examples

### Software Development Project

```markdown
---
status: In Progress
Last Updated: 2025-04-15
---
# Mobile App Redesign Project - Q2 2025

## Project Overview
- **Timeline**: March 15 - June 30, 2025
- **Team**: Sarah (Design), Mike (Frontend), Alex (Backend)
- **Goal**: Improve user engagement by 25%

## Key Resources
- [[User Experience Design Principles]] - permanent knowledge
- [[React Native Best Practices]] - technical reference
- [[Project Management Methodology]] - process guidance

## Current Sprint (Week 8)
- **Focus**: Payment integration testing
- **Blockers**: [[API Rate Limiting Issue]] - needs backend fix
- **Decisions**: Using Stripe over PayPal (see [[Payment Provider Analysis]])

## Living Documentation
- [[User Interview Insights March 2025]]
- [[Technical Architecture Decisions]]
- [[Design System Components]]

## Next Actions
- [ ] Finalize payment flow UX
- [ ] Code review for checkout module
- [ ] Prepare demo for stakeholder meeting
```

### Research Paper Project

```markdown
# Climate Change Adaptation Strategies Paper

## Project Scope
- **Deadline**: September 15, 2024
- **Target**: Environmental Policy Journal
- **Word Count**: 8,000 words
- **Thesis**: Local governance structures are more effective than federal mandates

## Research Foundation
- [[Climate Science Fundamentals]] - background knowledge
- [[Policy Implementation Theory]] - analytical framework
- [[Case Study Methodology]] - research approach

## Argument Development
- [[Federal vs Local Climate Policies]] - comparative analysis
- [[Copenhagen Case Study]] - success story
- [[Miami Adaptation Failures]] - counterexample

## Writing Progress
- [x] Literature review complete
- [x] Methodology section drafted
- [ ] Case study analysis (60% complete)
- [ ] Discussion section
- [ ] Conclusion and recommendations

## Submission Pipeline
- [[Peer Review Feedback Integration]]
- [[Journal Formatting Requirements]]
- [[Author Guidelines Checklist]]
```

## Lifecycle Management

### Active Phase Patterns

- **Daily Standup**: Quick reference for current priorities and blockers
- **Weekly Review**: Update progress, identify risks, plan next steps
- **Resource Accumulation**: Continuously link to relevant permanent notes and external sources
- **Decision Documentation**: Capture key choices and rationale for future reference

### Completion Strategies

#### Archive Approach

```markdown
# ARCHIVED: Mobile App Redesign - Completed June 2024

## Final Outcomes
- **Result**: 32% increase in user engagement (exceeded goal)
- **Lessons Learned**: [[Mobile UX Lessons from Q2 Project]]
- **Reusable Assets**: [[Design System Components]] (moved to permanent notes)

## Knowledge Extraction
- [[Payment Integration Patterns]] - technical insights
- [[Cross-Platform Testing Strategy]] - process improvements
- [[User Research Methodology Refinements]] - method updates

## Project Artifacts
- Final designs archived in company drive
- Code repository: github.com/company/mobile-redesign
- Metrics dashboard: [internal link]

---
**Status**: COMPLETED ✅ | **Archived**: 2024-07-01
```

#### Decomposition Approach

- **Extract Valuable Insights**: Move reusable knowledge to permanent notes
- **Preserve Key Decisions**: Document important choices that might inform future projects
- **Archive Reference Materials**: Store project-specific documents externally
- **Delete Temporary Content**: Remove task lists, meeting notes, and transient information

## Integration with Permanent Knowledge

### Bidirectional Value Flow

**Project → Permanent**: Insights from specific projects enrich your permanent knowledge base
```markdown

- [[Lessons from Failed Product Launch]] → [[Product Management Principles]]
- [[Client Communication Breakthrough]] → [[Stakeholder Management Strategies]]

**Permanent → Project**: Existing knowledge accelerates new projects

- [[Negotiation Techniques]] → Current contract discussion
- [[Database Design Patterns]] → New application architecture
```

### Knowledge Distillation Process

- **During Project**: Identify insights that transcend the specific context
- **At Completion**: Systematically extract and formalize learnings
- **Post-Project**: Reference extracted knowledge in future similar endeavors

## Tools and Techniques

### Obsidian Implementation

- **Folder Structure**: Separate `Projects` and `Archive` folders
- **Template Usage**: Standardized project note templates for consistency
- **Tag System**: `#project-active`, `#project-completed`, `#project-archived`
- **Dataview Queries**: Automatically list active projects and track completion rates

### Maintenance Workflow

- **Monthly Cleanup**: Archive completed projects, update active ones
- **Quarterly Review**: Extract patterns across multiple completed projects
- **Annual Analysis**: Identify systemic improvements in project management approach

## Benefits of Temporal Structure

- **Cognitive Load Management**: Separates active project complexity from permanent knowledge
- **Context Preservation**: Maintains project-specific context while it's needed
- **Knowledge Evolution**: Allows insights to mature and generalize beyond specific projects
- **System Hygiene**: Prevents knowledge base from being cluttered with obsolete project details

Project structure notes serve as **temporary scaffolding** for complex endeavors, providing organization and context while active, then gracefully dissolving to leave behind distilled wisdom integrated into your permanent knowledge system.

A project is anything we want to do that requires ==more than one action== step. It's therefore a **mechanism** to remember that, when we finish that first action step, there will still be something more to do.

Some projects have a concrete goal, and thus a finishing point, others might be long-term or even open-ended (learn French), keep updating the MOCs to avoid having stale content in your ZK.

## See also 
[[Getting Things Done]]
![[ahrens_2022#^hsproj01]]>– [[How to Take Smart Notes - Sönke Ahrens]]
