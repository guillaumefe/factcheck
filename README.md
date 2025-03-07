# FactCheck

An automated fact checker that helps break down any statement into concrete facts, assess their scientific veracity, and optionally attach proofs/references.

## Features

**Multi-Step Wizard**  
  1. **Enter Statement**: Provide any statement to be evaluated.  
  2. **List Facts**: Identify the key facts required to validate the statement.  
  3. **Determine Materiality**: Mark each fact as *true* or *false* (i.e., whether it is scientifically sound).  
  4. **Add Proofs**: If at least one fact is marked *true*, you can optionally add proofs or references for those facts.  
     - If no facts are marked *true*, this step is automatically skipped.  
  5. **Final Result**: Shows the overall veracity percentage, color-coded:
     - **Red** if ≤ 50%
     - **Orange** if 51–90%
     - **Green** if > 90%

**History & Editing**  
  - Each completed evaluation is added to the History panel. 
  - You can edit and entry, preserving the same ID.
  - You can clone an entry, with a new unique ID.

**Import/Export JSON**  
  - **Export**: Save all evaluations as a single JSON file.  
  - **Import**: Restore previously exported evaluations to exactly the same state.

**PDF/Print Export**  
  - One-click export to PDF (or direct printing) from the History panel.  
  - Generates a cover page (title, date, count of statements), followed by a table of statements (color-coded veracity) and detailed fact-proof listings.  
  - Each statement in the table is a clickable link pointing to its details.

## Usage
1. **Open** `index.html` in a modern browser (IndexedDB support required).  
2. **Enter a statement** and follow the wizard steps:  
   - List facts  
   - Mark each as true/false  
   - Optionally add proofs if any fact is true  
3. **Finish** to see the final result and add it to your History.  
4. **Use the History** to review, edit, delete, or clear all evaluations.  
5. **Import or Export** your current data as JSON via the buttons under “Enter your statement.”  
6. **Export to PDF** to generate a cover page, summary table, and detailed pages for each statement.

## Technical Notes

- **Pure HTML/CSS/JavaScript**: No frameworks or external libraries.  
- **IndexedDB**: Evaluations persist locally, even after page refresh.  
- **Responsive**: Basic CSS ensures functionality on desktop or mobile.  
- **Color-Coding**: Veracity percentage ≤ 50% is red, 51–90% is orange, and > 90% is green.

## License

FactCheck is released under the **GNU General Public License v2 (GPLv2)**.  
You are free to modify and redistribute this code under its terms.
