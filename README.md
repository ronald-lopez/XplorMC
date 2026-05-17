# XplorMC SMP — Mod Downloads

A GitHub Pages site for distributing Forge 1.20.1 mods to server members.

## How to add or update a mod

1. Drop the `.jar` file into the `/mods` folder.
2. Open `mods.json` and add (or update) an entry:

```json
{
  "name": "Mod Name",
  "filename": "exact-filename.jar",
  "version": "1.2.3",
  "description": "One-line description for your friends."
}
```

3. Update `"last_updated"` at the top of `mods.json` to today's date.
4. Commit and push — the site updates automatically.

## How to remove a mod

Delete the `.jar` from `/mods` and remove its entry from `mods.json`.

## First-time GitHub Pages setup

1. Push this folder to a new GitHub repo (e.g. `xplormc-mods`).
2. Go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch** → `main` → `/ (root)`.
4. Save. Your site will be live at `https://<your-username>.github.io/xplormc-mods/` in ~1 minute.

Share that URL with your friends — they just open it and hit Download.
