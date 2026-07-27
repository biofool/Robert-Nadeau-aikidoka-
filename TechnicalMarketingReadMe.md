# Technical Marketing Summary — Robert-Nadeau-aikidoka-

## One-Line Positioning

A content repository preserving the Wikipedia article about Robert Nadeau, a pioneering American aikido teacher (8th dan, Shihan) who trained directly with Aikido founder Morihei Ueshiba.

## Target Users / Personas

- **Aikido practitioners** researching the lineage and teachings of Robert Nadeau
- **Martial arts historians** studying the transmission of Aikido from Japan to America
- **Students of the California Aikido Association** and its member dojos
- **Researchers** exploring the energy and awareness aspects of aikido

## Key Features (Grounded in Code)

- **Wikipedia article preservation** — complete copy of the Wikipedia article about Robert Nadeau (aikidoka) including wiki markup, infobox, references, and further reading (`README.md`)
- **Biographical content** — birth date (March 10, 1937), nationality, rank (8th dan, Shihan), martial art (Aikido), teacher (Morihei Ueshiba) (`README.md`)
- **Teaching lineage documentation** — detailed account of Nadeau's study with Ueshiba in Japan (1962-1964), including alchemical concepts of "two forces" and "levels" of progression (`README.md`)
- **Notable students list** — Richard Strozzi-Heckler, Jack Wada, Richard Moon, Bob Noha, Dan Millman, Paul Bohlman (`README.md`)
- **Collaborator documentation** — Aikido instructors (Frank Doran, Hiroshi Ikeda, Mitsugi Saotome, Seiichi Sugano) and non-Aikido collaborators (Richard Bunch, Peter Ralston, Professor Sig Kuferath) (`README.md`)
- **Publications and media references** — "Moon Sensei" YouTube channel, "O Sensei's Process" DVD, and further reading bibliography (`README.md`)
- **Seminar history** — United States, Switzerland, Israel, New Zealand (`README.md`)

## Technical Differentiators

- **Primary source preservation** — maintains the Wikipedia article content in version control, ensuring it persists even if the Wikipedia article changes
- **Wiki markup retained** — preserves the original Wikipedia edit-source format with templates, citations, and infobox markup
- **Cross-reference with Moon Sensei channel** — links to the YouTube channel that publishes Nadeau's ongoing teachings

## Use Cases

- Reference material for aikido students studying Nadeau's lineage and teachings
- Historical preservation of martial arts biographical content
- Source material for the "Moon Sensei" YouTube channel and related projects (e.g., YT-Moon-Manager, VirtualDojo)
- Research into the transmission of aikido from Japan to Northern California

## Benefits / Value Proposition

- Preserves biographical and historical content in version control — immune to Wikipedia edits or deletions
- Comprehensive reference for the California Aikido Association community
- Links to the "Moon Sensei" YouTube channel for ongoing teachings
- Includes detailed further reading bibliography for deeper research

## Tech Stack

- **Content format**: Markdown with Wikipedia wiki markup
- **Version Control**: Git, GitHub
- **License**: GNU General Public License v3 (`LICENSE`)

## Known Limitations

- **Content-only repository** — no runnable code or application
- **Wikipedia markup not rendered** — the README contains raw Wikipedia templates (e.g., `{{Infobox martial artist}}`, `{{Reflist}}`) that do not render as intended in standard Markdown viewers
- **Static content** — does not automatically sync with the live Wikipedia article
- **Image references missing** — the article references images (e.g., teaching certificate, Ueshiba scroll) that are not included in the repository
- **GPL license unusual for content** — the GPL is typically used for software, not biographical content; the Wikipedia source content is CC-BY-SA licensed
