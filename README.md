# Zoomer — Outside the Feed

A responsive 2D character website with a continuous skateboard loop, animated scroll scenes and four original mood illustrations.

## Preview locally

No build step or dependency installation is required.

    python -m http.server 5173 --directory dist

Open http://127.0.0.1:5173.

## Deploy to Vercel

The included vercel.json configures the static dist directory. Import this repository in Vercel with Framework Preset Other, or run:

    npx vercel --prod

## Assets and behavior

Artwork and motion provenance is recorded in ASSETS.json. Fonts are self-hosted. Decorative videos are muted, play only when relevant and retain static image fallbacks for reduced-motion, data-saving and playback failures.

The current version includes four original mood illustrations, the continuous skateboarding loop and the complete-character closing composition. Removed decorative captions and controls remain absent.

## 2K media delivery

The hero uses a new whole-body skateboarding performance generated in Higgsfield with MiniMax H3 at native 2560×1440. The supporting knee bends, hips dip and rise, torso/head balance, free arm swings and rear foot pushes and recovers together. A matched forward cycle is retimed to 1.5 seconds and interpolated as complete 2K frames to 60 fps with RIFE. The native generation was 24 fps with paired near-held frames; it was not natively 60 fps.

The whole generated rider, cup and skateboard are segmented into the moving skatepark. No body parts are frozen or manually retargeted. One seamless 10.5-second video contains seven body cycles and a full moving-world period, with anchored sky and faster foreground pavement. The matching poster is its first frame. Detailed generation, resampling and review evidence is in ASSETS.json.

Square illustrations and story videos are delivered at 2048×2048. Story videos use 60 fps. Only active media plays, with reduced-motion and data-saving static fallbacks.
