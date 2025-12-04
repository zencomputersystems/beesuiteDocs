# Copilot Instructions for beesuiteDocs

## Overview
This is a Sphinx-based documentation project for beesuite, an HR software suite (Employee Lifecycle Suite). It documents user workflows including login, administration, employee management, and location tracking (beewhere).

## Architecture
- **Structure**: Flat RST file organization in `docs/source/` with images in `docs/source/images/`
- **Build Output**: HTML generated to `docs/build/html/`
- **Theme**: Read The Docs theme (`sphinx_rtd_theme`)
- **Extensions**: `sphinx.ext.autosectionlabel` for automatic section labeling

## Build and Development Workflow
- **Build Docs**: `cd docs && make html` (generates HTML in `docs/build/html/`)
- **Clean Build**: `cd docs && make clean html`
- **Serve Locally**: Open `docs/build/html/index.html` in browser
- **Dependencies**: Requires Sphinx and sphinx-rtd-theme (install via pip if needed)

## Conventions
- **Content Format**: Use reStructuredText (.rst) with standard Sphinx directives
- **Images**: Place in `docs/source/images/` and reference as `.. image:: images/filename.png`
- **Cross-References**: Use autosectionlabel for automatic linking (e.g., `:ref:`section-title``)
- **Structure**: Each major feature gets its own .rst file (e.g., `administration.rst`, `employee.rst`)
- **Navigation**: Update `docs/source/index.rst` toctree to include new pages

## Key Files
- `docs/source/conf.py`: Sphinx configuration (project info, extensions, theme)
- `docs/source/index.rst`: Main table of contents
- `docs/Makefile`: Build automation
- `docs/source/images/`: Screenshots and diagrams for documentation

## Patterns
- **User Guides**: Step-by-step instructions with numbered lists and images (see `administration.rst`)
- **Section Headers**: Use overline/underline for main sections (e.g., `***************`)
- **Image Captions**: Include alt text and width specifications for accessibility</content>
<parameter name="filePath">/mnt/d/Development/beesuiteDocs/.github/copilot-instructions.md