# VIDEO 05 — The Tech Stack That Makes Sense

STATUS: ✍️ Nguyên liệu

---

## PHẦN 1 — TIÊU ĐỀ + CAPTION

**Tiêu đề:** "The Optimal Tech Stack for Claude-Powered Products (Stop Overthinking)"

**Video Description with Timestamps:**

Stop wasting time choosing between 10 different technologies. Here's the boring, proven tech stack that Claude understands perfectly and that scales from zero to 1 million users with zero server management. Learn why this stack is 3x faster to build on.

⏱️ **Key Topics:**
- ✅ Frontend: Next.js + Tailwind CSS (why this beats Vue, Remix, etc.)
- ✅ Backend: Next.js API Routes (no separate backend needed)
- ✅ Database: Supabase PostgreSQL (proven, free tier, real-time)
- ✅ Auth: Supabase Auth (handles login, OAuth, 2FA built-in)
- ✅ Payment: Stripe (PCI compliant, works globally)
- ✅ Deployment: Vercel (auto-deploy, serverless scaling, free)
- ✅ Email: Resend (developer-friendly transactional emails)
- ✅ Cost Progression: $0 → $350/month as you scale

**Tags:** tech stack, Next.js, SaaS development, Claude Code, no-code alternative, full-stack development, Vercel deployment, Supabase tutorial, startup stack, web development

---

## PHẦN 2 — VOICEOVER SCRIPT

**HOOK (0:00–0:30)**

"I watched a developer waste 8 weeks choosing between different database technologies, frameworks, and deployment platforms. Meanwhile, another developer shipped the exact same product in 3 weeks using a boring tech stack. Here's the tech stack that actually works for making money fast."

---

**SECTION 1: THE PRINCIPLE & FRONTEND (0:30–2:15)**

Let me give you the uncomfortable truth: Your tech stack doesn't determine your success. Your execution does.

But that said, some tech stacks make it 3x easier to build and launch. I'm going to give you the exact stack that does this, specifically optimized for Claude-powered products.

The principle is simple: Minimize decisions. The more decisions you make, the slower you ship. Your goal is to make zero technology decisions and focus 100% on product decisions.

This is the stack that achieves that.

For the frontend, use Next.js plus Tailwind CSS.

Why Next.js? Built for production. 30% of the web uses it. Claude understands it perfectly—trained on massive amounts of Next.js code. It's full-stack, so you can do frontend AND backend. Auto-deployment to Vercel—literally one click. File-based routing means less config. Image optimization built in. SEO friendly with server-side rendering.

Why Tailwind? No CSS to write, which reduces decisions. Claude generates Tailwind perfectly—it's the most popular CSS framework. Responsive by default. Fast development because styling lives in the component, no separate files.

Cost: Zero dollars for development. $20 to $100 per month on Vercel once you launch.

For the backend, use Next.js API Routes. Don't use a separate backend.

Why not a separate backend? You're one person. Separate backend equals double the deployment, double the debugging. Next.js API routes are production-ready. Claude can generate full API endpoints instantly.

You literally do this: Create `/pages/api/users.js`. Claude generates the handler. Deploy. Auto-deployed by Vercel. Done. You don't run servers, don't manage Docker, don't configure reverse proxies.

Cost: Included with Next.js.

---

**SECTION 2: DATABASE, AUTH, PAYMENT (2:15–4:45)**

For the database, use Supabase PostgreSQL.

Why PostgreSQL via Supabase? Most stable database technology—25 years, proven. Supabase has excellent free tier: 1GB storage, up to 50K requests per month. Built-in authentication handles login for you. Real-time subscriptions if you need live updates. Claude understands SQL perfectly.

Why not MongoDB? Wrong data structure for business apps. Harder to query complex data. Higher costs at scale.

Why not Firebase? Vendor lock-in. Expensive at scale. Less control.

You connect Next.js to Supabase with a simple library. Claude handles all schema design and queries.

Cost: Zero to $25 per month depending on usage.

For authentication, use Supabase Auth. Don't build auth yourself.

Supabase Auth handles: Password reset emails, email verification, OAuth—Google, GitHub, Discord login—session management, two-factor authentication.

One line of code in your Next.js app. Claude assists all integration.

Cost: Included with Supabase.

For payment, use Stripe.

Why Stripe? Works globally. Handles currency conversion. PCI compliant—you don't touch credit cards. Webhooks for subscription management. Test mode for development.

Alternatives exist: Lemonsqueezy or Gumroad if you want less infrastructure. But Stripe is industry standard and worth learning.

Cost: 2.9% plus $0.30 per transaction. You pay nothing until you get revenue.

---

**SECTION 3: DEPLOYMENT, EMAIL, & COST PROGRESSION (4:45–7:00)**

For deployment, use Vercel.

Why Vercel? Built by the Next.js creators. Auto-deploys on git push. Serverless—scales automatically. Free tier until you need it. Analytics built in. Edge functions at no additional cost. Environment variables handled automatically.

You literally do: git push. Auto-deployed in 60 seconds. No servers to manage.

Cost: Zero to $20 per month.

For transactional emails like password reset and welcome emails, use Resend.

Why Resend? Built for developers with API-first approach. Free tier: 100 emails per day. Claude can generate email templates. Integrates with Next.js in 5 minutes.

Alternatives: SendGrid, Mailgun—both fine.

Cost: Zero for first 100 per day, $0.20 per email after.

Now, the complete stack:

Frontend: Next.js plus Tailwind equals zero dollars.

Backend: Next.js API Routes equals zero dollars.

Database: Supabase equals zero to $25 per month.

Auth: Supabase equals included.

Payment: Stripe equals 2.9% plus $0.30.

Deployment: Vercel equals zero to $20 per month.

Email: Resend equals zero to $20 per month.

Monitoring: Vercel analytics plus basic logging equals included.

Total monthly cost: Zero dollars until you get revenue.

Total setup time: 2 to 3 hours.

---

**SECTION 4: WHAT NOT TO USE & THE CLAUDE WORKFLOW (7:00–8:45)**

What not to use:

Rails—too opinionated, not optimized for solo builders.

Django—overkill for SaaS.

Vue—less popular, fewer Claude training examples.

Remix—unnecessary complexity over Next.js.

Custom Node.js server—requires infrastructure knowledge.

These are all fine technologies, but they add decisions and complexity. Avoid them.

Here's the workflow with Claude:

Day 1: Tell Claude, "I want to build a tool that takes emails and summarizes them." Claude generates a complete Next.js project structure. You run npm install and npm run dev. You see a working app with basic UI.

Day 2-3: Describe the feature: "Users can upload PDF, app uses Claude API to extract key points." Claude generates the API route, database schema, frontend component. You integrate, connect the pieces, test locally, push to git. Auto-deploys to Vercel.

Day 4-7: Add payment by asking Claude to integrate Stripe. Add auth—Supabase integration takes one line. Add email with Resend integration for payment confirmation. Deploy—git push.

By day 7 to 10, you have a production SaaS with authentication, payment processing, database, API, frontend, automatic scaling. All from one boring, proven stack.

---

**SECTION 5: COST PROGRESSION & THE PERFECT SETUP TRAP (8:45–9:45)**

Cost progression shows how this scales:

Month 1 development: Zero dollars.

Month 2 launch with zero customers: Zero dollars.

Month 3 with 5 customers: $25 for Supabase plus $0.30 for Stripe fees—about $25 total.

Month 4 with 15 customers: $25 plus $5 for Stripe fees—$30.

Month 6 with 50 customers: $50 for Supabase, $30 for Stripe fees—$80.

Month 12 with 200 customers: $200 plus for Supabase, $150 plus for fees—$350 plus.

By the time you're paying $350 per month in infrastructure, you're making $3K-plus per month. That's a healthy ratio.

Here's the reason developers don't launch: They're obsessed with perfect setup. "Should I use Postgres or MongoDB?" Postgres, doesn't matter after first month. "Should I use Docker?" No, Vercel handles deployment. "Should I use GraphQL or REST?" REST, simpler. "Should I build a mobile app?" No, make web work first.

Answer: Postgres. No. REST. No.

Setup should take 1 to 2 hours maximum. Spend the rest of your time on product.

This stack is perfect for Claude because: Next.js is the most trained-on framework—Claude has seen millions of examples. TypeScript, recommended, is clear for Claude to understand. Supabase SQL is straightforward for Claude to write. Claude can generate production-grade code for all components. Minimal weird configurations that need explanation.

---

**CLOSING (9:45–10:00)**

Go to Vercel and create a new Next.js project. Take 15 minutes. Run it locally. That's it. You now have a fully deployed application that scales to 1 million users for free.

Tell me in the comments: what's the biggest technical thing blocking you from shipping? Subscribe—next video I'm showing you how to overcome it with Claude.

---

## PHẦN 3 — VISUAL DIRECTION

**Scene 1 (0:00–1:15) — The Tech Stack Architecture Overview**
Diagram showing clean layers: Frontend (Next.js + Tailwind) → Backend (Next.js API Routes) → Database (Supabase PostgreSQL). Arrows flowing between layers. Each component labeled with cost ($0). Clean, minimal, professional architecture diagram. Mood: Clear, organized. Color palette: Blues and whites with accent colors for each layer.

**Scene 2 (1:15–3:00) — Frontend & Backend Components Breakdown**
Split screen: Left shows Next.js features (file-based routing, image optimization, SSR). Right shows API Routes with simple endpoint examples. Use simplified code snippets or icons representing each feature. Checkmarks next to Claude-friendly features. Mood: Educational, capability-focused. Color palette: Professional blues.

**Scene 3 (3:00–4:15) — Database, Auth, Payment Stack**
Three connected boxes: Supabase (PostgreSQL, Auth included), Stripe (payment processor), integration arrows between them. Key features listed: user tables, OAuth buttons, payment webhooks. Clean, integrated feel. Mood: Solid, proven. Color palette: Supabase blues, Stripe blues, unified theme.

**Scene 4 (4:15–5:30) — Deployment & Email Services**
Two components: Vercel (showing auto-deployment flow: Code → Git Push → Auto Deploy) and Resend (email template examples). Connected to the overall stack. Zero-cost focus highlighted. Mood: Frictionless, automated. Color palette: Vercel blacks/whites, Resend accent colors.

**Scene 5 (5:30–6:45) — Cost Progression from $0 to $350/month**
Line chart showing months 1-12 on X-axis, monthly costs on Y-axis. Starting at $0, gradually ascending to $350 by month 12. Annotations showing milestones: "5 customers ($25)," "15 customers ($30)," "50 customers ($80)," "200 customers ($350)." Revenue line visible above costs. Mood: Sustainable growth. Color palette: Green for revenue, neutral for costs.

**Scene 6 (6:45–8:00) — Claude Development Workflow**
Three-step animated progression: Day 1 (Claude generates project), Day 2-3 (Build features with Claude), Day 4-7 (Add payments, auth, email). Each step shows Claude assisting, code appearing, Vercel deployment. Final result: production SaaS. Mood: Fast, efficient. Color palette: Claude blues, progression greens.

**Scene 7 (8:00–9:15) — What NOT to Use (Avoidance)**
Four icons crossed out with red X: Rails, Django, Vue, Remix. Each with brief reason (too opinionated, overkill, less popular, unnecessary complexity). Contrasted with green checkmarks for chosen technologies. Clean, simple visual filter. Mood: Clarity, decision-focused. Color palette: Red X's, green checkmarks.

**Scene 8 (9:15–10:00) — Call to Action & Next Steps**
Simple scene showing Vercel dashboard with "Create New Project" button highlighted. Text overlay: "Create a Next.js project. Takes 15 minutes. Scales to 1 million users." YouTube subscribe button animation. Next video preview. Mood: Actionable, inviting. Color palette: Vercel-inspired, call-to-action highlights.

---

## PHẦN 4 — SCENE PROMPTS

**Scene 1 Prompt:**
"2D flat illustration of layered tech stack architecture. Bottom layer: 'Supabase (PostgreSQL) $0-25/mo.' Middle layer: 'Next.js API Routes ($0)' with arrow connections. Top layer: 'Next.js + Tailwind ($0 dev, $20-100 prod).' Each layer connected by clean arrows showing data flow. Add deployment arrow to Vercel. Professional software architecture diagram style. Blues, whites, minimal accents. Aspect ratio 16:9."

**Scene 2 Prompt:**
"2D flat illustration split-screen. Left: Next.js logo with features listed: 'File-based routing, Image optimization, Server-side rendering, Fast deployment.' Right: API Routes with example endpoint (/api/users) shown as simple code block. Both sections have green checkmarks for 'Claude-friendly.' Professional, educational layout. Subtle code syntax highlighting. Aspect ratio 16:9."

**Scene 3 Prompt:**
"2D flat illustration showing three service boxes connected by arrows: Supabase (showing database icon and auth features), Stripe (payment processing), and connection to Next.js backend. Features visible: user tables, OAuth buttons, payment webhooks, API integrations. Professional, interconnected feel. Clean lines, Supabase and Stripe brand colors incorporated. Aspect ratio 16:9."

**Scene 4 Prompt:**
"2D flat illustration showing Vercel deployment workflow (Code → Git Push → Auto Deploy → Live) and Resend email service (template icons). Both services integrated into the full stack. Free-tier highlighting for Vercel and Resend. Professional service integration visualization. Brand colors from both services. Aspect ratio 16:9."

**Scene 5 Prompt:**
"2D line chart animation. X-axis: Months 1-12. Y-axis: Cost $0-400. Starting point Month 1 at $0, gentle upward curve to Month 12 at $350. Revenue line shown above (green) growing to $3K+/month. Key milestones labeled: Month 1 ($0, zero customers), Month 3 ($25, 5 customers), Month 6 ($80, 50 customers), Month 12 ($350, 200 customers). Professional financial chart. Aspect ratio 16:9."

**Scene 6 Prompt:**
"2D animation sequence showing three time phases. Day 1: Claude icon generating Next.js project structure on screen. Day 2-3: Features being added (database schema, API routes, UI components appearing). Day 4-7: Payment, auth, and email integrations added. Final frame: Complete SaaS application displayed on Vercel dashboard. Fast-paced, satisfying progression feeling. Professional, clean aesthetic. Aspect ratio 16:9."

**Scene 7 Prompt:**
"2D flat illustration showing technology comparison. Left side: 'Avoid These' with four technology icons (Rails, Django, Vue, Remix) each marked with large red X. Next to each: brief reason (too opinionated, overkill, less popular, unnecessary complexity). Right side: 'Use This Stack' with checkmarks. Professional rejection/selection visual. Clean, simple decision tree. Aspect ratio 16:9."

**Scene 8 Prompt:**
"2D illustration of Vercel dashboard mockup with 'Create New Project' button prominently displayed. Overlay text: 'Go to Vercel. Create a Next.js Project. Takes 15 minutes. Scales to 1M Users for Free.' YouTube subscribe button animation in corner. Next video thumbnail preview. Call-to-action focused design. Vercel brand colors, friendly, approachable tone. Aspect ratio 16:9."

---

**Status:** ✅ HOÀN THÀNH
