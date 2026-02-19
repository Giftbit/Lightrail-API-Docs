# Overview
The documents in this directory define our public api docs, published and available through the Mintlify platform.

# Making Changes
## Locally
1. Open this repository in Cursor or your editor of choice.
2. Create a new git branch before editing:
   - In Cursor Source Control, select `Create Branch` and use a descriptive name (for example: `docs/update-payout-quickstart`).
   - Or run: `git checkout -b docs/<description-of-changes>`.
3. Follow the official Mintlify local preview instructions here: [Mintlify Quickstart (CLI preview)](https://www.mintlify.com/docs/quickstart).
4. Run Mintlify locally via the CLI to preview your edits.

## Mintlify
1. Log in to Mintlify and open the docs project from your dashboard.
2. Open the `Editor`
3. Used the branch selector to select, or create a new working branch for your update.
4. Make changes, use the arrow / preview button in the top right nav to preview your changes.
5. Use the `Publish` button to save changes to the branch
6. When ready, use the `Publish` button to submit your changes for review via `Create pull request`

# Publishing
Once your change `Pull request` is made, a developer will review the changes and then merge to main after review.
After merge, Mintlify runs it's own CD workflow to publish the changes.

! If you changes are time sensitive post in the `#project-lightrail` to flag it for review
