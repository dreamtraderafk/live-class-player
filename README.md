# Live Class Player

Watch any YouTube lecture inside a Zoom-style live class screen, with **no pause, seek or speed controls**. Built for people who study better when a video plays like a live class.

**Live app:** https://dreamtraderafk.github.io/live-class-player/

Single file, no build step, no dependencies.

## Features

- Paste a YouTube video or playlist link and join
- No play, pause, forward or backward controls
- Auto-resumes if the video ever pauses
- Live-class look: host tile, participants, recording dot, class timer
- Timestamped notes while you watch (saved in your browser)
- Rejoin the same link and resume where you left
- Top and bottom bars auto-hide for a bigger view (tap the screen to bring them back)
- Fullscreen button (locks to landscape on supported phones)
- Settings on the home page: your name, host name, and the number and names of participants
- Dark and light themes, works on phone and desktop

## Use it

1. Open https://dreamtraderafk.github.io/live-class-player/
2. Paste a YouTube link
3. Tap **Join class**

On phone, use **Add to Home screen** for one-tap access.

## Run your own copy

1. Fork this repo
2. Go to **Settings → Pages**
3. Choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**
4. Your copy will be at `https://<your-username>.github.io/live-class-player/`

Any HTTPS host works too (Netlify, Cloudflare Pages).

## Important

- It must be opened from a web address (`https://`). Opened as a local file, YouTube refuses to play the video.
- Videos whose owners disabled embedding won't play.
- YouTube ads can still appear.
- This is a focus tool, not a lock. Nothing stops you from opening YouTube elsewhere.

## Customise

Use the **Settings** button on the home page to change your name, the host name, and the number and names of participants. Settings are saved in your browser.

Everything else is in `index.html`.

## Contributing

Issues and pull requests are welcome.

## Disclaimer

Not affiliated with or endorsed by YouTube, Google or Zoom. Videos are played through YouTube's official embedded player.

## License

MIT. See [LICENSE](LICENSE).

Made by [@dreamtraderafk](https://github.com/dreamtraderafk)
