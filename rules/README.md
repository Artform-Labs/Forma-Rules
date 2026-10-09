# Rule records

Forma-Rules had no rule schema and no tests when these records were added. New rules use the same fields. Do not rename fields or move a rule to another status to make a conflict go away.

Each file is a list under `rules`. Every record has:

- `id`: stable id, unique across `rules/`
- `status`: `confirmed` or `needs_confirmation`
- `statement`: the rule as it should be applied
- `sources`: one or more `{file, drawing, location}` citations

A `needs_confirmation` record also has `question`, which is the open point for Austin. A conflict between sources is stored as `needs_confirmation`. It is not resolved by picking a value.

`confirmed_on` is set only when Austin confirmed the rule on 2026-10-09 and the drawings do not contradict it.

`PANEL-FABRICATION-STANDARDS.md` from Auditor is cited for V.1.R only. Rules that come from it say so in the statement and in `sources`. The Foldr V1.4 checklist was not in that file. It is outdated on return-bottom weep location, so it was not used. The return-bottom weep rule here is Austin's 2026-10-09 confirmation.
