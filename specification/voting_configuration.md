# Voting Configuration

For the configuration of a voting session, it is necessary to choose a type of vote and a voting mode, also in certain cases, custom weights and tiebreakers may be configured.

Each configuration topic is listed and detailed below with some examples for a better understanding in the end of this file.

---
## Vote Types

Possible types of vote to be applied an certain voting session, these types cannot be merged and cannot be changed after session starts.

### Simple Criteria Vote:

- Binary Vote:
    - A simple vote that the only possible answers are positive or negative.

- Note Vote:
    - Consists of the application of a note from 1 to 5.

- Enumerated Vote:
    - Consists of choosing an option among one of predetermined values.

### Multi Criteria Vote:

Consists of applying a simple criterion multiple times, you can define custom criteria fields as needed for that vote.

\***The use of more than one type of criterion is not allowed, basically, binary fields, note fields and enumerated fields cannot be merged in the same vote of this type.**

---

## Voting Modes

The types of votes listed above can be applied to the following modes.

### Simple Target Voting

This is the simplest mode of vote, in which a type of vote is applied directly to a simple target, for this reason tiebreaker criteria are not applicable to this mode.

### Multi Target Voting

This voting mode consists of multiple voting targets to be voted individually to consolidate and form a ranking result. If desired, in some cases tiebreaker criteria can be configured for this mode.


---
## Weights System

For votes of multiple criteria, customized weights may be applied for each listed criterion, these weights will be percentage values of addition to the criterion, these values must be from 0 to 100 and will be applied to each type as follows:

*To facilitate the explanation we will use the value 50 as the parameter value, this value means that the presence of a certain property will have a weight of 150% in the evaluation of this criterion.*

- Binary
- Note
- Enumerated