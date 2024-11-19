# Devin Extension

Launch and manage Devin sessions right from your IDE.

![Devin Extension Showcase](assets/devin-extension-showcase.gif)

## Using the Extension

Open the Devin tab in the activity bar (on the left, unless you changed the layout). We recommend pinning this tab.

### Keyboard shortcuts:

- **⌘ + G** to start a new Devin. If you have a snippet of code selected, it will be attached as context.
- **⌘ + ⇧ + G** to add context to the current input (either new Devin or reply to the current Devin).

### Managing Devins:

At the bottom of the Devin sidebar tab, you can see the "Your Devins" section. Click a Devin to open it in the chat and use the icons on the right to manage them:

1. Connect to Devin's machine via VS Code Remote SSH ('VS Code' icon).
2. Open the Devin session in the browser ('Globe' icon).
3. Archive Devin sessions to keep your sidebar decluttered ('Archive' icon). Devin automatically goes to sleep when archived.

### Reviewing Devin's code:

There are two main ways to review Devin's code:

1. View the changes live in your VS Code:

- View a summary of all the changes Devin made by clicking the 'Global Diff' icon in the "Your Devins" section.
- Expand the Devin to see and open (read-only) diffs of indvidual files.

2. View Devin's PR on GitHub by clicking the 'GitHub' icon in the "Your Devins" section.

If you need to make changes, use the **Checkout PR** button to view & edit the code locally.
