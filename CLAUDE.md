Build an interactive "Gensyn Testnet Survivor Stories" timeline website.

TIMELINE DATA (USE EXACTLY THIS - ALL VERIFIED):

=== GENESIS ERA (2020-2021) ===

Nov 2020 - The Founding
- Ben Fielding & Harry Grieve found Gensyn
- Vision: L1 protocol uniting global compute into "supercluster" for ML
- Initial funding (undisclosed)
Community vibe: "We're building the future of decentralized AI"

2021 - Stealth Mode
- Quiet research phase, no public announcements
- Internal POC for decentralized ML verification
Community vibe: "Trust the process, we're cooking"

=== BUILD ERA (2022-2023) ===

Mar 21, 2022 - Seed Round 
- $6.5M led by Eden Block
- Galaxy Digital, Maven 11, CoinFund, Hypersphere, Zee Prime join
- X and Discord community starts
Community vibe: "We're so early! DePIN narrative incoming"

June 11, 2023 - A16Z SERIES A
- $43M led by a16z Crypto (Total: $50.6M+)
- Published foundational research: Verde, NoLoCo, SkipPipe
- Announcement video planned
Community vibe: "A16Z just gave us $43M, WE'RE GONNA MAKE IT"

2023 Late - Growing Anticipation
- Conference participation with Protocol Labs
- X followers growing, Discord AMAs
Community vibe: "Wen testnet? Soon™"

=== REFINEMENT YEAR (2024) ===

2024 - The Long Build
- CheckFree paper published
- Internal Ethereum Rollup testing
- X followers hit ~50K
- Still no public testnet
Community vibe: "Wen testnet? (asked 1000x)" "Are we still early or are we rugged?"

=== TESTNET EXPLOSION (2025) ===

Mar 31, 2025 - TESTNET FINALLY DROPS
- Phase 0 launches on custom Ethereum Rollup
- RL Swarm for collaborative post-training
- Announcement video: 800K+ views
- Airdrop hints
Community vibe: "WE'RE SO BACK! After 2 years, it's finally here!"

Apr 30, 2025 - First Upgrade
- Harder datasets, models up to 72B parameters
Community vibe: "My GPU is sweating"

June 25, 2025 - GenRL Backend
- Complete redesign, Docker support
- Reasoning Gym (100+ environments)
Community vibe: "Finally, easier deployment"

July 8, 2025 - Research Drop
- 5 papers highlighted: Verde, CheckFree, NoLoCo, SkipPipe, Diverse Expert Ensembles
Community vibe: "The nerds are eating good today"

July 17, 2025 - Congestion Fixed
- Network issues resolved
Community vibe: "Smooth sailing now"

July 23, 2025 - 9,809 Nodes Milestone
- RL Swarm growing strong
Community vibe: "We're scaling!"

July 25, 2025 - Swarm Role Opens
- Rewards program launches
Community vibe: "Time to farm"

Aug 6, 2025 - BlockAssist Drops
- AI assistant learns from Minecraft gameplay
Community vibe: "Wait, I can train AI by playing Minecraft?!"

Aug 23, 2025 - HUGE MILESTONE
- 40.5M+ transactions
- 128,293 users
- 21,000 RL Swarm nodes
- 27,835 BlockAssist models
Community vibe: "These numbers are INSANE for a testnet"

Aug 27, 2025 - Judge Framework
- Verifiable AI evaluations via Verde
Community vibe: "Trustless evaluation is the future"

Sept 9, 2025 - BlockAssist v0.1.0
- UI improvements
Community vibe: "Quality of life updates hitting different"

Sept 11, 2025 - SAPO Paper
- Swarm Sampling Policy Optimization
Community vibe: "More research alpha"

Sept 19, 2025 - Round 3 Teased
Community vibe: "What's cooking?"

Oct 7, 2025 - 500K MODELS TRAINED
- Across all applications
Community vibe: "Half a million models, let's gooo"

Oct 15, 2025 - Official Blog Launch
Community vibe: "Medium to Gensyn blog migration"

Oct 23, 2025 - Docs Restructured
- Multi-page format
Community vibe: "Finally, readable docs"

Oct 27, 2025 - BlockAssist Skins
- New in-game visuals
Community vibe: "Drip update"

Oct 30, 2025 - TEE Analysis
- Shifted to verification over trusted hardware
Community vibe: "Tech deep dive szn"

Nov 5, 2025 - CodeAssist Launch
- RL app learning from your coding
- LeetCode integration
Community vibe: "Teaching AI to code by coding myself, meta"

Nov 7, 2025 - CodeAssist Research
- Three-phase roadmap published
Community vibe: "The roadmap looks fire"

Nov 12, 2025 - CodeZero Launch
- Collaborative code generation
- Roles: Proposer, Solver, Evaluator
Community vibe: "Multi-agent coding swarm is wild"

Nov 14, 2025 - 1 MILLION MODELS
- Community-driven milestone
Community vibe: "FROM 0 TO 1 MILLION IN 8 MONTHS 🚀🚀🚀"

Nov 17, 2025 - Weekly Summary (TODAY)
- CodeZero highlights
- "Hail to the Thief" paper on dRL robustness
Community vibe: "Just another day shipping"

Nov 19, 2025 - Devcon Buenos Aires Party
Community vibe: "IRL meetup vibes"

=== SPECIAL CALLOUTS ===

Pioneer Program (Ongoing)
- Roles: Rover, Navigator
- Community engagement
Community vibe: "Early contributors eating good"

November AMA
- 985 attendees
Community vibe: "Community is STRONG"

===================================

DESIGN REQUIREMENTS:

STYLE:
- Dark theme with deep purples/blues and neon cyan/magenta accents
- Glassmorphism effects on cards
- Smooth scroll-triggered animations (fade in + slide up)
- Vertical timeline with glowing connecting line
- Modern crypto/AI aesthetic
- Fully responsive (mobile + desktop)

TIMELINE STRUCTURE:
- Each era gets a section header with gradient background
- Milestones as cards along the vertical timeline
- Each card shows:
  * Date (prominent)
  * Title/Event name
  * Details (bullet points)
  * "Community vibe" quote in italics with different styling
  * Icon representing the milestone type (rocket for launches, money bag for funding, chart for stats, etc)

INTERACTIVE FEATURES:
1. Cards fade in as you scroll to them (Intersection Observer)
2. Click card to expand for "Add Your Story" section
3. Each expanded card has:
   - "Share Your Memory" button
   - Modal form with:
     * Name (optional, default "Anon")
     * Your story/memory (textarea, 500 char max)
     * Submit button
4. User stories display beneath milestone as smaller cards with:
   - Username
   - Their story
   - Timestamp
   - Small upvote button (count only, no backend)
5. Stories stored in localStorage
6. Top of page shows stats:
   - "X Testnet Survivors"
   - "Y Stories Shared"
   - "Z Days Since Testnet Launch"

ANIMATIONS:
- Fade in + slide up for milestone cards (stagger delay)
- Pulse effect on "Share Memory" buttons
- Smooth expand/collapse for cards
- Parallax effect on timeline line (slower scroll)
- Glow effects on milestone icons on hover
- Floating particles in background (subtle, don't overdo)

SPECIAL ELEMENTS:
- Each era section gets unique gradient background
- Timeline line glows with gradient colors
- Milestone icons change based on type:
  * 💰 for funding
  * 🚀 for launches
  * 📊 for metrics/stats
  * 📚 for research papers
  * 🎮 for app releases
  * 🎉 for community events
- "Wen testnet?" should appear as an Easter egg somewhere (maybe if you click the 2024 section 3 times)
- Add a "Scroll to top" button that appears after scrolling down

STATS COUNTER AT TOP:
Display these key numbers prominently:
- Total Funding: $50.6M+
- Current Users: 128,293+
- Total Models Trained: 1,000,000+
- Active Nodes: 21,000+
- Days Since Testnet: [calculate from Mar 31, 2025]

TECH STACK:
- Single HTML file with embedded CSS and vanilla JavaScript
- Use Intersection Observer API for scroll animations
- localStorage for story persistence
- NO frameworks - keep it lightweight
- Use CSS Grid for layout
- Web fonts: something modern like Inter or Space Grotesk

IMPORTANT:
- Include ALL milestones from the timeline above
- Keep "Community vibe" quotes EXACTLY as written
- Make it look professional but fun (this is crypto Twitter content)
- Ensure fast load times
- Add meta tags for Twitter card preview

Make it BEAUTIFUL and shareable on crypto Twitter. This is going viral.
