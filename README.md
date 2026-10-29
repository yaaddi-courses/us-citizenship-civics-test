# US Citizenship Civics Test

Pass the 2025 US naturalization civics test. All 128 official USCIS questions in short, repeatable lessons on American government, history, symbols and holidays.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog: a spaced-repetition flashcard course, ready to build and validate with the standard Yaaddi course tooling.

## Sources and accuracy

- Questions and answers come from the official USCIS 2025 naturalization civics test study material (form M-1778, 09/25, 128 questions). The 2025 test asks up to 20 questions and you need 12 correct.
- Names of current officials (president, Vice President, Speaker, Chief Justice) are written as USCIS listed them in October 2026. They change after elections: always check https://www.uscis.gov/citizenship/testupdates before your interview.
- This course is not affiliated with USCIS. It is study help, not legal advice.

This course is study help, not professional advice. See the [Terms of use](https://courses.yaaddi.com/terms/).

## Structure

- `meta.json`: course metadata (title, description, cover image, version)
- `source/`: authoring source (`meta.csv`, `units.csv`, `cards.csv`, `glossary.csv`, images)
- `plan.csv`: table of contents (not shipped in the zip)
- the built `.zip`: generated from `source/` via `build_course_zip.py`

## Editing this course

```bash
python validate_course.py . --source
python build_course_zip.py .
```
