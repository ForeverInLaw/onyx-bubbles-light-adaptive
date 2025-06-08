# Onyx Bubbles - Adaptive Light & Dark Theme for Seelen-UI

A custom CSS style definition for the Seelen toolbar, providing a light/dark "bubble" appearance in the normal state and adapting to the focused window's background color when maximized.

This file contains the YAML definition for the style, including metadata and the CSS code.

## Features

*   **Fully Adaptive**: Intelligently transitions from a centered "bubble" style to a full-width bar that matches the color of any maximized application.
*   **Bubble Style:** Toolbar items have a rounded, bubble-like appearance in the normal state.
*   **Centered Toolbar:** In the normal state, the toolbar is centered on the screen using padding and positioning techniques.
![default](https://github.com/ForeverInLaw/onyx-bubbles-light-adaptive/blob/main/default.png?raw=true)

*   **Smooth Transitions:** Animations for padding, gap, width, position, and background color ensure smooth visual transitions between states.
*   **Adaptive Maximized State:** When a window is maximized, the toolbar:
    *   Expands to full screen width.
    *   adopts the background color of the focused application.
    *   Item backgrounds become transparent, using hover/active colors tailored for the adaptive state.

![dark themed](https://github.com/ForeverInLaw/onyx-bubbles-light-adaptive/blob/main/dark_themed.png?raw=true)
![light themed](https://github.com/ForeverInLaw/onyx-bubbles-light-adaptive/blob/main/light_themed.png?raw=true)
- **Automatic Dark/Light Mode**: Seamlessly switches between light and dark themes to match your system's settings. No manual switching required.
- **Cohesive Styling**: All UI elements, including popups, menus, and tooltips, are consistently styled across both light and dark modes.

## Installation

This file contains a specific YAML structure defining a toolbar style. It is likely intended to be used this way:

1.  **Placing the file directly:**
    *   Navigate to your Seelen UI theme directory using buttons General -> Themes
    *   Click `Folder` icon
    *   Put there `onyx-bubbles-light-adaptive.yaml`
    *   Select theme and activate it
    *   Click `Save` button in the top-right corner

## Credits

*   **Original Author:** 1Developpeur (@1Developpeur on GitHub) (OnyxToolbar)
*   **Reworked by:** ForeverInLaw (@ForeverInLaw on GitHub)

*Note: The author handles are reproduced directly from the source file's metadata.*

---
