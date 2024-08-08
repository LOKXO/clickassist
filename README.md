
# ClickAssist
## Idea from @sh1d0wg1m3r

This is a simple Python script that simulates automatic mouse clicks. It allows you to toggle the auto-clicking functionality with a configurable hotkey and customize various settings such as the click button, number of clicks, and delay between clicks.

## Features

- Toggle auto-clicking with a configurable hotkey (default: `\`)
- Simulate left, right, or middle mouse clicks
- Randomize the number of clicks per activation (configurable range)
- Randomize the delay between each click (configurable range)
- Control verbosity of click logging

## Usage

1. Configure the settings in the `config` dictionary at the beginning of the script.
2. Run the script: `python auto_clicker.py`
3. Press the configured toggle key (default: `\`) to activate or deactivate the auto-clicker.
4. When activated, click anywhere on the screen to trigger a burst of automatic clicks.
5. Press the toggle key again to deactivate the auto-clicker.

## Requirements

This script has no external dependencies and uses only built-in Python modules. It should work on any Windows system with Python installed.

## Configuration

You can customize the auto-clicker behavior by modifying the values in the `config` dictionary:

- `toggle_key`: The key to toggle the auto-clicker on/off (default: `\\`)
- `click_button`: The mouse button to simulate clicks (options: `'left'`, `'right'`, `'middle'`)
- `min_clicks`: The minimum number of clicks per activation (default: 8)
- `max_clicks`: The maximum number of clicks per activation (default: 9)
- `min_delay`: The minimum delay between clicks in seconds (default: 0.038)
- `max_delay`: The maximum delay between clicks in seconds (default: 0.047)
- `verbose`: Control whether to print click logs or not (default: `True`)

### Note

This README file was improved with the help of AI
