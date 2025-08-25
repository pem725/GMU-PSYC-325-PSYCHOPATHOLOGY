# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains course materials for **PSYC 325-1: Psychopathology** taught at George Mason University. The course is structured as an academic psychology course focusing on adult psychopathology, diagnosis, classification, epidemiology, and pathogenesis.

## Repository Structure

### Core Files
- `README.md` - Basic repository information
- `psyc325_syllabus.qmd` - Quarto source file for the course syllabus
- `PSYC325_syllabus_fall2025.md` - Markdown version of the syllabus
- `psyc325_syllabus.html` - HTML rendered version of the syllabus
- `GMU-PSYC-325-PSYCHOPATHOLOGY.Rproj` - R project file for RStudio

### Generated Content
- `psyc325_syllabus_files/` - Contains generated HTML assets (CSS, JavaScript libraries) from Quarto rendering

## Development Workflow

### Working with Quarto Documents
This project uses **Quarto** for document generation. The primary source file is `psyc325_syllabus.qmd`.

### Rendering Commands
```bash
# Render the syllabus to all formats (HTML, PDF, DOCX)
quarto render psyc325_syllabus.qmd

# Render to specific format
quarto render psyc325_syllabus.qmd --to html
quarto render psyc325_syllabus.qmd --to pdf
quarto render psyc325_syllabus.qmd --to docx
```

### R Integration
The `.Rproj` file indicates this can be opened as an R project in RStudio, which provides integrated Quarto support.

## Content Structure

The course follows a modular structure:
- **Module 1** (Required): Classification of Psychopathology
- **Module 2** (Optional): Depressive Disorders  
- **Module 3** (Optional): Anxiety Disorders
- **Module 4** (Optional): Personality, Substance Use, and Other Disorders

Each module includes lectures, assigned readings from the [Noba Project](http://nobaproject.com/), movies for clinical examples, and examinations.

## File Management Guidelines

- The `.qmd` file is the authoritative source - make edits there, not in the generated `.md` or `.html` files
- The `psyc325_syllabus_files/` directory contains auto-generated assets and should not be manually edited
- When updating course content, modify the `.qmd` file and re-render to update all output formats

## Academic Context

This is educational content for a university psychology course. All materials should maintain academic rigor and align with scientific approaches to psychopathology as emphasized in the course objectives.