Paste-Into-P4Merge
====================

Mac Automator UI to allow pasting into P4Merge.

P4Merge (https://www.perforce.com/products/helix-core-apps/merge-diff-tool-p4merge) is a powerful diff/merge tool that shows intra-line changes.  However, it requires text to be in existing files before they can be opened.

PasteDiff is an Automator Application which takes in two text inputs, creates appropriate temporary files, and passes them into P4Merge.
PasteUnidiff is another Automator Application which takes in a text input (a unified diff), creates appropriate temporary files, and passes them into P4Merge so you can see the intra-line changes.  (This is very rough right now)

You can open the .app files in Automator to edit the workflow.
