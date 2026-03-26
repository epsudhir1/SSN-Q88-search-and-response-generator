# Data Dictionary (Recommended)

## Mandatory fields

- `event_id`: Unique identifier.
- `event_date`: Event date (`YYYY-MM-DD`).
- `event_class`: One of `Incident`, `Near Miss`, `Unsafe Act`, `Unsafe Condition`.
- `title`: Short title.
- `narrative`: Descriptive text.

## Strongly recommended fields

- `area`: `Deck`, `Engine`, `Accommodation`, `Other`.
- `type_of_work`: Work type/activity.
- `incident_category`: Approved category list used by company.
- `root_cause`: For incidents when available.
- `preventive_action`: For incidents when available.
- `severity`: Actual severity class.
- `potential_consequence`: If captured.
- `vessel`: Vessel name.

## Optional fields

- `fleet`
- `location`
- `shift/watch`
- `equipment_tag`
- `status`
- `close_out_date`

## Normalization rules

- Dates must be in ISO format (`YYYY-MM-DD`).
- Keep a single category label per record where possible.
- If multi-select categories exist, separate using semicolon (`;`).
- Keep free-text narratives untrimmed to preserve context.

## Approved consequence categories

Insert your controlled list here and keep it stable across reporting cycles.

Example placeholder list (replace with your official taxonomy):

- Injury / Ill Health
- Fire / Explosion
- Equipment Damage / Technical Failure
- Pollution / Environmental Release
- Mooring / Berthing Event
- Navigation / Collision / Grounding
- Cargo / Containment Issue
- Security
- Other
