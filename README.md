# manisha-kalia.github.io

Portfolio site for **Manisha Kalia** — graduate applicant in Computational
Linguistics / NLP / Data Science. Built with Jekyll + the Prologue theme base,
in the same look-and-feel family, with its own teal + rose
identity.

## Pages

| Page | File | Purpose |
|---|---|---|
| Home | `index.md` | Hero + metrics, focus areas, experience, projects, honors |
| About | `about.html` | Story, journey, timeline, quick facts |
| Certificates | `certificates.html` | Degrees, diplomas, REET/RAS — **list only, no scans** |

## Preview / build

GitHub Pages builds this automatically on push (same setup as the sibling
site). No local Ruby needed — push and check the live URL.

## Deploy (GitHub Desktop)

1. In GitHub Desktop: **File → Add local repository →** and select the
   local `manisha-kalia.github.io` folder.
2. Push `main` to the existing **`manisha-kalia/portfolio`** repo
   (public). First push sets upstream: `git push -u origin main`.
3. On github.com → repo **Settings → Pages → Deploy from branch →
   `main` / `/ (root)`**.
4. Live in ~1–2 min at `https://manisha-kalia.github.io/portfolio`.
   (`baseurl: "/portfolio"` in `_config.yml` makes all links work there.)

> Cleaner URL option: rename the repo to **`manisha-kalia.github.io`**
> (Settings → rename), set `baseurl: ""`, push — then the site serves
> from the root `https://manisha-kalia.github.io`.

## Conventions & privacy

- **Never commit certificate/marksheet scans** — they contain Aadhaar, roll
  and enrolment numbers. The `/certificates` page lists credentials only.
- Social icons render only for URLs set in `_config.yml`. Add LinkedIn etc.
  there when the accounts exist (commented placeholders included).
- Theme colors live in `assets/css/main.scss` (`:root` vars `--blue` teal,
  `--purple` rose).
- Bump `main.css?v=N` in `_includes/head.html` + the service-worker cache
  name whenever CSS changes, so visitors get fresh styles.
