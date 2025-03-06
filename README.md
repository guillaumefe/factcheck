# FactCheck

An automated fact checker with an optional moral evaluation step. **FactCheck** helps users break down any statement into concrete facts, assess their scientific relevance, and optionally evaluate moral considerations.

## Features

- **Multi-Step Wizard**  
  Enter your statement, list the necessary facts, determine factual relevance, and optionally perform a moral check.
  
- **Dynamic Interface**  
  Progress is highlighted step by step. The interface automatically shows or hides form elements based on user choices.
  
- **Local Storage (IndexedDB)**  
  All evaluations are stored in your browser’s IndexedDB. No server is required.
  
- **History & Editing**  
  Each completed evaluation appears in the History panel. Click on an entry to reload and edit it (replacing the old entry).
  
- **PDF/Print Export**  
  Export or print a simple table of all stored evaluations.

## Usage

1. **Open** `index.html` in a modern web browser that supports IndexedDB.  
2. **Follow the steps** to input a statement and relevant facts.  
3. **Decide** whether you want a moral check.  
4. **Finish** to see the results and add the evaluation to the History.  
5. **Edit or Delete** entries from the History at any time, or clear them all.

## Technical Notes

- **Pure JavaScript**: No external libraries are required.  
- **Responsive Layout**: Basic CSS ensures a neat display on mobile and desktop.  
- **IndexedDB**: Data is stored locally, right in your browser.

## License

FactCheck is released under the **GNU General Public License v2 (GPLv2)**.  
Feel free to modify and distribute this code under the terms of the GPLv2.
