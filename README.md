# Fantasy Wiki

A structured, interlinked knowledge base for optimal fantasy football strategies and league-specific data.

## Project Overview

This repository serves as a centralized hub for a fantasy football team's collective knowledge. It includes strategy guides, platform rules, and season-specific insights, primarily focused on the Sports.ru fantasy platform.

## Repository Structure

- `wiki/`: Contains all wiki pages in Markdown format.
  - `wiki/index.md`: The table of contents for the entire wiki.
  - `wiki/log.md`: A record of all updates and ingestions.
- `raw/`: Immutable source documents (articles, JSON data, rules) used to populate the wiki.
- `AGENTS.md`: Guidelines and workflows for AI agents managing the wiki.

## How to Use

- **Browse**: Start with the [Wiki Index](wiki/index.md) to explore available topics.
- **Contribute**: Add new source materials to the `raw/` folder and use the ingest workflow defined in `AGENTS.md` to update the wiki.
- **Consult**: Use the wiki to answer strategic questions or prepare for the upcoming gameweeks.

## Maintenance

The wiki is maintained following a strict workflow to ensure consistency, proper citations, and interlinking between concepts. Refer to `AGENTS.md` for detailed instructions on the ingestion process and page formatting.
