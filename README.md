# All Things MC94

Agent resource site for the MC94 market center, published with GitHub Pages at https://allthingsmc94.com.

## How this site works

- `index.html` is the whole site (layout, styles and behavior). It rarely needs to change.
- `resources.json` holds every category and every link. **Almost all updates happen here.**
- `CNAME` tells GitHub Pages the site's domain. Do not delete or edit it.

## Notes for Claude (and anyone maintaining this)

To add, move, rename or remove a link or category, edit `resources.json` and push to `main`. The live site updates in a minute or two.

- Each category needs a unique `id` made only of lowercase letters, numbers and hyphens, plus a `name` and an optional `desc`.
- Each resource needs a unique `id`, a `cat` that matches a category `id`, a `title` and a full `url` starting with `https://`. `note` is optional. Set `"pin": true` to show it under "Start here" on the home page.
- Entries marked `"example": true` are placeholders and show an "Example" badge. Remove them when the real link replaces them.
- Keep the JSON valid (commas between entries, none after the last one). Check it before pushing.
- Never put passwords, client information or private documents in this repository. It is public.
- After a change, tell the person what was added and where it appears on the site.
