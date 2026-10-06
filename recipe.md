# Recipe: Make a 30-Second Vox-Style AI Video

> This is the exact workflow I used to create my overview video. Edit anything below to match your own experience.

**Result:** one 30-second video, made from three 10-second clips
**Style:** Vox-style paper-cutout collage, halftone archival photos, hand-drawn annotation arrows
**Tools:** Claude (prompt writer), Gemini Veo 3 (video generator), any video editing app (stitching)

---

## What this recipe does

You give Claude a topic. Claude writes three fully styled 10-second prompts. You paste each prompt into Veo 3 to create three clips. You then join the three clips in an editing app to get one polished 30-second video.

```
Topic -> Claude -> 3 prompts -> Veo 3 -> 3 clips (10s each) -> Editing app -> Final 30s video
```

---

## Ingredients

- `prompt.md` (the master prompt)
- A topic for your video
- Access to Claude (or GPT / Gemini) to write the prompts
- Access to Gemini Veo 3 to generate the clips
- A video editing app (CapCut, DaVinci Resolve, Premiere, or similar)

---

## Steps

### Step 1: Give Claude the master prompt
1. Open `prompt.md` and copy the master prompt from Part 2.
2. Paste it into Claude.
3. Claude asks for your **topic** and your **tool**.
4. Answer: topic = your topic, tool = **Gemini Veo 3**, duration = **30 seconds**, split into **3 clips of 10 seconds**.

### Step 2: Get the three prompts from Claude
Claude gives you three separate prompts:
- Clip 1 (0-10s): the hook and the problem
- Clip 2 (10-20s): the explanation
- Clip 3 (20-30s): the payoff and the closing line

Each prompt repeats the full style block so the look stays consistent across clips.

### Step 3: Generate each clip in Veo 3
1. Open Veo 3.
2. Paste Clip 1's prompt and generate. Repeat for Clip 2 and Clip 3.
3. Generate one clip at a time. If a clip drifts from the style, regenerate that clip only.
4. Download all three clips and name them `clip1.mp4`, `clip2.mp4`, `clip3.mp4`.

### Step 4: Combine the clips in an editing app
1. Import the three clips.
2. Place them on the timeline in order: clip 1, clip 2, clip 3.
3. Trim any dead frames at the start or end of each clip.
4. Add a quick paper-rustle or whoosh sound at each join.
5. Add captions and one background music track under the whole video.
6. Export at 1080p.

### Step 5: Publish
Export the final 30-second video and share it. In my case, this video also served as my overview, so people can see my experience and process.

---

## The three prompts (fully styled template)

Replace `[TOPIC]` and the content lines, then paste each into Veo 3. Or let Claude fill them in for you using the master prompt.

### Clip 1 (0-10s): Hook and problem

```
Create a 10-second animated explainer clip, 16:9, about "[TOPIC]".

STYLE: Vox-style paper-cutout collage with layered shapes, rough torn edges, soft drop shadows and slight rotation, pinned to a corkboard. Black-and-white halftone archival photos relevant to the topic, each tinted with one accent color. Hand-drawn marker arrows, circles, underlines and handwritten labels that draw on stroke by stroke, then wobble slightly. Warm cream paper-grain background with faint fold lines. Palette: cream #F5EFE0, ink black #1A1A1A, yellow #FFD100 (emphasis only), coral #FF4B3E, teal #2B8A8A. Bold condensed sans-serif headlines, typewriter font for data, handwritten font for annotations.

TIMELINE:
0-4s: [HOOK: a surprising question or contrast about the topic]. On-screen text: "[max 12 words]". Halftone photo slides in behind.
4-10s: [PROBLEM: what goes wrong without this]. Hand-drawn arrow points to the problem with the handwritten note "[annotation]".

MOTION: Stop-motion feel at about 12 fps, cutouts popping and sliding in, slow push-in on the halftone photo, arrows drawing themselves.
AUDIO: Friendly voiceover saying "[voiceover line, about 25 words]". Light paper-rustle transition at the end, soft pen-scratch on arrow draws, subtle lo-fi music.
```

### Clip 2 (10-20s): Explanation

```
Create a 10-second animated explainer clip, 16:9, continuing a video about "[TOPIC]".

STYLE: Vox-style paper-cutout collage with layered shapes, rough torn edges, soft drop shadows and slight rotation, pinned to a corkboard. Black-and-white halftone archival photos relevant to the topic, each tinted with one accent color. Hand-drawn marker arrows, circles, underlines and handwritten labels that draw on stroke by stroke, then wobble slightly. Warm cream paper-grain background with faint fold lines. Palette: cream #F5EFE0, ink black #1A1A1A, yellow #FFD100 (emphasis only), coral #FF4B3E, teal #2B8A8A. Bold condensed sans-serif headlines, typewriter font for data, handwritten font for annotations.

TIMELINE:
0-3s: [EXPLAIN STEP 1]. Cutout appears with the label "[label]".
3-7s: [EXPLAIN STEP 2]. Arrows connect the cutouts, with the handwritten note "[annotation]".
7-10s: [EXPLAIN STEP 3]. A sticky-note cutout drops in with the text "[max 12 words]".

MOTION: Stop-motion feel at about 12 fps, cutouts popping and sliding in, arrows drawing themselves and wobbling.
AUDIO: Friendly voiceover saying "[voiceover line, about 25 words]". Paper-rustle transition at the end, soft pen-scratch on arrow draws, subtle lo-fi music.
```

### Clip 3 (20-30s): Payoff and close

```
Create a 10-second animated explainer clip, 16:9, finishing a video about "[TOPIC]".

STYLE: Vox-style paper-cutout collage with layered shapes, rough torn edges, soft drop shadows and slight rotation, pinned to a corkboard. Black-and-white halftone archival photos relevant to the topic, each tinted with one accent color. Hand-drawn marker arrows, circles, underlines and handwritten labels that draw on stroke by stroke, then wobble slightly. Warm cream paper-grain background with faint fold lines. Palette: cream #F5EFE0, ink black #1A1A1A, yellow #FFD100 (emphasis only), coral #FF4B3E, teal #2B8A8A. Bold condensed sans-serif headlines, typewriter font for data, handwritten font for annotations.

TIMELINE:
0-5s: [PAYOFF: why this matters]. Three sticky notes drop in one by one with hand-drawn checkmarks: "[benefit 1]", "[benefit 2]", "[benefit 3]".
5-8s: Before/after split screen: a messy scribbled scene vs. a clean organized scene. Handwritten note: "[annotation]".
8-10s: Closing line stamps on screen: "[memorable closing line]". Hold the final frame.

MOTION: Stop-motion feel at about 12 fps, notes popping with a slight bounce, checkmarks drawing themselves, slow push-in on the final frame.
AUDIO: Friendly voiceover saying "[voiceover line, about 25 words]". Soft closing chime, subtle lo-fi music fading out.
```

---

## If you use a different tool

### Muse AI
Paste the master prompt from `prompt.md`, choose **Muse AI** when Claude asks, and you get one single timed prompt instead of three. Paste it once and generate the full video in one go. No stitching needed.

### Claude Opus only
Choose **Claude Opus** when asked. You get a storyboard and script (scene table, voiceover, asset list) rather than clips. Use it as a plan if you are building the video manually.

---

## Tips from my experience

- Keep the style block identical in all three prompts. This is what makes the three clips feel like one video.
- If one clip looks off, regenerate only that clip. Do not redo all three.
- Keep on-screen text short (12 words max). Veo can garble long text, so add final captions in the editing app instead.
- Check the clip length your Veo plan allows. If it caps at 8 seconds, either make four shorter clips or trim your timeline to fit.
- Match the end of each clip to the start of the next: end clip 1 on a settled frame, start clip 2 with a fresh slide-in.

---

## My notes (edit this section)

- Topic I used: [your topic]
- Date made: [date]
- What worked well: [your notes]
- What I would change next time: [your notes]
