# House Sitting Guide

A simple multi-page [Astro](https://astro.build) site with everything a house sitter needs to look after our home and dogs.

## Pages

- **Home** (`/`) — Daily dog schedule: potty breaks, feeding times and amounts.
- **Using the TV** (`/tv`) — Step-by-step instructions for the television and streaming.
- **The Dogs** (`/dogs`) — Profiles, quirks, and care notes for each dog.
- **House Info** (`/house`) — Wifi, thermostat, trash day, and general house notes.
- **Emergencies** (`/emergency`) — Vet, contacts, and what to do if something goes wrong.

## Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:4321`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## Editing the content

All the schedule, dog, and house details live in `src/data/info.js`.
Update that one file and every page stays in sync.
