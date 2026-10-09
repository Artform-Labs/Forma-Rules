# Rule records

Forma-Rules had no rule schema and no tests when these records were added. New rules use the same fields. Do not rename fields or move a rule to another status to make a conflict go away.

Each file is a list under `rules`. Every record has:

- `id`: stable id, unique across `rules/`
- `status`: `confirmed` or `needs_confirmation`
- `statement`: the rule as it should be applied
- `sources`: one or more `{file, drawing, location}` citations

A `needs_confirmation` record also has `question`, which is the open point for Austin. A conflict between sources is stored as `needs_confirmation`. It is not resolved by picking a value.

`confirmed_on` is set only when Austin confirmed the rule on 2026-10-09 and the drawings do not contradict it.

The Artform-Labs/Auditor documents (`PANEL-FABRICATION-STANDARDS.md` and the FOLDR checklists) were not readable from this environment (repository not found). Foldr V1.4 is outdated on return-bottom weep location, so that checklist was not used. The return-bottom weep rule here is Austin's 2026-10-09 confirmation.
