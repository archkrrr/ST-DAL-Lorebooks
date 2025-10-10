# Date A Live - SillyTavern World Info Repository

![Date A Live Logo Banner](https://i.imgur.com/83J22gV.png)

Welcome to a high-fidelity *Date A Live* World Information repository for SillyTavern. This project provides an exceptionally detailed and lore-accurate set of files designed to create an immersive and consistent AI roleplaying experience within the *Date A Live* universe.

This repository is actively maintained and improved for my own roleplays. Always check back for the latest version.

## Project Origin

This lorebook was never intended for a public release. For a long time, it was a purely personal project, meticulously crafted and constantly refined to support my own private roleplaying sessions. Over time, it grew into a monster—a beast of a lorebook clocking in at **over 40,000 tokens**. My only goal was to create a perfectly consistent and deeply immersive world for myself.

However, after looking at the other *Date A Live* lorebooks available to the public, I felt a sense of disappointment. The quality was low, the details were often wrong, and the overall experience felt shallow and inaccurate. Frankly, I felt bad that the community didn't have a better resource.

That feeling is what led to this repository. I decided to take my personal, obsessively detailed lorebook, clean it up, and release it to the public in the hope that it can provide everyone with the kind of high-quality, lore-accurate roleplay that I've been enjoying. This is my effort to give back and raise the standard for what a good lorebook can be.

## A Note on Creation

It is important to be transparent about this project's development: this entire lorebook was created in collaboration with AI. I served as the director, editor, and final arbiter of quality, but the text itself was generated and refined through an extensive, iterative process. While I have made every effort to ensure accuracy and internal consistency, the nature of AI generation means you shouldn't expect perfect consistency between every single entry.

## Files & Usage

This repository contains two primary types of lorebook files, designed to be used together or separately depending on your needs.

### 1. The Core Lorebook (`Date a Live [Version].json`)

This is the main, essential file. It contains over 100 detailed entries covering:
- **Characters:** All major Spirits, Ratatoskr crew, DEM operatives, and key human characters.
- **Factions:** In-depth descriptions of Ratatoskr, DEM, and the AST.
- **World Mechanics:** Detailed explanations of Spirits, Angels, Astral Dresses, Sephira Crystals, Inversion, and more.
- **Hard Rules:** Specific, unbreakable rules for the AI to follow, ensuring consistency and preventing common lore mistakes (e.g., Shido having an Astral Dress).

### 2. The Storyline Addon (`Date a Live Arcs.json`)

This is an **optional but highly recommended** companion file. It breaks down the entire *Date A Live* anime/light novel plot into sequential arcs.
- **Purpose:** To give the AI context of "what has happened so far" in the story.
- **How it Works:** By enabling arcs sequentially, you can guide the roleplay through the canon timeline. For example, if you only enable "Arc 1" and "Arc 2," the AI will know that Tohka and Yoshino have been sealed, but it will have no knowledge of Kurumi or the Yamai twins yet.
- **AI Instructions:** Includes a detailed entry that instructs the AI on how to interpret the arcs and integrate a user's original character into the narrative logically.

### How to Install

1.  **Download the Files:** Click on the `.json` file you want (`Date a Live [Version].json` is the main one) and use the "Download raw file" button.
2.  **Open SillyTavern:** Launch your SillyTavern instance.
3.  **Navigate to World Info:** Click the icon that looks like a globe (usually on the right-hand side menu) to open the World Info panel.
4.  **Import:** At the bottom of the World Info panel, find the "Import" button.
5.  **Select File:** Choose the `.json` file(s) you downloaded. The entries will be automatically imported.
6.  **Enable Entries:** By default, all entries will be enabled. If using the `Date a Live Arcs.json` file, it is recommended to disable the arcs that take place after your desired starting point.

### Recommended Settings for the Best Experience

To get the absolute best performance and most immersive roleplay out of this comprehensive lorebook, the following setup is highly recommended:

-   **AI Model:** **Google Gemini 2.5 Pro** (if available). The massive context window and advanced reasoning capabilities of this model are ideal for wrangling a beast of this size and making sense of the over 40,000 tokens of information.
-   **SillyTavern Extension:** **Lucid Loom**. This lorebook was designed and tested with the structured data handling of Lucid Loom in mind. Using it will ensure the AI can make the most logical and context-aware use of the provided information.

While the lorebook will function with other models and setups, this combination will provide the highest fidelity experience.

## Key Features

- **Unmatched Detail:** Each entry is written to provide maximum context, including character mannerisms, speech patterns, and thematic importance.
- **Roleplay-Focused:** Character entries include `Example Lines` to help the AI capture the perfect voice.
- **Canon-Compliant:** Meticulously researched to align with the light novel and anime canon.
- **AI-Proofed:** Includes hard-coded `RULE` entries to prevent the AI from making common lore errors, ensuring a consistent experience.
- **Flexible Storytelling:** The optional `Arcs` file allows you to start your roleplay at any point in the *Date A Live* timeline.
- **OC Friendly:** The framework is designed to be accommodating to original characters, with specific instructions for the AI on how to logically integrate them.


## Contributing & Feedback

Found an error, a typo, or have a suggestion for an improvement? Please feel free to open an "Issue" on this GitHub repository! Your feedback is invaluable in making this the best possible resource for the community.
