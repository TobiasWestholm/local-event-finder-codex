# Event Scanner Runtime

A Codex-native runtime for discovering, scoring, and shortlisting events from user-provided sources and public event listings.

Supports calendar integration.

## Setup

Open this folder in Codex and send the below prompt to configure the project. Replace the FILL IN YOUR PREFERENCE parentheses with your actual preferences.

````md
Set up this event scanner runtime for me.

First create my local preference files:

```sh
cp preferences/taste-profile.example.md preferences/taste-profile.md
cp preferences/sources.example.md preferences/sources.md
```

Then replace the <PLACEHOLDER> blocks in the copied files with my preferences below.

**Interests to add to my taste-profile**

- (FILL IN YOUR PREFERENCE, eg ceramics, techno, traveling, italian wines, DIY, ...)

**Dealbreakers to add**

- (FILL IN YOUR PREFERENCE, eg age restrictions, audience restrictions, fully booked events, ...)

**Primary sources for standard locations**

Default location: (FILL IN YOUR PREFERENCE: eg your home city)
- (_optional_ FILL IN YOUR PREFERENCE: list of sources where you usually find good local events, preferably URLs)

(_Optional_) Additional standard location: (FILL IN YOUR PREFERENCE, eg your working location)
- (_optional_ FILL IN YOUR PREFERENCE: list of sources where you usually find good local events, preferably URLs)

(_Optional_) Then, install the Calendar tool so the scanner can use calendar availability and add selected events when I explicitly ask.

(_Optional_) Then, create a weekly Codex automation from this runtime folder, running (FILL IN YOUR PREFERENCE, eg "weekly on Mondays at 09:00 AM").
````
