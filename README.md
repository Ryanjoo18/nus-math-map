# NUS Mathematics Interactive Course Map

An interactive, web-based visualisation of course dependencies for Mathematics courses at the National University of Singapore (NUS). 

Inspired by the [UC Berkeley Mathematics Interactive Course Map](https://math.berkeley.edu/~musa/exposition.html).

## Overview
This tool is designed specifically for Mathematics majors. 
To keep the map clean and relevant, the following courses are filtered out:
- Courses targeted at Engineering and Computer Science (e.g., MA15xx).
- Internship and Research-coded courses.
- Bridging courses (e.g., MA13xx).

## Features
- **Live data**: Fetches real-time course information from the [NUSMods API](https://api.nusmods.com/v2/).
- **Hierarchical layout**: Courses are organised by level (1000, 2000, etc.) using the Dagre layout engine.
- **Interactive highlighting**: Clicking a course node highlights its entire prerequisite path.
- **Information card**: View course titles and descriptions without leaving the map.

## Tech Stack
- **Cytoscape.js**: Graph theory library for visualisation.
- **Dagre**: Directed graph layout for Cytoscape.
- **NUSMods API V2**: Source of truth for academic year data.
- **Vanilla JS/HTML5**: Lightweight and dependency-free frontend.

## How to Use
1. Clone this repository.
2. Open `index.html` in your web browser.