# Rule records

Forma-Rules had no rule schema and no tests when these records were added. New rules use the same fields. Do not rename fields or move a rule to another status to make a conflict go away.

Each file is a list under `rules`. Every record has:

- `id`: stable id, unique across `rules/`
- `status`: `confirmed` or `needs_confirmation`
- `statement`: the rule as it should be applied
- `sources`: one or more `{file, drawing, location}` citations

A `needs_confirmation` record also has `question`, which is the open point for Austin. A conflict between sources is stored as `needs_confirmation`. It is not resolved by picking a value.

`confirmed_on` is set when Austin confirmed the rule (2026-10-09 or 2026-11-05) and the drawings do not contradict it.

`PANEL-FABRICATION-STANDARDS.md` from Auditor was the source for many V.1.R rivet and weep records. Austin Durbin (abd@art-form.com), via Sydney on 2026-11-05, confirmed that rivet and weep schedule rules apply to all panel types. The Foldr V1.4 checklist was not in that Auditor file. It is outdated on return-bottom weep location, so it was not used. The return-bottom weep rule here is Austin's 2026-10-09 confirmation. Where Austin's 2026-11-05 shop answer conflicts with an earlier Foldr/SOP reading, the shop answer wins for this repo.
