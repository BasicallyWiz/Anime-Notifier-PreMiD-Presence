# Anime Notifier PreMiD Presence
 An ababnoned project made to allow the use of discord rich presence on [notify.moe](https://notify.moe) via [PreMiD](https://premid.app/)

## How To Build?
To build this project into a PreMiD presence, you must:
- Download this git.
- Download the [PreMiD Presences git](https://github.com/PreMiD/Presences).
- Go to the PreMiD Presences directory > websites > A, and create a new folder named "Anime Notifier"
- Copy tsconfig.json, presence.ts, and the dist folder from this project into the newly created Anime Notifier folder.
- Open a terminal in the Presences dir and execute the "npm install" command to install required modules.
- Go to the Anime Notifier dir, open a console there, and type "npx tsc -w" in it to build the presence.

## How To Use?
### Once you've built the presence, or have a build of it, you can follow these instructions.
- Open the PreMiD browser extension, and view the list of presences.
- Hold shift, and a button labeled "Load Presence" should display.
- Click the button, and navigate to the dist folder inside the Anime Notifier, and load that presence.
- Congratulations! Discord will now show what page your on while viewing the Anime Notifier Website!