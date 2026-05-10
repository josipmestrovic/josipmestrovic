### Hi, I'm Josip 👋

I'm a PHP developer working mostly inside the WordPress and WooCommerce
ecosystem. I think in modules and document as I go. I pay attention to versioning things properly and I take security seriously.

On most projects I've also been the person doing the architectural
decisions on the WordPress side — how data is modelled, how features
talk to each other, what's a plugin vs. a theme module vs. an external
service.

#### Beyond writing code

- **Product discovery** — sitting with clients (or their team) to turn
  a vague "we need X" into a concrete feature list with edge cases
  thought through before a single line of code gets written.
- **Client meetings & feature communication** — explaining technical
  trade-offs in plain language, scoping what's realistic, and
  pushing back when a request will hurt the project later.
- **WordPress architecture** — on most projects I've been the one
  deciding how the site is structured: CPTs vs. custom tables, plugin
  vs. theme module, where state lives, how features integrate with the
  builder / ACF / WooCommerce, what stays in WP and what belongs
  elsewhere.
- **Project management** — I've led delivery on a few high-end builds
  end-to-end: planning, breaking work down, coordinating with
  designers, keeping the client in the loop, shipping on time.

#### What I actually do day to day

- Build **custom WordPress / WooCommerce features** from scratch or **plug my own code into existing themes, page
  builders (Divi, Elementor) and plugins (ACF, etc.)**.
- Build **admin tooling** — custom DB tables, `WP_List_Table` panels,
  AJAX flows, status workflows with audit trails, smart search and
  filters — when the standard CPT + postmeta combo isn't enough.
- Build **custom internal tools** for clients — small dashboards,
  CRMs, lead managers, anything that lives in `wp-admin` and saves
  somebody an hour a day.
- **Integrate with external systems** — payment gateways, third-party
  APIs, CRMs, mailing services. REST clients, webhooks, signed
  callbacks, retries.
- Set up **cron jobs / scheduled tasks** for background sync, cleanup,
  reminders, and anything that shouldn't block a page load.
- Build **transactional email pipelines** — branded HTML shells,
  multipart/alternative, mobile-responsive, deliverability-aware
  (SPF / DKIM / DMARC, `Reply-To` routing).
- Take a **Figma / XD design and turn it into pixel-perfect, responsive
  HTML / CSS / JS** that holds up when content editors update copy and
  images later.
- **Site migrations & basic server work** — moving WordPress sites
  between hosts (files, DB, serialized search/replace, DNS cutover),
  comfortable on the command line over SSH, working with git in real
  team workflows (branches, tags, conflict resolution, deploy by pull).
  I'm not a full-time sysadmin, but I won't break the box.

#### The stack I reach for

- **PHP** — my main language. Comfortable with WordPress internals,
  hooks, the Settings API, custom queries, `WP_List_Table`, custom
  admin pages, the whole admin UI surface.
- **MySQL** — schemas, joins, query tuning, custom tables with
  `dbDelta()` migrations when postmeta isn't the right tool.
- **JavaScript** (vanilla, mostly) — front-end behavior, AJAX, focus
  traps, Pointer Events, IntersectionObserver, Swiper init, drag and
  swipe gestures. No framework worship.
- **HTML / CSS** — yeah, that too. Mobile-first, BEM-ish, CSS
  variables, accessibility-aware 


#### About AI

I'm pro-AI, but I'm the engineer making the decisions. I gather the
context, understand the problem, design the solution, and review every
line that ends up in the repo. I use AI the same way I use snippets
and IDE autocomplete — to type faster, not to decide what to build.

---

#### Good fit for

- Custom WordPress sites and WooCommerce stores with non-standard
  requirements.
- Existing sites that need a specific feature built and integrated
  cleanly into whatever theme / builder / plugin stack is already
  there.
- Teams that already have a designer and need someone to ship the
  build — pixel-perfect, responsive, accessible.
- Projects that need someone to own the WordPress side end-to-end —
  from discovery and architecture through to shipping.

#### Get in touch

Best way to reach me is by email — **info@e-com.hr** ←

You can also open an issue on any of my pinned repos.
