### Hi, I'm Josip 👋

I'm a PHP developer working mostly inside the WordPress and WooCommerce
ecosystem.

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
  variables, accessibility-aware (ARIA, keyboard nav,
  `prefers-reduced-motion`), no surprises.

#### How I work

- I **think in modules**. Each feature ships as its own folder with a
  README, a version, and a clean install line — so it can be dropped
  into another site without manual wiring.
- I **document as I go**. Every module I build has a README explaining
  what it does, the public surface, dependencies, and how to
  extend it - for the next person but in reality it's mostly future me.
- I **version things properly** (semver, tags, changelogs) so other
  sites can pull updates safely or pin to a known-good version.
- I take **security seriously** — nonces, capability checks, prepared
  statements, enum whitelisting, escape-on-output, honeypots. Not as
  an afterthought, as part of the build.

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
- Internal tools, CRMs, and admin dashboards living inside `wp-admin`.

#### Get in touch

Best way to reach me is by email — **info@e-com.hr** ←

You can also open an issue on any of my pinned repos.
