# Java Coursework Portfolio

**From console exercises to desktop applications with persistent data.**

I'm DuckWater, a Cambodian high school student graduating in 2027. This collection brings together my Java coursework so it is easier to explore the code, run individual exercises, and follow what I have been learning.

The projects cover **Java · object-oriented programming · Swing · SQLite/JDBC · MVC · collections**. They include guided assignments, small experiments, unfinished features, and reference material. Original scaffolding and comments are preserved. These are learning applications, not production systems.

## Start here

| Project | What to look at | Current scope |
| --- | --- | --- |
| [Vehicle Rental](projects/vehicle-rental) | Vehicle subclasses, insurance interfaces, rental pricing, transactions | Guided coursework application; strongest architecture example |
| [Contact Manager](projects/contact-manager) | MVC organization, contact CRUD, search, photo handling | Desktop database application |
| [Library Manager](projects/library-manager) | Books/members/loans, service layer, borrowing rules | Substantial prototype; fines and return handling need fixes |
| [Mini Mart](projects/mini-mart) | Product records, images, cart, saved orders | Shop prototype; cart editing and stock updates unfinished |
| [Collections Practice](exercises/collections) | Maps, sorted lookups, custom keys, bus timetable | Small examples that are easy to compile and inspect |

## Try a small example

With a JDK 17+ and Python 3 installed, from this repository's root:

```sh
python3 tools/portfolio.py run collections --main Week4.BusRoute
```

Enter `08:00`. The example selects the `08:30` departure. It uses `TreeMap.ceilingKey` to find the next timetable entry. Use `py` instead of `python3` on Windows if needed.

[Setup and running](docs/RUNNING.md) · [All collections](docs/INDEX.md) · [Validation and known issues](docs/VALIDATION.md) · [Source provenance](docs/PROVENANCE.md)

## How the collection is organized

- **projects/** — larger desktop and console applications, each with its own source folder and guide.
- **exercises/** — focused practice in collections, JDBC, Swing, and introductory Java/JavaFX.
- **versions/** — the second supplied version of the vehicle rental assignment, preserved for comparison.
- **references/** — reference examples, clearly separated from portfolio projects.
- **tools/** — a small build/run helper added during portfolio organization.

These are separate programs in one repository. They are not merged into a single application because several use overlapping class names and different startup requirements.

## What this records

My coursework moves from entry points and console interaction to SQL persistence, event-driven interfaces, and separating model, view, controller, and data-access responsibilities. Keeping the early exercises alongside the larger applications makes that development visible.

The November 2026 organization pass added navigation, documentation, privacy-safe sample data, and validation notes. It did not rewrite the application logic or create a fictional development timeline. Teacher-provided scaffolding remains visible, and reference examples are not claimed as original projects.

## Next work

1. Fix and test library returns, fine calculation, and edited copy counts.
2. Finish Mini Mart cart lookup/editing and transactional stock updates.
3. Add database initialization to the to-do app and strengthen input validation.
4. Add real desktop screenshots after checking the GUI workflows locally.
5. Document personal extensions separately from the assignment requirements.
