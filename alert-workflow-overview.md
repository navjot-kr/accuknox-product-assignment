Overview:

The Alert Triage Workflow is designed to help teams quickly review incoming alerts, identify high-priority items, and assign ownership without delay. The focus of this workflow is speed and clarity at the triage stage, enabling users to take immediate action before moving into deeper investigation workflows. The scope is intentionally limited to alert visibility, prioritization, and ownership to support fast decision-making.


Proposed Features:

    Alert Overview with Ownership Status - 
      Displays alerts with Alert ID, severity, and status, clearly indicating whether each alert is assigned to the user, assigned to others, or unassigned.

  Assigned vs Unassigned Alerts Grouping - 
  Alerts are grouped into assigned and unassigned sections, helping users quickly identify alerts that need immediate ownership.

  Inline Assignment & Co-assignment - 
  Users can assign alerts to themselves or co-assign them directly from the alert list, reducing delays during triage.

  Priority Selection for Assigned Alerts - 
  Users can set priority for alerts assigned to them directly within the list view to support faster triage decisions.
  
  Basic Alert Context via Description - 
  Assigned alerts include a brief description that provides enough context for users to decide severity and priority during triage.

Prioritization:

Features were prioritized to support fast triage by clearly showing alert ownership and urgency. Separating assigned and unassigned alerts helps users quickly identify items that need immediate attention. Priority can be set directly on assigned alerts using the provided severity and description, without navigating away from the list.
More detailed alert handling can be added later and is not included in this version.

Success Metrics:

  Ownership Clarity - 
  Reduction in the number of alerts that remain unassigned and faster assignment of alerts after they appear.

  Early Prioritization - 
  Percentage of assigned alerts where priority is set during the triage stage and time taken to set priority after assignment.

  Reducing Alert Noise - 
  Increase in the number of low-priority alerts closed or deprioritized during triage, helping users focus on what matters.

  Collaboration - 
  Usage of assign and co-assign actions, indicating how often alerts are shared or jointly handled by multiple users.

Development Discussion Points:

  Confirm which alert details are available and how missing information should be handled.

  Clarify whether alerts are auto-assigned or manually assigned, and who has permission to assign them.

  Confirm whether users can collaborate with other teams on an alert when required.

  Clarify whether an alert can have multiple owners through co-assignment, and who is allowed to co-assign alerts.

  Decide how alerts that do not require immediate action should be handled (for example, deprioritized or closed).

  Clarify what happens when an alert is assigned to a user who is not currently logged in.
