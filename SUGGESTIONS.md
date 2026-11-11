# Saved suggestions (from the review after 0.8.3, 2026-11-10)

On hold at the owner's request. Bring these up when asked for "the list" or "the suggestions".
Suggested next build: 1, 2, 5, 6, 8, 9 and 16.

## Data safety
1. Ask the browser for persistent storage (navigator.storage.persist) so the phone does not clear the app's data when space is low or the app is unused for a while.
2. Import > Replace wipes everything with no safety net. Save an automatic backup right before any Replace.
3. Merge can bring back old values: a pick edited after a backup is overwritten by the older copy. Add a "last changed" time to each record and keep the newer one when merging.
4. "Saved At" in the backup CSV is in UTC, not local time (a 9:57 pm pick shows 02:57 the next day). Write local time.

## Workflow
5. Renaming a category leaves every item with the old name (stamp rule). On rename, offer "Also update the X items that use this category?".
6. Renaming a recipient splits their history: old picks stay under the old name. Offer to update past picks too.
7. Deleting a category or recipient that is in use gives no warning. Show how many items or picks use it first.
8. Duplicate items are easy to create: a search that only matches a historical item leads to "Add new item". Offer "This matches a historical item. Restore it?" and warn when a new item exactly matches an existing one.
9. It is hard to see what is selected before saving. Make the button read "Save 2 x Long grain", and confirm "Saved 2 x Long grain for <recipient>".
10. Picked dates only default to today. Add quick buttons such as "This week" and "All dates".
11. The email has no To address. Store an email address with each recipient and fill it in.

## Screens
12. Delete, Rename and New Category use the phone's built-in pop-ups, which look technical and show the web address on iPhone. Use in-app dialogs like the help box.
13. The Items table is very wide because of three buttons per row. Tap a row to open Edit / Historical / Delete instead.
14. The Picking list is in the order items were added. Sort it the same way as the Items list.
15. "Copy as fixed width" only lines up in fixed-width fonts; most email apps use proportional fonts. Consider removing it now that the email has a real table.

## Technical
16. The app tries the internet first and only falls back to its saved copy when that fails, so it opens slowly on a weak signal. Open from the saved copy right away and update in the background.
17. Photos are embedded directly in the email. iPhone Mail shows them, but Gmail and Outlook often hide them. Check with one real email to a Gmail reader.
