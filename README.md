# IsaacSpot

**IsaacSpot** is a lightweight, spotlight-style overlay for macOS, designed to streamline item lookups in _The Binding of Isaac_. Simply press `Cmd + B` to bring up a compact search bar. Type the name of any item, card, or trinket, and IsaacSpot instantly displays the essential details—letting you stay focused on the game without ever leaving it. 

## Features
- **Global Hotkey**: Quickly open the overlay from within the game (or any app).
- **Search Bar**: Type partial or full item names to find the matching entry.
- **Instant Results**: Pull item details (like effects, synergies, stats) from the wiki or a local database.
- **Always on Top**: The overlay appears above other windows, making it easy to read in real-time.
- **Compact & Minimalist**: Styled similarly to macOS Spotlight, with a simple search field and results panel.

## Requirements
- **macOS** (tested on macOS 10.15+)
- **Python 3.7+**
- Libraries:

## Usage
1. **Install dependencies**
2. **Run the script**
    `python main.py`
3. **Grant Accessibility permissions** (macOS) to allow global hotkey capture.
4. **Press the hotkey** (default is `Cmd + B`) to toggle the overlay.
5. **Type an item name** and press Enter to retrieve info.
