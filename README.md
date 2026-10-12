# Case studies

Products I've built where the code lives in private repos. Each write-up covers what it is, what I made, and the stack. Live links are included where one exists.

## AIATWORK homepage: a 3D scroll experience

Live: [theaiatwork.com](https://www.theaiatwork.com)

A from-scratch rebuild of the marketing homepage for an AI workforce platform. Instead of the usual stack of sections, the page is a WebGL scene. As you scroll, the camera moves through a directed story. The look is a glassy blue-black system with a single cobalt accent.

**Stack:** React 19, Vite, TypeScript, React Three Fiber

## AIATWORK Command Center: a CRM you move through in 3D

The internal CRM lives in the same app. Instead of flat tabs, you navigate a 3D tree: a core with eight branches, each opening a set of 2D sub-hubs. The tree is pruned by role (rep, admin, superadmin), so each person only sees the spokes they can use. The hubs read live data from Supabase rather than mock numbers.

**Stack:** React 19, Vite, TypeScript, React Three Fiber, Supabase

## Solar sales dialer: browser-based outbound calling

Live landing page: [aiatworkdialer.vercel.app](https://aiatworkdialer.vercel.app)

A browser-based outbound calling platform that helps solar companies reach homeowners, qualify them, and book account reviews, with optional AI qualification. It runs in a simulated demo mode by default and places real Twilio-backed calls once credentials are set up.

**Stack:** Next.js 15, React 19, TypeScript, Tailwind CSS v4, Framer Motion, Recharts, Twilio Voice SDK, Supabase

---

The code for these is private. If you want to talk through any of them, [open an issue](https://github.com/VASTRIXCODER/case-studies/issues/new) and I'll get back to you.
