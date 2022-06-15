---
layout: page
---

# Adding yourself to the roster

To add yourself to theroster,

1. Visit the <a target="_blank" href="https://github.com/MathBlocks/manim.dev/tree/main/_devs">GitHub repo</a> of this website.

2. Create a markdown file with your username.

   E.g. if your username is
   `manimchad`, create a file called `manimchad.md` in
   the `_devs` directory.
3. Copy the empty template below and fill in your details accordingly:


```markdown
---
layout: dev
name:
profile_pic_url:
youtube_portfolio_id:
background:
github:
website:
availability:
discord_handle:
discord_id:
timezone:
---
```

Feel free to take hints from other users' files under [`_devs`](https://github.com/MathBlocks/manim.dev/tree/main/_devs).

#### `name`

Your display name. Use the name that people recognize you online—it could be your name + surname, or your online alias.

#### `profile_pic_url`

A URL to your profile picture. Make sure that it is hosted on a server that will remain available. E.g. you could get the URL of your GitHub-hosted profile picture visiting your GitHub profile, right clicking your profile picture, clicking "Open Image in New Tab" and then copying the URL from the address bar.

```
profile_pic_url: https://avatars.githubusercontent.com/u/...
```

#### `github`

Your GitHub username (must be the same account that creates the pull request).

#### `youtube_portfolio` (optional)

The ID of your portfolio video on YouTube.

The part in the video URL that follows after https://www.youtube.com/watch?v=)

E.g. if your video URL is `https://www.youtube.com/watch?v=cZr4-SZ17dE`, you should add

```
youtube_portfolio: cZr4-SZ17dE
```
#### `availability` (optional)

A string describing your availability for hiring. For example,

- Full time
- Part time
- Fully booked
- ...

Feel free to describe your availability in a concise way.

#### `background` (optional)

A string describing your background field. For example,

- Mathematics
- Mechanical Engineering
- Physics and Computer Science
- ...

Feel free to describe your background in a concise way.

#### `website` (optional)

Your website, without the `https://` at the beginning. For example,

```
website: manimchad.com
```

#### `discord_handle` and `discord_id` (optional)

Your Discord handle and ID.

- Discord handle: is your human-readable username that ends with # and 4 numbers.
- Discord ID: the unique numeric ID that Discord assigns you when you first create an account. To find out yours, visit [this webpage](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-).

Eventually, the entries should look like this:

```
discord_handle: manimchad#1234
discord_id: 123456789012345678
```

#### `timezone` (optional)

The timezone that you generally reside in. For example,

- EST
- CET
- UTC+5
- ...

---

**Finally, create a pull request to the repo that commits your file to the repo.** If you don't know how to do that, you can use [this guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).