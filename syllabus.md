# MERN Full-Stack Developer Syllabus
### From Zero → 5 Years of Experience (Phase-wise & Day-wise)

---

## 0. How to Use This Syllabus

| Item | Details |
|---|---|
| **Stack** | MongoDB, Express.js, React, Node.js (+ TypeScript, Next.js, Docker, AWS) |
| **Part A (Days 1–320)** | Zero → Job-ready (Junior Developer). ~4–6 hrs/day, 6 days/week ≈ 11–12 months |
| **Part B (Years 1–5)** | On-the-job growth: Junior → Mid → Senior (month/quarter-wise) |
| **Daily rhythm** | 1 hr theory → 2–3 hrs hands-on coding → 30 min notes/revision → push to GitHub |
| **Weekly rhythm** | Day 6 of each week = revision + mini-project; Day 7 = rest |
| **Rule #1** | Never just watch. Every day ends with code committed to GitHub |
| **Rule #2** | After every phase, build a project and deploy it |

### Phase Overview

| Phase | Title | Days | Outcome |
|---|---|---|---|
| 0 | Foundations (Web, Terminal, Git) | 1–10 | Comfortable with dev environment |
| 1 | HTML, CSS, Responsive, Tailwind | 11–35 | Build pixel-perfect responsive sites |
| 2 | Core JavaScript | 36–80 | Strong JS + DOM + async |
| 3 | TypeScript & Dev Tooling | 81–95 | Typed code, tooling, HTTP/REST mastery |
| 4 | Node.js & Express | 96–125 | Production-style REST APIs, auth, sockets |
| 5 | Databases (MongoDB, SQL, Redis) | 126–150 | Schema design, aggregation, Mongoose |
| 6 | React (Core → Advanced) | 151–195 | Modern React with state, routing, testing |
| 7 | Full-Stack MERN Integration + Capstones | 196–225 | Two production-grade MERN apps |
| 8 | Next.js | 226–245 | SSR/SSG, server components, SEO |
| 9 | DevOps, Cloud & Security | 246–270 | Docker, CI/CD, AWS, OWASP |
| 10 | DSA, System Design & Interview Prep | 271–310 | Interview-ready |
| 11 | Open Source, Portfolio & Job Hunt | 311–320 | Hired |
| 12 | Year 1 on the job (Junior) | Part B | Ship features independently |
| 13 | Year 2–3 (Mid-level) | Part B | Own modules, design systems & services |
| 14 | Year 4–5 (Senior) | Part B | Architect, lead, mentor |

---

# PART A — ZERO TO JOB-READY

---

## PHASE 0 — Foundations (Days 1–10)

**Goal:** Understand how the web works and set up a professional workflow.

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 1 | How the web works: client-server, HTTP, DNS, browsers, frontend vs backend | Install VS Code, Chrome; trace a request in DevTools Network tab |
| 2 | Terminal basics (cd, ls, mkdir, cp, mv, rm, cat, grep, pipes) | Create a folder structure entirely from the terminal |
| 3 | Git I: init, add, commit, status, log, diff, .gitignore | Version-control a sample project |
| 4 | Git II: branches, merge, merge conflicts, rebase intro | Create and resolve a deliberate conflict |
| 5 | GitHub: remotes, push/pull, SSH keys, Pull Requests, Issues | Push first repo, open and merge a PR |
| 6 | Programming fundamentals: variables, types, conditions, loops, functions (pseudocode & flowcharts) | Draw flowcharts for 5 everyday problems |
| 7 | Problem-solving method: understand → plan → code → test | Solve 10 beginner problems (FizzBuzz, palindrome, etc.) |
| 8 | Dev tools: Node.js via nvm, npm, VS Code extensions, Prettier, ESLint intro | Configure editor with format-on-save |
| 9 | Markdown, reading documentation, debugging mindset, using AI assistants responsibly | Write a good README; practice reading MDN |
| 10 | **Review + Mini-project:** GitHub profile README & portfolio repo | Published profile README |

---

## PHASE 1 — HTML, CSS & Responsive Design (Days 11–35)

**Goal:** Build accessible, responsive, modern UIs.

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 11 | HTML structure: doctype, head, body, headings, paragraphs, text semantics | First web page |
| 12 | Links, images, lists, absolute vs relative paths | Multi-page site with navigation |
| 13 | Tables and Forms I (input types, buttons, select, textarea) | Registration form |
| 14 | Forms II: labels, validation attributes, fieldsets, accessibility | Fully validated form (no JS) |
| 15 | Semantic HTML & accessibility (landmarks, ARIA basics, alt text, tab order) | Audit a page with Lighthouse a11y |
| 16 | Media, iframes, meta tags, SEO basics, Open Graph, favicon | Share-ready page |
| 17 | **Project:** Semantic resume/CV page | Deployed on GitHub Pages |
| 18 | CSS basics: selectors, specificity, cascade, inheritance | Selector challenge (CSS Diner) |
| 19 | Box model, units (px, rem, em, %, vh/vw), display, overflow | Box-model playground |
| 20 | Colors, typography, Google Fonts, backgrounds, gradients, shadows | Style the resume page |
| 21 | Positioning: relative, absolute, fixed, sticky, z-index | Sticky header + badges |
| 22 | Flexbox I: axes, justify, align, wrap, gap | Navbar |
| 23 | Flexbox II: grow/shrink/basis, real layouts | Card layout, centering patterns |
| 24 | CSS Grid I: tracks, areas, gap, fr, repeat, minmax | Photo gallery |
| 25 | CSS Grid II: auto-fit/auto-fill, responsive grids, Grid vs Flex | Dashboard layout |
| 26 | Responsive design: mobile-first, viewport, media queries, breakpoints | Make resume responsive |
| 27 | Responsive images (srcset, picture), clamp(), fluid typography, container queries | Fluid hero section |
| 28 | CSS variables, pseudo-classes/elements, :is/:where/:has, BEM | Theme using variables |
| 29 | Transitions, transforms, keyframe animations | Animated buttons, loaders |
| 30 | **Project:** Responsive landing page (pure CSS) | Deployed on Netlify |
| 31 | Sass/SCSS basics (variables, nesting, mixins) | Convert landing page to SCSS |
| 32 | Tailwind CSS I: utilities, spacing, typography, flex/grid | Rebuild navbar & hero |
| 33 | Tailwind II: responsive, dark mode, custom config, @apply, component extraction | Dark-mode toggle UI |
| 34 | **Project:** Clone a real product page with Tailwind | Pixel-perfect clone |
| 35 | **Phase review:** Lighthouse audit, cross-browser testing, deploy | Score 90+ on all Lighthouse metrics |

---

## PHASE 2 — Core JavaScript (Days 36–80)

**Goal:** Master the language, the DOM, and asynchronous programming.

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 36 | JS intro, console, `let/const/var`, primitive types | 10 variable exercises |
| 37 | Operators, type coercion, truthy/falsy, `==` vs `===` | Quirks quiz |
| 38 | Conditionals: if/else, switch, ternary | Grade calculator |
| 39 | Loops: for, while, do-while, for...of, for...in, break/continue | Pattern printing |
| 40 | Functions: declarations, expressions, arrow, default/rest params | 15 function problems |
| 41 | Scope, hoisting, TDZ, lexical environment | Predict-the-output drills |
| 42 | Closures I & II, IIFE, practical uses (counters, private state) | Build a once() and counter factory |
| 43 | Arrays I: push/pop/slice/splice/find/includes/indexOf | Array CRUD exercises |
| 44 | Arrays II: map/filter/reduce/sort/flat/some/every | Data transformation drills |
| 45 | Objects: literals, this, methods, destructuring, Object.* methods | Inventory manager |
| 46 | Spread/rest, optional chaining, nullish coalescing, template literals | Refactor old code to modern syntax |
| 47 | Strings & Regular Expressions | Email/phone/password validators |
| 48 | Date, Math, JSON, Intl API | Countdown timer logic |
| 49 | **Practice:** 20 problems + CLI-style quiz game | Quiz game |
| 50 | DOM I: selecting, creating, modifying, removing elements | Dynamic list |
| 51 | DOM II: events, bubbling/capturing, event delegation | Delegated todo list |
| 52 | DOM III: forms, validation, classList, dataset, FormData | Form with live validation |
| 53 | **Project:** To-do app (add/edit/delete/filter) | Deployed |
| 54 | **Project:** Calculator + Tic-Tac-Toe | Deployed |
| 55 | Web storage: localStorage, sessionStorage, cookies | Persist to-do app |
| 56 | Prototypes & prototype chain, constructor functions | Draw the chain for 5 objects |
| 57 | Classes, inheritance, getters/setters, static, private fields | Bank-account class hierarchy |
| 58 | `this` in depth: call/apply/bind, arrow vs regular | Fix `this` bugs |
| 59 | Event loop: call stack, task queue, microtasks, timers | Predict-the-output async quiz |
| 60 | Callbacks, callback hell, error-first callbacks | Convert nested callbacks |
| 61 | Promises: then/catch/finally, all/allSettled/race/any | Parallel vs sequential fetch |
| 62 | async/await, try/catch, error handling patterns | Refactor promises to async/await |
| 63 | Fetch API, REST consumption, AbortController, handling HTTP errors | Fetch & render API data |
| 64 | **Project:** Weather/Movie search app | Deployed |
| 65 | ES Modules, import/export, Vite basics | Modularize previous project |
| 66 | Iterators, generators, Symbol, Map/Set/WeakMap/WeakSet | Custom iterable |
| 67 | Functional programming: HOFs, currying, composition, pure functions | Build compose/pipe |
| 68 | Error handling, custom errors, debugging with DevTools & breakpoints | Debug a broken app |
| 69 | Browser APIs: IntersectionObserver, History, Clipboard, Geolocation, Notifications | Lazy-load images |
| 70 | Web Workers, Service Workers, PWA basics | Make an app installable |
| 71 | Immutability, shallow vs deep copy, `structuredClone` | Immutable update helpers |
| 72 | JS design patterns: module, observer, singleton, factory, pub-sub | Mini event bus |
| 73 | Performance: debounce, throttle, memoization, lazy loading | Search box with debounce |
| 74 | Clean code, naming, ESLint, Prettier, Husky, lint-staged | Pre-commit hooks setup |
| 75–79 | **Project (5 days):** Kanban board / Expense tracker (vanilla JS, drag-drop, storage, charts) | Deployed, README with screenshots |
| 80 | **Review:** 50 JS interview questions, output-based questions | Self-assessment |

---

## PHASE 3 — TypeScript & Developer Tooling (Days 81–95)

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 81 | TypeScript intro, setup, basic types, type inference | Compile first TS file |
| 82 | Interfaces vs types, unions, intersections, literal types | Model a domain |
| 83 | Functions & Generics I | Generic utility functions |
| 84 | Generics II, utility types (Partial, Pick, Omit, Record, ReturnType) | Typed API helpers |
| 85 | Narrowing, type guards, discriminated unions, enums, tuples, `unknown` vs `any` | Safe parser |
| 86 | Classes in TS, modifiers, abstract, tsconfig deep dive | Strict-mode config |
| 87 | TS with Node & DOM, `@types`, declaration files, Zod for runtime validation | Typed fetch layer |
| 88 | npm deep dive: package.json, semver, lockfiles, scripts, npx, workspaces, pnpm | Publish a tiny package locally |
| 89 | Bundlers: Vite, Webpack concepts, Babel, tree-shaking, source maps | Analyze bundle size |
| 90 | Git advanced: rebase, cherry-pick, stash, reflog, bisect, conventional commits, trunk vs GitFlow | Rewrite history safely |
| 91 | Linux for devs: processes, ports, curl, env vars, ssh, permissions | Debug a port-in-use issue |
| 92 | HTTP deep dive: methods, status codes, headers, caching, cookies, CORS, HTTPS/TLS | Inspect headers with curl |
| 93 | REST principles, resource design, versioning, Postman/Thunder Client | API collection |
| 94 | OpenAPI/Swagger, JSON schema | Document a sample API |
| 95 | **Review:** Convert a JS project to TypeScript | Strict TS project |

---

## PHASE 4 — Node.js & Express (Days 96–125)

**Goal:** Build secure, scalable, well-structured backend APIs.

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 96 | Node architecture: V8, libuv, event loop phases, single-thread model | Explain event loop with code |
| 97 | Modules: CommonJS vs ESM, core modules (path, os, url) | Utility scripts |
| 98 | `fs` (sync/async/promises), file handling | File-organizer CLI |
| 99 | Streams, buffers, pipelines | Stream a large file |
| 100 | EventEmitter, process, env variables, dotenv, CLI args | Env-driven config |
| 101 | Raw `http` server: routing by hand | Tiny router |
| 102 | Express I: app, routing, req/res, params, query, body | Hello API |
| 103 | Middleware: built-in, third-party, custom, order of execution | Logging/auth middleware |
| 104 | Routers, MVC / layered architecture (routes → controllers → services → repositories) | Restructure API |
| 105 | Validation: Zod / Joi / express-validator | Validate all inputs |
| 106 | Centralized error handling, async wrapper, custom error classes, HTTP status discipline | Consistent error format |
| 107 | **Mini-project:** CRUD REST API (in-memory) | Tested in Postman |
| 108 | Logging: morgan, pino/winston, log levels, correlation IDs | Structured logs |
| 109 | Security basics: helmet, CORS, rate limiting, sanitization, HPP | Hardened API |
| 110 | File uploads: multer, Cloudinary/S3, size/type validation | Image upload endpoint |
| 111 | Pagination, filtering, sorting, searching (offset vs cursor) | Query-builder utility |
| 112 | Auth concepts: sessions vs tokens, hashing with bcrypt/argon2 | Register/login |
| 113 | JWT: access + refresh tokens, httpOnly cookies, rotation | Refresh-token flow |
| 114 | Authorization: RBAC, ownership checks, permissions middleware | Admin vs user routes |
| 115 | OAuth2 / social login (Google/GitHub), Passport.js | Google login |
| 116 | Email: Nodemailer, password reset, email verification, OTP | Forgot-password flow |
| 117 | Config management, 12-factor app, secrets | Multi-env config |
| 118 | API docs with Swagger UI | Live docs endpoint |
| 119 | WebSockets / Socket.IO I: rooms, events, auth | Echo server |
| 120 | Socket.IO II: real-time chat backend | Chat prototype |
| 121 | Background jobs: node-cron, BullMQ, queues, retries | Email queue |
| 122 | Caching intro with Redis (cache-aside, TTL) | Cached endpoint |
| 123 | Testing Node: Jest/Vitest, Supertest, mocking, coverage | 80% coverage on API |
| 124–125 | **Project (2 days):** Auth + Blog REST API (users, posts, comments, roles) | Documented, tested, deployed |

---

## PHASE 5 — Databases (Days 126–150)

**Goal:** Model data well, query efficiently, understand NoSQL vs SQL trade-offs.

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 126 | DB fundamentals: SQL vs NoSQL, ACID vs BASE, CAP theorem | Decision matrix |
| 127 | MongoDB setup, Atlas, mongosh, BSON, documents/collections | Cluster running |
| 128 | CRUD operations | CRUD in shell |
| 129 | Query operators, projection, sort, limit/skip | 20 queries |
| 130 | Update operators, array operators, embedded docs | Advanced updates |
| 131 | Schema design: embedding vs referencing, one-to-many, many-to-many, patterns | Model e-commerce |
| 132 | Indexes: single, compound, text, TTL, `explain()` | Optimize slow query |
| 133 | Aggregation pipeline I: $match, $group, $project, $sort | Sales reports |
| 134 | Aggregation II: $lookup, $unwind, $facet, $bucket | Analytics dashboard queries |
| 135 | Mongoose I: connection, schemas, models, CRUD | Connect to Atlas |
| 136 | Mongoose II: validation, defaults, virtuals, instance/static methods | Rich schema |
| 137 | Mongoose III: middleware (hooks), populate, discriminators | Relations working |
| 138 | Mongoose IV: transactions, sessions, lean(), performance tips | Atomic order creation |
| 139 | Refactor Blog API to MongoDB + Mongoose | Persisted API |
| 140 | Modeling workshop: e-commerce schema (users, products, carts, orders, reviews) | ER/Schema diagram |
| 141 | SQL (PostgreSQL) I: DDL, SELECT, WHERE, JOINs | 20 SQL problems |
| 142 | SQL II: GROUP BY, subqueries, indexes, normalization, transactions | Normalize a schema |
| 143 | ORM awareness: Prisma/Sequelize with Node + Postgres | Same API with Postgres |
| 144 | Redis: data structures, sessions, pub/sub, rate limiting | Redis session store |
| 145 | Migrations, seeding, backup/restore | Seed script |
| 146 | DB security: roles, network access, NoSQL injection | Harden Atlas cluster |
| 147 | Replication, sharding, scaling concepts, read preferences | Diagram a scaled architecture |
| 148–150 | **Project (3 days):** E-commerce backend (products, cart, orders, reviews, search, admin) | Postman-tested, deployed |

---

## PHASE 6 — React (Days 151–195)

**Goal:** Build complex, performant, tested UIs with modern React.

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 151 | React intro, Vite setup, JSX, virtual DOM | First app |
| 152 | Components & props, composition | Reusable UI kit (Button, Card) |
| 153 | State with `useState`, event handling | Counter, toggles |
| 154 | Conditional rendering, lists, keys | Product list |
| 155 | Forms: controlled vs uncontrolled | Multi-step form |
| 156 | Lifting state up, children, composition patterns | Shared state between siblings |
| 157 | `useEffect` I: lifecycle, dependencies | Document title, timers |
| 158 | `useEffect` II: cleanup, data fetching, race conditions | Fetch with cancellation |
| 159 | **Project:** Movie search app (API, debounced search, pagination) | Deployed |
| 160 | `useRef`, `forwardRef`, imperative handles | Focus management, scroll |
| 161 | `useReducer` and reducer patterns | Cart with reducer |
| 162 | Context API, avoiding prop drilling, context performance | Theme + Auth context |
| 163 | Custom hooks (useFetch, useLocalStorage, useDebounce) | Hook library |
| 164 | `useMemo`, `useCallback`, `React.memo` and when NOT to use them | Profile and optimize |
| 165 | Rendering model, reconciliation, StrictMode, batching | Render-count experiments |
| 166 | React Router I: routes, links, params, navigation | Multi-page SPA |
| 167 | React Router II: nested routes, protected routes, loaders/actions, lazy routes | Route guards |
| 168 | Styling: CSS Modules, Tailwind in React, shadcn/ui, MUI | Design-system-based UI |
| 169 | Forms at scale: React Hook Form + Zod | Validated complex forms |
| 170 | **Project:** Auth UI (login/signup/forgot password, protected pages) | Ready for API hookup |
| 171 | Axios, interceptors, token refresh handling | API client layer |
| 172 | TanStack Query I: queries, caching, stale time | Replace useEffect fetching |
| 173 | TanStack Query II: mutations, optimistic updates, infinite queries | Infinite scroll feed |
| 174 | Redux Toolkit I: slices, store, selectors | Cart in Redux |
| 175 | RTK II: createAsyncThunk, RTK Query | Server state via RTK Query |
| 176 | Zustand/Jotai + choosing state tools (local vs global vs server state) | State decision guide |
| 177 | Error boundaries, Suspense, lazy, code-splitting | Split bundle by route |
| 178 | Portals, modals, focus trapping, a11y in React | Accessible modal/dropdown |
| 179 | Performance: React Profiler, virtualization (react-window), memo strategy | 10k-row list smooth |
| 180 | Modern React (18/19): transitions, `useDeferredValue`, `use`, Actions, Server Components concepts | Concurrent UI demo |
| 181 | TypeScript with React (props, hooks, generics, events) | Typed component library |
| 182 | Patterns: compound components, HOC, render props, headless UI | Build a Tabs/Accordion |
| 183 | Design systems, Storybook | Documented components |
| 184 | Animations: Framer Motion | Page transitions |
| 185 | Ecosystem: Recharts, TanStack Table, dnd-kit | Data table + charts |
| 186 | Testing I: Vitest + React Testing Library | Component tests |
| 187 | Testing II: Playwright/Cypress E2E, MSW for mocking | E2E login flow |
| 188 | i18n, theming, dark mode, accessibility audit | Multi-language app |
| 189 | SEO limitations of SPAs, PWA, web vitals | Lighthouse optimization |
| 190–195 | **Project (6 days):** Admin dashboard / Kanban (auth UI, tables, charts, DnD, tests) | Deployed with mock API |

---

## PHASE 7 — Full-Stack MERN Integration & Capstones (Days 196–225)

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 196 | MERN architecture, monorepo structure, shared types/validation | Project scaffold |
| 197 | Connect React ↔ Express: CORS, proxy, env, API layer | Working vertical slice |
| 198 | Full auth flow: JWT cookies, refresh, logout, persistence on reload | Complete auth |
| 199 | Protected routes + RBAC across frontend and backend | Admin vs user UIs |
| 200 | File upload end-to-end (preview, progress, cloud storage) | Avatar & product images |
| 201 | Pagination, filters, infinite scroll end-to-end | Product listing |
| 202 | Real-time with Socket.IO in React (presence, notifications) | Live notifications |
| 203 | Payments: Stripe/Razorpay (checkout, webhooks, idempotency) | Test-mode payments |
| 204 | Emails, queues, and notifications | Order confirmation email |
| 205 | Search: Mongo text/Atlas Search, debounce, highlights | Search with filters |
| 206–215 | **CAPSTONE 1 – E-Commerce Platform (10 days)** | See breakdown below |
| 216–225 | **CAPSTONE 2 – Choose one: Real-time Chat / Social App / Project-management SaaS (10 days)** | See breakdown below |

**Capstone 1 breakdown (E-commerce):**
206 Requirements, ERD, API design, wireframes · 207 Auth & users · 208 Product catalog & admin CRUD · 209 Cart & wishlist · 210 Checkout & payments · 211 Orders & order tracking · 212 Reviews, ratings, search · 213 Admin dashboard & analytics · 214 Tests, a11y, performance · 215 Deploy (Vercel + Render + Atlas) + case study README.

**Capstone 2 breakdown (e.g., Project-management SaaS / Chat):**
216 Requirements & design · 217 Auth, teams/workspaces · 218 Core entities & APIs · 219 Core UI · 220 Real-time collaboration (Socket.IO) · 221 Notifications & email · 222 Roles/permissions, activity logs · 223 File attachments, search · 224 Tests + CI · 225 Deploy + demo video + documentation.

---

## PHASE 8 — Next.js (Days 226–245)

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 226 | Why Next.js; App Router, file-based routing | First app |
| 227 | Layouts, loading/error states, route groups, dynamic routes | Nested layouts |
| 228 | Server Components vs Client Components | Boundary design |
| 229 | Data fetching, caching, revalidation strategies | ISR blog |
| 230 | Server Actions, forms, mutations | Form without API |
| 231 | Route Handlers (API routes) | REST endpoints inside Next |
| 232 | Authentication (Auth.js / custom JWT), middleware | Protected routes |
| 233 | Middleware, edge runtime, i18n | Locale routing |
| 234 | Images, fonts, metadata, SEO, sitemap, OG images | 100 SEO score |
| 235 | Rendering strategies: SSG, ISR, SSR, streaming, PPR | Compare strategies |
| 236 | Next.js + MongoDB/Mongoose (connection pooling in serverless) | Data layer |
| 237 | Next.js + Prisma/Postgres (optional) | Alternative stack |
| 238 | Testing & performance (bundle analysis, Core Web Vitals) | Optimization report |
| 239 | Deploy on Vercel; env, preview deployments | Live URL |
| 240–245 | **Project (6 days):** SEO-friendly Blog/Marketplace/SaaS landing + dashboard in Next.js | Deployed |

---

## PHASE 9 — DevOps, Cloud & Security (Days 246–270)

| Day | Topic | Hands-on / Outcome |
|---|---|---|
| 246 | Linux server basics, SSH, firewall, users, systemd | Provision a VPS |
| 247 | Nginx reverse proxy, Let's Encrypt SSL, PM2 | App live on HTTPS |
| 248 | Docker I: images, containers, volumes, networks | Run Node app in Docker |
| 249 | Docker II: Dockerfile best practices, multi-stage builds, .dockerignore | Slim production image |
| 250 | docker-compose for MERN (+ Mongo, Redis) | One-command dev env |
| 251 | CI/CD concepts; GitHub Actions I | Run tests on every PR |
| 252 | GitHub Actions II: build, cache, deploy, secrets, environments | Auto-deploy pipeline |
| 253 | PaaS deployments: Render/Railway/Vercel/Netlify, MongoDB Atlas | Compare options |
| 254 | AWS I: IAM, EC2, S3, security groups | Deploy to EC2 |
| 255 | AWS II: Route 53, CloudFront, ALB, RDS/DocumentDB | CDN + custom domain |
| 256 | AWS III: Lambda, API Gateway, ECS/Fargate overview | Serverless function |
| 257 | Kubernetes concepts (pods, deployments, services, ingress) | Minikube demo |
| 258 | Infrastructure as Code: Terraform basics | Provision S3 + EC2 via code |
| 259 | Observability: logs, metrics, tracing, Sentry, Prometheus/Grafana, OpenTelemetry | Error tracking live |
| 260 | OWASP Top 10 I: broken access control, injection, auth failures | Exploit & fix in a lab |
| 261 | OWASP II: XSS, CSRF, SSRF, secrets management, `npm audit`, dependency risk | Security checklist |
| 262 | Web performance: CDN, compression, HTTP/2, caching headers, image optimization | Core Web Vitals pass |
| 263 | Scalability basics: stateless services, horizontal scaling, load balancing | Nginx load-balance 2 instances |
| 264 | **Project:** Dockerize + CI/CD + deploy capstone to AWS/VPS | Production pipeline |
| 265 | Redis in production, rate limiting, session scaling | Distributed rate limiter |
| 266 | Backups, disaster recovery, zero-downtime deploys (blue/green) | Runbook |
| 267 | Cost awareness, monitoring alerts, uptime checks | Alert rules |
| 268 | Feature flags, env promotion, rollback strategy | Release checklist |
| 269 | Load testing (k6/Artillery) | Find your bottleneck |
| 270 | **Review:** DevOps interview questions | Self-assessment |

---

## PHASE 10 — DSA, System Design & Interview Prep (Days 271–310)

### DSA in JavaScript (Days 271–290)

| Day | Topic |
|---|---|
| 271 | Big-O, time/space complexity |
| 272 | Arrays & strings patterns |
| 273 | Hash maps & sets |
| 274 | Two pointers |
| 275 | Sliding window |
| 276 | Prefix sums, binary search |
| 277 | Recursion & backtracking |
| 278 | Linked lists |
| 279 | Stacks & queues |
| 280 | Trees I (traversals, DFS/BFS) |
| 281 | Trees II (BST, LCA) |
| 282 | Heaps / priority queue |
| 283 | Graphs I (BFS/DFS, connected components) |
| 284 | Graphs II (topological sort, shortest path basics) |
| 285 | Dynamic programming I (1D) |
| 286 | Dynamic programming II (2D) |
| 287 | Greedy & intervals |
| 288 | Sorting algorithms & tries |
| 289 | Mixed practice set (timed, 4 problems) |
| 290 | Mock coding round + review (target: 100+ problems solved) |

### System Design & Machine Coding (Days 291–300)

| Day | Topic |
|---|---|
| 291 | System design fundamentals: requirements, estimation, trade-offs |
| 292 | Load balancers, caching, CDN, databases at scale |
| 293 | Design: URL shortener |
| 294 | Design: chat application |
| 295 | Design: news feed / notification system |
| 296 | Frontend machine coding: autocomplete, star rating |
| 297 | Machine coding: infinite scroll, file explorer |
| 298 | Machine coding: Kanban, tic-tac-toe, stopwatch |
| 299 | Low-level design: OOP, SOLID, design patterns in JS/TS |
| 300 | Mock machine-coding + design round |

### Role-Specific & Soft Skills (Days 301–310)

| Day | Topic |
|---|---|
| 301 | JavaScript deep-dive interview questions |
| 302 | React interview questions (hooks, rendering, performance) |
| 303 | Node.js & Express interview questions (event loop, streams, scaling) |
| 304 | MongoDB & database interview questions |
| 305 | Behavioral interviews, STAR method, project storytelling |
| 306 | Resume (ATS-friendly), LinkedIn, GitHub polish |
| 307 | Portfolio website with case studies |
| 308 | Mock interview #1 (peer/AI) |
| 309 | Mock interview #2 + feedback fixes |
| 310 | Job-search strategy, referrals, negotiating offers |

---

## PHASE 11 — Open Source, Portfolio & Job Hunt (Days 311–320)

| Day | Topic | Outcome |
|---|---|---|
| 311 | Find "good first issues"; read a codebase | Shortlist 3 repos |
| 312–314 | Make your first open-source contribution | Merged/opened PR |
| 315 | Write 2 technical blog posts (dev.to/Hashnode) | Published articles |
| 316 | Finalize 3 flagship projects (README, demo video, live link) | Portfolio complete |
| 317–319 | Apply daily (10–15 targeted applications), networking, mock interviews | Pipeline started |
| 320 | **Graduation review:** compare against the skills checklist below | Job-ready |

### ✅ Job-Ready Checklist
- [ ] 3 deployed full-stack projects with README & tests
- [ ] 100+ DSA problems solved
- [ ] Comfortable with Git workflows & PR reviews
- [ ] Can explain event loop, closures, React rendering, JWT flow, indexing
- [ ] Docker + CI/CD pipeline created at least once
- [ ] 1 open-source PR, 2 blog posts, polished LinkedIn/GitHub

---

# PART B — YEARS 1 TO 5 ON THE JOB

> From here the pace is **month/quarter-wise**. Each month has a focus theme, a weekly cadence, and a "deliverable". Follow a **70/20/10 rule**: 70% job work, 20% deliberate learning, 10% side experimentation.

**Weekly cadence (all years):**
- Mon–Fri: 30–60 min learning block (read docs/blogs/source code, one topic)
- Saturday: build/experiment (side project or open-source)
- Sunday: weekly review, update learning log, plan next week

---

## PHASE 12 — Year 1: Junior Developer (0–1 yr)

**Goal:** Become a reliable contributor who ships features with minimal supervision.

| Month | Focus | Learning Targets | Deliverable |
|---|---|---|---|
| 1 | Onboarding | Codebase tour, dev setup, team Git workflow, ticketing (Jira), code-review etiquette | Fix 3 small bugs |
| 2 | Debugging mastery | Debuggers, logs, network tab, reproducing issues, reading stack traces | Resolve a production bug with RCA |
| 3 | Feature delivery | Break tickets into tasks, estimation, writing clean PRs, unit tests | Ship first full feature |
| 4 | Testing culture | TDD basics, integration tests, mocking, test pyramid | Raise coverage on a module |
| 5 | API & DB proficiency | Query optimization, indexes, pagination in real data, migrations | Optimize a slow endpoint |
| 6 | Frontend polish | Accessibility, performance profiling, reusable components, design-system usage | Improve a page's Lighthouse score |
| 7 | Security hygiene | Input validation, authN/authZ review, secrets handling, dependency updates | Security checklist applied |
| 8 | Reading code deeply | Read source of Express/React internals, popular libs | Blog post: "How X works internally" |
| 9 | Communication | Writing design notes, async updates, asking good questions, standups | Write a mini-RFC |
| 10 | CI/CD & tooling | Pipeline tweaks, Docker usage, env management | Fix/extend a pipeline |
| 11 | Ownership | Take a small module end-to-end, on-call shadowing, monitoring | Own one module |
| 12 | Review & goal-setting | Self-review, collect feedback, plan Year 2 | Promotion/appraisal doc |

**Year-1 Exit Skills:** independent bug-fixing, clean PRs, solid testing, comfortable with prod logs, basic estimation.

---

## PHASE 13 — Years 2–3: Mid-Level Developer (1–3 yrs)

**Goal:** Own features and services end-to-end; design solutions; start influencing the team.

### Year 2 — Depth

| Quarter | Focus | Topics | Deliverable |
|---|---|---|---|
| Q1 | Advanced Node & backend design | Clustering, worker threads, streams at scale, graceful shutdown, API versioning, idempotency, retries | Refactor a service for reliability |
| Q2 | Advanced React & frontend architecture | Micro-frontends concept, module federation, state architecture, performance budgets, design system ownership, advanced TypeScript | Lead a frontend architecture improvement |
| Q3 | Data & messaging | Advanced Mongo/Postgres tuning, transactions, CQRS/event sourcing basics, Kafka/RabbitMQ/SQS, caching strategies | Build an event-driven workflow |
| Q4 | Quality & reliability | Contract testing, E2E strategy, observability (metrics/tracing), SLOs, incident response, postmortems | Lead an incident postmortem |

### Year 3 — Breadth & Leadership

| Quarter | Focus | Topics | Deliverable |
|---|---|---|---|
| Q1 | Architecture | Monolith vs microservices, modular monolith, domain-driven design, API gateways, GraphQL/tRPC/gRPC | Architecture decision record (ADR) |
| Q2 | Cloud-native | AWS/GCP deeper (ECS/EKS, SQS/SNS, CloudWatch), IaC (Terraform), Kubernetes fundamentals, cost optimization | Deploy a service with IaC |
| Q3 | Security & compliance | OAuth2/OIDC deep dive, SSO, threat modeling, GDPR/SOC2 awareness, pen-test findings remediation | Threat model for a feature |
| Q4 | Mentorship & delivery | Mentoring juniors, running code reviews, sprint planning, tech-debt management, estimation at scale | Mentor 1–2 juniors; lead a project |

**Mid-Level Exit Skills:** designs features independently, writes RFCs, mentors juniors, handles on-call, owns reliability of a service.

---

## PHASE 14 — Years 4–5: Senior Developer (3–5 yrs)

**Goal:** Drive technical direction, solve ambiguous problems, multiply the team's output.

### Year 4 — Technical Leadership

| Quarter | Focus | Topics | Deliverable |
|---|---|---|---|
| Q1 | System design at scale | Distributed systems (consistency, partitioning, consensus concepts), multi-region, sharding, rate-limiting, back-pressure | Design doc for a high-scale system |
| Q2 | Performance & scale engineering | Profiling Node (flamegraphs), memory leaks, DB sharding/replicas, CDN/edge strategy, caching layers, load tests | 2–5× performance improvement on a key flow |
| Q3 | Platform & developer experience | Monorepo tooling (Nx/Turborepo), internal libraries, CI speedups, standards, golden paths | Reduce build/test time significantly |
| Q4 | Product thinking | Working with PM/design, metrics, experimentation/A-B tests, trade-off communication, roadmap input | Drive a feature from idea → impact metric |

### Year 5 — Senior / Staff-Track

| Quarter | Focus | Topics | Deliverable |
|---|---|---|---|
| Q1 | Architecture governance | ADRs, tech radar, build-vs-buy, migration strategies (strangler pattern), managing tech debt at org level | Lead a major migration plan |
| Q2 | Reliability & security leadership | SRE practices, error budgets, chaos testing, DR drills, secure SDLC | Reduce incidents/MTTR measurably |
| Q3 | People & influence | Hiring & interviewing, coaching, cross-team collaboration, technical writing, public speaking | Run hiring loops; give a tech talk |
| Q4 | Specialization & next step | Choose a path: **Staff/Principal IC**, **Engineering Manager**, **Architect**, **AI-augmented engineering**, or **Founding engineer/Freelance** | 3-year career plan |

**Senior Exit Skills:** designs and leads multi-team systems, balances trade-offs, mentors seniors/juniors, communicates with leadership, owns outcomes not just code.

---

## Optional Specializations (Choose After Year 2)

| Track | Topics |
|---|---|
| **Frontend Specialist** | Web performance, advanced a11y, WebGL/Canvas, design systems, micro-frontends, browser internals |
| **Backend/Platform Specialist** | Distributed systems, message brokers, Kubernetes, observability, database internals |
| **AI-Enabled Full-Stack** | LLM APIs, RAG, vector databases (Atlas Vector Search/pgvector), streaming UIs, prompt/eval engineering, agent tooling |
| **Mobile Extension** | React Native / Expo with shared TypeScript logic |
| **Realtime/Gaming** | WebSockets at scale, WebRTC, CRDTs |
| **Security-Focused** | AppSec, pen-testing basics, secure architecture |

---

## Skills Progression Matrix

| Skill Area | Junior (0–1) | Mid (1–3) | Senior (3–5) |
|---|---|---|---|
| JavaScript/TS | Solid fundamentals | Advanced types, patterns | Language-level depth, mentor others |
| React | Build features | Architect modules, performance | Define frontend architecture |
| Node/Express | CRUD, auth APIs | Reliable services, queues, caching | Distributed design, scale, platform |
| Databases | Basic CRUD, schemas | Indexing, tuning, transactions | Data architecture, sharding, polyglot |
| Testing | Unit tests | Integration/E2E strategy | Quality strategy across org |
| DevOps | Use CI/CD, Docker | Own pipelines, IaC | Platform strategy, reliability |
| Security | Basic hygiene | Threat-aware design | Secure SDLC leadership |
| Design | Follow patterns | Design features/services | System-level, multi-team design |
| Communication | Ask good questions | Write RFCs, mentor | Influence, stakeholder alignment |
| Ownership | Tasks | Features/services | Outcomes/products |

---

## Recommended Free Resources

| Area | Resource |
|---|---|
| Web fundamentals | MDN Web Docs, web.dev, javascript.info |
| HTML/CSS practice | Frontend Mentor, CSS Diner, Flexbox Froggy, Grid Garden |
| JavaScript | You Don't Know JS (book), Namaste JavaScript, Exercism |
| React | react.dev (official docs), Epic React, Bulletproof React repo |
| Node | nodejs.org docs, Node Best Practices repo |
| MongoDB | MongoDB University (free) |
| TypeScript | TypeScript Handbook, Total TypeScript (free parts) |
| DSA | NeetCode, LeetCode, Striver's sheets |
| System Design | System Design Primer (GitHub), ByteByteGo |
| DevOps | Docker docs, GitHub Actions docs, AWS Skill Builder |
| Security | OWASP Cheat Sheets, PortSwigger Web Security Academy |
| Full-stack courses | The Odin Project, freeCodeCamp, Full Stack Open (University of Helsinki) |

---

## Progress Tracking Template

Copy this into your daily log:

```
Date:
Day #:
Topic studied:
What I built/practiced:
GitHub commit link:
What confused me:
Tomorrow's plan:
```

**Checkpoints:** end of Phases 1, 2, 4, 6, 7, 9, and 10 → build/deploy a project and write a short retrospective.

---

*Tip: If a topic takes longer than planned, extend it — depth beats speed. Consistency (daily coding) matters more than the pace.*
