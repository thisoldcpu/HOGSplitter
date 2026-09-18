# HOGSplitter: The Descent Archive Extractor

<img width="1280" height="1392" alt="screenshot_9_18_26" src="https://github.com/user-attachments/assets/7d3b94f8-ef49-4bc1-80aa-71699205f238" />

HOGSplitter is a lean, purpose-built utility designed to crack open the `.HOG` archive files powering Parallax Software’s classic 6DOF shooters, *Descent* and *Descent II*. Whether you are a veteran Material Defender preserving original assets or a modern modder constructing custom mines, HOGSplitter gives you immediate, unhindered access to the raw materials of the PTMC.

Because `.HOG` files serve as the primary bulk containers for the game's data, cracking them open is ground zero for any serious modding project. HOGSplitter slices through these archives cleanly, translating packed binary into accessible textures, sound banks, 3D models (`.POF`), and level geometry.

### Core Features

* **Whole-Hog Extraction:** Instantly unpack every embedded asset from any standard *Descent* archive directly into an organized local directory.
* **Surgical Precision:** Parse the archive manifest to hunt down and extract specific files on demand, no full dump required.
* **Lightweight & Fast:** Built for speed with a minimal footprint, processing classic asset libraries in a matter of seconds.

> *Get in, grab the payload, and get out before the reactor blows.*

---

### Supported File Status

**Fully Supported**
* ✅ **BIN** - `BITMAPS.BIN` texture browser
* ✅ **TXB** - Decoded text viewing
* ✅ **BBM** - Bitmap image preview
* ✅ **PCX** - PCX image preview
* ✅ **256** - Palette visualization

**In Development / Planned**
* ❌ **RAW** - WAV-wrapped audio playback *(Plumbing basically done)*
* ❌ **SNG** - Structured/text preview *(Rather than generic text)*
* ❌ **FNT** - Render a glyph-sheet/font preview
* ❌ **HMP / HMQ** - Music metadata parsing *(Followed by playback, if the sequence can be cleanly converted for TMediaPlayer)*
* ❌ **BNK** - Bank header and instrument listing
* ❌ **DIG** - Structured inspection of actual fields *(Rather than a raw hex dump)*
* ❌ **POF** - Header, submodel, material, and geometry statistics. *(A wireframe viewer would be glorious, but this is prime territory for feature creep)*
* ❌ **RDL** - Level metadata, including segment, vertex, object, and wall counts, plus textures used.
