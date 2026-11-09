# tornero

**Shape messy small-business data into a validated star schema.**

tornero profiles spreadsheets and databases, uses an LLM to propose a
dimensional model in a reviewable YAML file, validates that proposal
against the real data (grain uniqueness, orphan keys, double counting),
and generates a ready-to-run dbt project on DuckDB.

The AI proposes. The data verifies. You decide.

> *Tornero* is Spanish for "machinist", someone who turns rough stock
> into a precise, measured part on a lathe. Named in honor of my
> grandfather, who was one.
