---
name: artist-data-verifier
description: Guide for gathering, verifying, and organizing real-time social media data for artists, specifically for talent scouting, campaign planning, and pitch decks. Use when asked to compile artist rosters, verify follower counts, or gather campaign context.
---

# Artist Data Verifier

This skill provides a standardized workflow for gathering and verifying real-time social media data for artists, ensuring accuracy for pitch decks and campaign planning.

## Core Workflow

When tasked with compiling or verifying an artist roster, follow these steps:

### 1. Initial Data Gathering
- Receive the initial list of artists from the user.
- If the user mentions a specific campaign or manager (e.g., "the campaign siyathemanager is referring to"), search for that context to identify any missing artists.
- Create a preliminary markdown table to track the artists and their known handles.

### 2. Handle Verification & Context Search
- Search for each artist to confirm their exact social media handles (primarily Instagram, unless otherwise specified).
- Look for recent news, campaign associations, or notable achievements (e.g., "Multi-award winning", "Recent collaboration with X").
- **Crucial:** Do not rely solely on search snippets for follower counts, as they are often outdated.

### 3. Real-Time Data Verification
- To get accurate, real-time follower counts and engagement rates, use third-party analytics platforms.
- **Preferred Platforms:** Search for the artist\'s handle on `Social Blade` (e.g., `https://socialblade.com/instagram/user/{handle}`).
- Use the `browser_navigate` tool to visit the specific Social Blade profile page.
- Extract the exact `followers` count and `engagement Rate` from the page content.
- If Social Blade data is unavailable or the page fails to load properly, try alternative analytics sites like Modash or HypeAuditor via search, or visit the artist\'s actual Instagram profile directly.

### 4. Compilation and Delivery
- Compile the verified data into a clean, professional Markdown table.
- Include columns for: Artist Name, Social Media Handle (with link), Verified Followers, and Recent Highlights/Notes.
- Add a section below the table detailing any relevant campaign context discovered during the search (e.g., key production personnel, upcoming launch dates).
- Deliver the final markdown file to the user.

## Best Practices
- **Accuracy over Speed:** Always verify follower counts via live analytics pages rather than relying on cached search results.
- **Context is Key:** Pay attention to the campaign context provided by the user. It often contains clues for finding additional artists or relevant highlights.
- **Professional Formatting:** Pitch decks require clean, easy-to-read data. Ensure the final markdown table is well-structured.
