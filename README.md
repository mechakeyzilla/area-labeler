# Area Labeler for Owlbear Rodeo

Area Labeler is a specialized extension designed for Game Masters using Owlbear Rodeo. It allows for the rapid, intelligent placement of map labels in the traditional style with automatic, context-aware sequence incrementing.

## Features

* **Intelligent Sequencing:** Automatically increments labels (e.g., A1 → A2, A3a → A3b).
* **Click-to-Place:** Simply type your starting label and click anywhere on the map to drop a parchment-styled circular marker.
* **GM-Friendly Tools:**
    * **Lock/Unlock All:** Toggle the locked state of all labels created by the extension to prevent accidental movement.
    * **Undo:** Correct mistakes instantly with a single button click. (CTRL-Z already used globally by Owlbear; this doesn't use that shortcut.
* **Accessibility & UX:** Includes input validation, clear visual feedback, and auto-focusing for rapid labeling sessions.

## Installation

1. Open Owlbear Rodeo.
2. Navigate to **Profile > Extensions > Add Extension**.
3. Paste the URL:
4. Enable the tool from the Extension bar.

## Usage

* **Entering Labels:** Type your label into the "Area Label" input field. The field supports A-Z, 0-9, and characters `:`, `_`, `-`.
* **Placing:** Once you type a label, click on the map to place a parchment circle. The tool will automatically increment the label in the input field for your next click. Before the next label is placed the previous label can be moved.
* **Locking:** Use the "Lock All" button to fix labels in place so they aren't moved during token movement.
* **Done:** Press the "Done" button or the `ESC` key to stop the labeling tool.

## Technical Details

* **Layer:** All markers are placed on the **NOTE** layer.
* **Visibility:** Markers are created in the **Hidden** state by default for GM privacy.
* **State:** The extension saves your last-used label, so you can pick up exactly where you left off in your next session.
This was vibe-coded by Realm Referee. Open to feedback and branching.
