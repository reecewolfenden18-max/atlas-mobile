# ATLAS Mobile

A mobile-first personal assistant interface prototype for Android and desktop browsers.

## Included
- Terminal-inspired dark interface with a gently animated neural-core graphic
- Local conversation history, project list and personal notes
- Speech-to-text dictation where supported by the browser
- Device text-to-speech with selectable installed voices
- Export and delete controls for local data
- Progressive Web App manifest and service worker

## AI connection status
This prototype does **not** contain an AI model and does **not** directly connect to a ChatGPT account. The Ask ChatGPT button copies the latest saved message and opens ChatGPT for manual pasting. No ChatGPT password, session or API key is collected or stored. A direct API integration would require separate API credentials and may incur separate usage charges.

## Publish with GitHub Pages
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Wait for the Pages deployment to finish.
5. Open the published HTTPS URL in Chrome on Android and choose **Install app** or **Add to Home screen**.

## Local data and privacy
Messages, projects and notes are stored in browser localStorage on the device. Clearing browser data can remove them. Use **Export My ATLAS Data** for a backup. Do not save passwords, API keys or sensitive information in this prototype.

## Voice
Voice input depends on Android browser speech-recognition support and microphone permission. Spoken output uses voices installed on the device. A specific film-character or actor voice is not included.