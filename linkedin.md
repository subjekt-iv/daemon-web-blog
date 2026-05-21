# LinkedIn post

> **Lead visual**: corridor video (attach as native LinkedIn video upload)

---

I run a rave. I also write software. So I built the whole thing myself.

There's a version of this post where I tell you I built a full event platform with AI in one afternoon. That's not this post.

I'm a software developer. I used AI throughout — to go faster, and to work in areas where my experience was thinner. The decisions, the architecture, the debugging at midnight before the event: that was mine.

337 tickets sold. The night ran without a single incident.

For DÆMON — an underground electronic music event in Buenos Aires — I built four things:

→ A GLSL fragment shader background on the landing page (4D Perlin noise, audio-reactive, built from scratch)
→ A Three.js corridor where visitors navigate the lineup — artist press photos on the walls, built on spite/cruciform
→ A ticketing system: MercadoPago checkout with fee grossing, bank transfer reconciliation via COELSA IDs, Claude Vision OCR for receipt validation
→ A door scanner with PostgreSQL row-locking to prevent race conditions on 4-pack tickets at 2am

One repo. One Vercel deployment.

The thing that made it possible as a solo developer wasn't the AI. It was being structured before touching code — specs, design decisions, task lists — and then using AI to execute faster within that structure. It let me work outside my comfort zone (3D, Argentine payment rails) without getting lost.

I'd sold tickets before. Through platforms that hold your money for weeks and charge your audience a service fee. Building it myself meant direct settlement, no commission layer, full data ownership.

337 people walked in. Nothing broke.

Full writeup with technical details, code snippets, and videos: [link]

---

> **Hashtags** (add at end of post):
> #softwaredevelopment #webgl #threejs #eventproduction #buildinpublic #solodev #argentina
