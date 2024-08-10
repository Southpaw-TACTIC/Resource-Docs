---
layout: default
title: Ghosting
nav_order: 2
parent: Crew Planner
has_children: true
---

Ghosting: Integrating Project Plans for Resource Visualization
=================================================================

The Crew Planner offers the capability to load project plans from the Role Planner, providing a valuable resource visualization tool for assessing schedule feasibility. This feature overlays proposed schedules onto the requested and booked schedules of crew members, allowing users to evaluate how the planned projects align with the team's current capacity.

Key features include:

**Multiple Project Schedule Loading**: Import one or more project schedules from the Role Planner, enabling a comprehensive view of resource distribution across ongoing and proposed projects.

**Schedule Visualization**: Compare proposed schedules against existing crew member schedules, helping identify potential conflicts, bottlenecks, or areas requiring resource reallocation.


By leveraging the Crew Planner's project plan integration, users can make informed decisions about resource allocation, ensuring that proposed projects align with the available capacity of crew members. This functionality facilitates proactive scheduling adjustments and promotes efficient project management.


## Matching Project Plans with Actual Schedules

The Crew Planner compares project plans from the Role Planner with actual crew member schedules, resulting in four possible cell statuses:

**Planned but Not Booked**: Cells representing roles that were included in the project plan but have not been booked with specific crew members.

**Booked but Not Planned**: Cells indicating roles that were booked with crew members but were not included in the original project plan.

**Booked and Planned**: Cells where roles were both planned in the project and successfully booked with crew members.

**Empty Cells**: Cells that are empty, indicating roles that have neither been planned nor booked.

Understanding these four cell cases allows users to identify discrepancies between project plans and actual resource allocation, helping to optimize crew scheduling and ensure that project requirements are met effectively.


