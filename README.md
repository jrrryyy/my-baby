# Only For You

A complete React + Vite surprise website with Tailwind CSS, Framer Motion and Lucide icons.

## Run locally

```sh
npm install
npm run dev
```

Build for static hosting with `npm run build`. Upload the contents of `dist` to your static host.

## Personalize

Edit `src/data.js` for the secret code, all captions, timeline dates, messages, letter and media paths. The initial code is `050306`. Timeline dates are explicitly editable placeholders, not invented dates.

Place your pictures in `public/media`, then update the paths in `src/data.js`, for example `/media/our-first-photo.jpg`. Replace the hero and favorite paths too. The supplied SVG images are original landscape illustrations, not photographs of another couple. Use portrait photos for the hero and landscape photos for the timeline. Gallery photos crop to fit; change `object-position` in the CSS if needed.

The included `public/media/our-song.wav` is a short original instrumental demo. Replace it with your own licensed or permitted music file. For MP3, change the music path to `/media/our-song.mp3`. Music starts only when the visitor presses play; volume and pause are available throughout the unlocked site.

## Interactions

The six password fields support typing, backspace, arrow keys, pasting a complete code and Enter. Unlock persists in the current browser tab's session. Clear session storage or use a fresh tab to view the welcome again. The gallery supports keyboard arrows, Escape, mobile swipe and focus restoration. The letter opens and folds, reasons rotate, the gift reveals the final message, and the hug creates a temporary heart animation.

## Privacy and sharing

The code is a client-side presentation gate, not authentication. Anyone with access to the files can inspect it and open the media directly. Do not upload private photos without real server-side authentication and protected media delivery. Sites publication initially uses owner-only access; that link must have suitable sharing configured before your girlfriend can visit. You can also deploy the build on your preferred static host.
