# D&D Character Sheet Technical Specification

## Overview

Static site D&D character sheet implementation using Alpine.js (interactivity), marked.js (markdown parsing), Bulma (styling), and Font Awesome (icons) with JSON-based data persistence.

## Technical Stack

- Alpine.js: Reactive data binding
- marked.js: Markdown parsing for notes
- Bulma: CSS framework
- Font Awesome: Icon set
- localStorage: Client-side persistence

## Data Architecture

JSON schema containing:

- Character metadata (name, class, race, level)
- Ability scores and calculated modifiers
- Skills with proficiency markers
- Equipment inventory and currency
- Spell slots and known spells
- Markdown-formatted background text
- Combat statistics and hit point tracking
- Experience progression data

## Functional Requirements

1. Character creation interface
2. JSON import/export functionality
3. Automatic derived stat calculations
4. Print-optimized layout option
5. Markdown rendering for text fields
6. Responsive design implementation

## Implementation Phases

### Phase 1: Foundation

- HTML scaffold with metadata
- Dependency integration
- Alpine data model definition
- Base Bulma layout implementation

### Phase 2: Core Development

- Character sheet section construction
- Derived value calculation logic
- Markdown parsing integration
- JSON persistence implementation

### Phase 3: Interface Enhancement

- Interactive component development
- Icon integration for UX improvement
- Responsive breakpoint configuration
- Print stylesheet creation

### Phase 4: Quality Assurance

- Cross-browser compatibility testing
- Performance optimization
- Error handling for data operations
- Documentation and deployment preparation

## 🧞 Astro Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
