# Notes for Claude

## Versioning
- The version lives in `index.html` as `const VER='x.y.z'` and is shown in small text at the bottom right of every help (?) dialog.
- Bump the last digit with every build that gets pushed (0.8.3, 0.8.4, ...).
- Keep `sw.js` cache name (`boxlog-x.y.z`) and the README title in step with it.
- The owner decides when to move to 0.9.0, 1.0.0 and so on. It is fine to suggest it when a big group of features is finished or things look stable.

## Saved suggestions
- `SUGGESTIONS.md` holds a review list the owner put on hold. When they ask for "the list" or "the suggestions", start from that file. Remove items from it as they are done.
