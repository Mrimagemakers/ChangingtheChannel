# Changing the Channel

WebXR 3D flipbook and EQ companion for *Changing the Channel: The 10 Golden Rules of Emotional Intelligence* by Darnell E. Clark (PenGame Publishing).

Live site: https://mrimagemakers.github.io/ChangingtheChannel/

## Narration

Audiobook narration by Lamont Hightower lives in `audio/narration/`, one MP3 per book spread (`00-book-intro.mp3` … `14-outro.mp3`). To swap a recording, replace the file with the same name. The spread-to-file mapping is the `NARRATION_TRACKS` list in `index.html`.

## Environments

Four switchable worlds (top bar, or the globe button on smaller screens; "New World" in VR): **Sanctuary** (temple with a pillar for each Golden Rule), **Calm Horizon** (ocean sunset deck), **EQ Studio** (neon broadcast stage that reacts to the music), and **Aurora Night** (frozen lake under the northern lights). Link straight to one with `?env=sanctuary|horizon|studio|aurora`. The glow effect turns itself off on slower devices; add `?hq=1` to force it on.
