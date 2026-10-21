# Game Library

A free website that lists your browser games. It has no server and costs nothing to host.

## What's in this folder

    index.html                          the library homepage (the list of games)
    games/seven-floors-down/index.html  your first game
    README.md                           these instructions (optional to upload)

## Put it online with GitHub Pages (free)

1. Make a free account at github.com.
2. Click the + at the top right, then **New repository**. Give it a name such as `games`.
   Choose **Public**, then click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Open this unzipped folder, select everything inside it (`index.html`, `games`, `README.md`),
   and drag it all onto the GitHub page. Dragging works for folders; the "choose your files"
   button does not. Do not drag the outer folder itself, only what is inside it.
5. Scroll down and click **Commit changes**.
6. In the repository, open **Settings**, then **Pages**. Under "Build and deployment", choose
   **Deploy from a branch**, pick **main** and the **/ (root)** folder, then click **Save**.
7. Wait a few minutes. Your library will be at `https://YOUR-USERNAME.github.io/games/`
   (swap in your username and repository name). The address also shows at the top of the Pages settings.

If you see a 404, wait a little longer and check that `index.html` is at the top level of the
repository, not inside another folder.

## Add a new game later

1. Make a folder inside `games/` named after the game, for example `games/my-next-game/`.
2. Put the game's page in it and name that file exactly `index.html`.
3. Open the top-level `index.html` and copy the game entry inside the `GAMES` list. Paste it at
   the top, then change `id`, `title`, `desc`, `tags`, `path` and `colors`.
4. On GitHub, upload the new folder and the edited `index.html` the same way as before
   (**Add file**, then **Upload files**) and click **Commit changes**. The site updates in a few minutes.

## Good to know

- Free GitHub Pages needs a public repository, so anyone can read your games' code.
- Each game keeps its saves in the browser, tied to the site address. Give each game its own
  prefix for saved data (Seven Floors Down uses `sfd_` and `pyrogue_`) so games don't overwrite each other.
- Moving to a new address starts saves fresh, because browsers keep saves per site.
- A custom address like `mygames.com` costs money (about $10 to $15 a year). The free
  `github.io` address works fine for sharing with friends.
