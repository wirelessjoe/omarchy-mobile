# PR 16 review captures

Real Pixel 4 captures for the AI Agent shortcut review. The source PR is a single commit; these evidence files live on a separate branch.

- `no-agent-picker.png`: launch the shipped shortcut with no default selected, from a workspace containing a temporary review terminal.
- `picker-cancelled.png`: cancel through the menu close lifecycle (the same cancel handler as Escape/backdrop). Omarchy home remains on the newly opened empty workspace; the previous terminal stays on its original workspace. No default is selected by cancellation.
- `chosen-agent-terminal.png`: restore the original Codex choice and launch the same shortcut. The existing Omarchy launcher opens its terminal and Codex welcome screen. No account sign-in or API operation is performed.
- `state.json`: observed workspace IDs and cancellation state; no device or network identifiers.

The temporary review terminal is removed, the original default is restored, and the chosen-agent window is left available after capture. Screenshots were inspected for account information, credentials, network names and device identifiers before publication.
