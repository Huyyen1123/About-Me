# Huy Nguyen — Portfolio

My personal portfolio, built to look and feel like the Minecraft title screen.

**Live:** [huyhoannguyen.com](https://huyhoannguyen.com)

## Features

- **3D panorama background** — a Three.js cubemap skybox that slowly rotates, just like the real title screen, with a looping video of my own Minecraft world as a fallback.
- **3D player model** — my Minecraft skin rendered on a real player model in the corner; the head follows your mouse. Skins, the nametag, and the yellow splash text rotate on every load and every minute.
- **Menu windows** — About Me (photo carousel, education, skills, resume), Experience (flip cards), and Projects.
- **Settings** — Music, Sound FX, and Reduce Motion toggles, saved in localStorage. Reduce Motion also respects the OS setting.
- **UI sounds** — hover/click sounds synthesized with the Web Audio API, no audio files.
- **Achievements** — Minecraft-style toast pop-ups.
- **Responsive** — works on phones with touch-friendly hints.

## Tech

Plain HTML, CSS, and JavaScript — no framework or build step. [Three.js](https://threejs.org) for the panorama and player model. Hosted on GitHub Pages.

## Structure

```
index.html            page markup
css/style.css         all styles
js/main.js            menus, settings, rotations, sounds, achievements
js/panorama.js        rotating cubemap background
js/player.js          3D player model
js/vendor/            three.min.js
assets/               images, video, fonts, resume
```

## Run locally

```bash
git clone https://github.com/Huyyen1123/portfolio.git
cd portfolio
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Credits

- **Panorama:** [Cherry Blossom Panorama](https://modrinth.com/resourcepack/cherry-blossom-panorama) by BlueHDGaming
- **Font:** [Minecraft Font](https://github.com/IdreesInc/Minecraft-Font) by Idrees Hassan (SIL Open Font License 1.1)
- **3D:** [Three.js](https://threejs.org) (MIT)

Not affiliated with Mojang or Microsoft. Minecraft is a trademark of Mojang Studios.

## Contact

- [LinkedIn](https://www.linkedin.com/in/huy-nguyen-682b87431/)
- [GitHub](https://github.com/Huyyen1123)

© 2026 Huy Nguyen
