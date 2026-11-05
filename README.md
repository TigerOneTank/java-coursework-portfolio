# Java Coursework Portfolio

**From console exercises to desktop applications with persistent data.**

I'm DuckWater, a Cambodian high school student graduating in 2027. This collection brings together my Java coursework in object-oriented programming, Swing, SQLite/JDBC, MVC, and collections.

## Explore the collection

[Download the organized source collection](Java-Coursework-Portfolio.zip), extract it, and open its `README.md` for project links and setup instructions.

**Import status:** The complete collection is available in the ZIP. Publishing the individual folders for direct browsing on GitHub is still pending. The archive contains 171 original Java source files across 18 source collections, including an earlier version of one assignment and a separate reference collection.

| Start with | What to inspect inside the archive |
| --- | --- |
| Vehicle Rental | Vehicle subclasses, insurance interfaces, rental pricing, and database transactions |
| Contact Manager | MVC organization, contact CRUD, search, and photo handling |
| Library Manager | Books/members/loans and service-layer borrowing rules; known defects documented |
| Mini Mart | Product records, images, cart, and order persistence; unfinished methods documented |
| Collections Practice | Maps, sorted lookups, custom keys, and a bus timetable |

Each collection has a README. `docs/INDEX.md` maps original folder names to the organized layout; `docs/RUNNING.md` explains how to build and run the programs.

## Try an example

After extracting the ZIP, open a terminal in its `java-coursework-portfolio` folder. With JDK 17+ and Python 3 installed:

```sh
python3 tools/portfolio.py run collections --main Week4.BusRoute
```

Enter `08:00` to select the `08:30` departure. Windows users can use `py` instead of `python3`.

## Validation and next work

Seventeen non-JavaFX source collections compiled with Java 17. Selected rental-pricing, database-initialization, and timetable checks were run. The JavaFX starter and form-generated Swing exercises require separate tooling; GUI workflows have not been validated end to end.

The review also reproduced a zero-valued library fine and duplicate returns that inflate available copies. Mini Mart cart editing and stock updates remain unfinished. Full findings and reproduction notes are included in `docs/VALIDATION.md`.

## Learning context

These are coursework and guided learning applications, with original scaffolding and comments retained. Reference examples are labeled separately. The collection is not presented as a set of independently designed or production-ready applications.

The November 2026 organization pass added navigation, documentation, privacy-safe sample data, and review checks with AI assistance. It preserved application logic and original learning context. Source databases, contact photos, dependency binaries, and compiled files are excluded; originals in Drive were not changed.
