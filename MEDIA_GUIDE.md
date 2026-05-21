# Media Guide

## Videos — upload to GitHub via drag-and-drop in a repo issue/PR, then copy the asset URL

After uploading, replace the placeholder IDs in README.md:

| Placeholder | File to record | Where in README |
|---|---|---|
| `CORRIDOR_VIDEO_ID` | Navigate corridor with W/ArrowUp, show 2+ artist panels, 15–20s | After "how it grew" section |
| `DIRECTOR_MODE_VIDEO_ID` | Open `/landing/daemon/index.html?director=true`, trigger export, show frame progress | After FFmpeg snippet |
| `GLSL_BACKGROUND_VIDEO_ID` | Homepage with audio playing, hover to show shader distortion, ~10s | After "homepage background" intro |
| `SCANNER_VIDEO_ID` | Scan a QR, show approval overlay with entry count ("1 de 2 entradas") | After `FOR UPDATE` snippet |

**How to upload videos to GitHub:**
1. Create a new issue in the blog repo (or open an existing one)
2. Drag the `.mp4` file into the comment box
3. Wait for upload — GitHub generates a URL like `https://github.com/user-attachments/assets/xxxxxxxx`
4. Copy that URL and replace the placeholder in README.md
5. Close the issue without submitting (the asset URL is permanent regardless)

## Screenshots — save to `images/` folder

| Filename | What to capture |
|---|---|
| `images/mp-checkout.png` | MercadoPago checkout redirect page — the payment screen the buyer sees |
| `images/admin-orders.png` | Admin dashboard orders table — status badges, entry counts visible |
| `images/ticket-email.png` | Ticket confirmation email — the generated PNG ticket with QR code |

## LinkedIn

- Upload the corridor video as a **native LinkedIn video** (not a link) — native video autoplay gets significantly more reach
- The `linkedin.md` post is ready — replace `[link]` at the bottom with the GitHub repo URL or Medium URL
- Post the LinkedIn version first, then the Medium version (LinkedIn algorithm favors native content)
