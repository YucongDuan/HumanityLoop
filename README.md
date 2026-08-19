# HumanityLoop / 人类再生环

**AI should leave people, communities and futures stronger than it found them.**  
**AI不应只替人完成任务，而应把能力、反馈、公共品与未来选择返还给人。**

HumanityLoop treats AI development as a starter for a new human-development cycle:

```text
Human need
-> bounded AI intervention
-> human action
-> real-world outcome
-> transferable human capability
-> consented commons return
-> feedback and correction
-> handoff and succession
-> renewed human need
```

## Why this exists

A linear AI economy extracts data, attention and experience, produces answers, and captures value centrally.

A regenerative cycle asks:

- Did a person become more capable?
- Was a real-world outcome observed?
- Did useful knowledge return to a commons or a justified private community?
- Was diversity preserved?
- Did compute, attention and personal-data demand remain within carrying capacity?
- Can the person or community continue without permanent dependence on this AI?
- Was harm repaired?
- Did the cycle seed a next steward or generation?

No aggregate human-value or regeneration score is produced.

## Quick start

```bash
python humanityloop.py new data/samples/seed_input.json --out outputs/my_cycle.json
python humanityloop.py event outputs/my_cycle.json data/samples/event_input.json --out outputs/my_cycle_v2.json
python humanityloop.py audit data/samples/regenerative_cycle.json
python humanityloop.py handoff data/samples/regenerative_cycle.json --out outputs/handoff.json
python humanityloop.py commons-export data/samples/regenerative_cycle.json --out outputs/public_cycle.json
python humanityloop.py compare data/samples/regenerative_cycle.json data/samples/extractive_cycle.json --out outputs/comparison.json
python humanityloop.py dashboard data/samples/regenerative_cycle.json data/samples/extractive_cycle.json
```

## Repository strategy

Do not automatically create another standalone repository. Prefer installation into an existing flagship:

```bash
python integration/install_into_existing_flagship.py /path/to/existing-flagship
```

The installer creates `modules/humanityloop/`, preserves the previous Git HEAD with a tag, writes an installation receipt, and never pushes automatically.

## Hard boundaries

- Private experience is not converted into public "compost" without explicit consent.
- Failed AI outputs are not silently deleted; they can become redacted tests and lessons.
- More tokens, models and content are not treated as more value.
- Human-AI complementarity is measured, not presumed.
- A platform cannot call a loop regenerative if human capability, exit and feedback remain open.
- Diversity, resource limits, rights and repair are non-compensable gates.
- No person, group or culture is ranked by a "regeneration score".
