# Escrow Calendar — AI Builders Guild Demo

A fictional home-closing timeline built by Russell Walsh with AI assistance for Rick's GitHub course and the AI Builders Guild. The site demonstrates a calendar, daily updates, progress indicators, a phone-friendly checklist, an animated closing-to-keys bridge, and sample video playback.

**School demonstration only.** The property and participants are generic. Dates and task statuses are illustrative, not a real transaction record or contract guidance.

## Use the project

Open the published page, browse the calendar, choose **Open phone checklist**, or choose **Removing Contingencies** to open the sample explainer. The four six-second videos are silent demonstration slides created for this public version.

The project uses HTML, CSS, and JavaScript. There are no packages to install or build commands to run. For local viewing with video support, serve the folder with any static HTTP server.

## Files

- `index.html`: page layout, styling, fictional sample data, and interactions.
- `.nojekyll`: serves the files directly through GitHub Pages.
- `assets/videos/demo-1.mp4` through `demo-4.mp4`: newly created silent demo clips.
- `PRIVACY-REVIEW.md`: public-version preparation and validation notes.

## Publish with GitHub Pages

1. Create a repository named `escrow-calendar-demo`.
2. Upload the contents of this folder to the repository root, preserving `assets/videos/`.
3. Commit the files to `main`.
4. In repository **Settings → Pages**, choose **Deploy from a branch**, `main`, and `/ (root)`, then save.
5. Wait for GitHub to display the deployed URL and open it to verify the result.

Video paths are relative, so the project supports a repository subpath.

## Update the same website

Edit `index.html`, commit, and push. GitHub Pages publishes the changed version at the same website address.

The example milestone data is in `const M`, day notes in `const NOTES`, messages in `const UPDATES`, and sample video descriptions in `const VIDEOS`. To change progress, update the relevant `done:true` field and republish.

The current date is calculated in `America/Los_Angeles` when the page loads. The example timeline remains November 2026. Countdown and relative-status labels change with the date; the fictional content does not update automatically. Viewers cannot edit shared progress. There is no login, database, local storage, or two-way synchronization.

## Privacy

This folder is the public school version. It contains no original client videos, private report access, real client names, property address, transaction amounts, or third-party team contact details. Do not upload the private source archive or its original README or videos to this repository.

Public Russell Walsh Realty branding remains. Google Fonts is the only external asset dependency; system fonts provide a fallback.
