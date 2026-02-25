# All Projects Overview & Analysis

> Auto-generated analysis of all catafest GitHub repositories.
> Date: 2026-02-25

---

## Table of Contents

- [Summary Statistics](#summary-statistics)
- [Projects by Category](#projects-by-category)
- [Detailed Project Analysis](#detailed-project-analysis)
- [Recommendations](#recommendations)

---

## Summary Statistics

| Metric | Value |
|--------|-------|
| Total Repositories | 44 |
| Active (updated in last year) | 5 |
| Stale (1-3 years old) | 18 |
| Archived/Abandoned (3+ years) | 21 |
| Python Projects | 14 |
| Godot Game Engine Projects | 8 |
| Web (JS/Next.js/Flask/Django) | 11 |
| Other (Go, C#, C, Mono, etc.) | 11 |

---

## Projects by Category

### Python Desktop & Tools
| Repository | Last Updated | Status |
|------------|-------------|--------|
| Alia | 2024-06 | Stale |
| catafest_browser | 2024-06 | Stale |
| catafest_yt_downloader | 2024-06 | Stale |
| catafest-md5-encrypt | 2024-06 | Stale |
| catafest_ro_tv | 2024-06 | Stale |
| delete_files_regular_expresion_catafest | 2024-06 | Stale |
| pygame_gui_001 | 2024-06 | Stale |
| pygame-medic-snake | 2019-12 | Abandoned |
| cut_sprites_masks | N/A | Empty |

### Web Development (Flask / Django)
| Repository | Last Updated | Status |
|------------|-------------|--------|
| my_flask | 2019-09 | Abandoned |
| flask_yt | 2019-08 | Abandoned |
| django_test_001 | 2024-06 | Stale |
| django_test_002 | 2024-06 | Stale |
| django_chart | 2020-01 | Abandoned |

### Web Development (JavaScript / Next.js)
| Repository | Last Updated | Status |
|------------|-------------|--------|
| nextjs-blog-theme | 2022-08 | Abandoned |
| nextjsthreejs001 | 2023-08 | Stale |
| Airtable001 | 2022-05 | Abandoned |
| modelviewer_Pepsi_3D | 2022-05 | Abandoned |
| vercel001 | N/A | Empty |
| test_static_001 | 2023-10 | Stale |

### Godot Game Engine
| Repository | Last Updated | Status |
|------------|-------------|--------|
| TypewriterEffect | 2023-06 | Stale |
| Godot-TypewriterEffect | N/A | Empty |
| Godot4MainMenu001 | 2023-08 | Stale |
| FileDialogExample | 2023-06 | Stale |
| ShadersTests | 2023-09 | Stale |
| ParticlesTests | 2023-09 | Stale |
| Sprite2D_001 | 2023-09 | Stale |
| CurvedTerrain_2D_001 | 2024-05 | Stale |

### Blender / 3D
| Repository | Last Updated | Status |
|------------|-------------|--------|
| catafest_blender_start | 2020-04 | Abandoned |
| catafest_ImageToPointCloud | 2025-05 | Active |

### Google Colab / Notebooks / Data
| Repository | Last Updated | Status |
|------------|-------------|--------|
| colab_google | 2026-01 | Active |
| catafest_jupyter-book | 2019-02 | Abandoned |
| devpost_hackathon_2025 | 2025-06 | Active |

### Other / Misc
| Repository | Last Updated | Status |
|------------|-------------|--------|
| catafest | 2026-02 | Active (Profile) |
| catafest.github.io | 2023-08 | Stale |
| catafest_pelican | 2019-05 | Abandoned |
| golang_tests | 2017-12 | Abandoned |
| fasm_editor | 2024-11 | Stale |
| radio-online-catafest | 2024-02 | Stale |
| planet | 2019-03 | Abandoned |
| projects_mono | 2020-10 | Abandoned |
| UnityProjects | 2021-07 | Abandoned |
| drawio_diagrams | 2023-04 | Stale |
| skills-introduction-to-github | 2025-04 | Active |

---

## Detailed Project Analysis

### 1. Airtable001
- **Description**: Test project with Airtable and Node.js
- **Tech**: Node.js, `airtable` ^0.11.4
- **Last Commit**: 2022-05-15
- **Freshness**: The `airtable` npm package is now at v0.12.x. Minor version behind.
- **Improvements**: Update `airtable` dependency. Add `.gitignore` for `node_modules`. Add error handling and example usage documentation.

### 2. Alia
- **Description**: Human interface Python app using Google Speech (tray icon, splash screen)
- **Tech**: Python 3.7.4, PyQt5, SpeechRecognition, pyaudio
- **Last Commit**: 2024-06-12
- **Freshness**: PyQt5 is legacy; PyQt6 is current. SpeechRecognition is still maintained.
- **Improvements**: Migrate to PyQt6. Update Python version requirement to 3.10+. Add `requirements.txt`. The README references Fedora-specific installs; add cross-platform instructions.

### 3. catafest
- **Description**: GitHub profile README
- **Last Commit**: 2026-02-01
- **Status**: Active and up to date.
- **Improvements**: None critical. Could add dynamic stats with GitHub Actions.

### 4. catafest_blender_start
- **Description**: Simple Blender 3D addon for version 2.8
- **Tech**: Python, Blender API
- **Last Commit**: 2020-04-22
- **Freshness**: Built for Blender 2.8. Current Blender is 4.x. The addon API has changed significantly.
- **Improvements**: Rewrite for Blender 4.x Extensions API. The `bl_info` dictionary format and registration have changed. This addon will NOT work on modern Blender without modifications.

### 5. catafest_browser
- **Description**: Simple browser with Python and PyQt5
- **Tech**: Python, PyQt5
- **Last Commit**: 2024-06-12
- **Freshness**: PyQt5 is legacy. PyQt6 + QtWebEngine is the modern approach.
- **Improvements**: Migrate to PyQt6. Add `requirements.txt`. Add basic security features (HTTPS indicator, cookie management). Consider using `QWebEngineView` with modern settings.

### 6. catafest.github.io
- **Description**: GitHub Pages personal site
- **Tech**: Jekyll (implied by `_config.yml`), Markdown
- **Last Commit**: 2023-08-30
- **Improvements**: Update content. Consider migrating to a modern static site generator (Hugo, Astro) or use GitHub Pages with Next.js.

### 7. catafest_ImageToPointCloud
- **Description**: Blender extension for processing 2D images to point cloud
- **Tech**: Python, Blender Extensions API
- **Last Commit**: 2025-05-02
- **Status**: Active and relatively current.
- **Improvements**: Pending approval on Blender extensions website. Add installation instructions. Add example output images.

### 8. catafest_jupyter-book
- **Description**: Jupyter Book project
- **Tech**: Ruby (Gemfile), Jekyll-based, Python requirements
- **Last Commit**: 2019-02-15
- **Freshness**: Very outdated. Jupyter Book has been completely rewritten since 2019. Current version uses Sphinx, not Jekyll.
- **Improvements**: Migrate to modern Jupyter Book (v0.15+) which uses `_toc.yml` and `_config.yml` with Sphinx backend. Remove Ruby/Gemfile dependencies.

### 9. catafest-md5-encrypt
- **Description**: MD5 encryption tool in Python
- **Tech**: Python (single `main.py`)
- **Last Commit**: 2024-06-12
- **Improvements**: MD5 is cryptographically broken and should NOT be used for security. Add warnings in README. Consider adding SHA-256/SHA-3 alternatives. Add `argparse` for CLI usage.

### 10. catafest_pelican
- **Description**: Pelican static site generator project
- **Tech**: Python, Pelican
- **Last Commit**: 2019-05-23
- **Freshness**: Pelican is still maintained (v4.9+), but this repo appears to be minimal/empty.
- **Improvements**: Either populate with content and update Pelican config, or archive the repo.

### 11. catafest_ro_tv
- **Description**: Romanian TV channels scraper/viewer
- **Tech**: Python
- **Last Commit**: 2024-06-12
- **Improvements**: Add `requirements.txt`. Document the purpose and usage more clearly.

### 12. catafest_yt_downloader
- **Description**: YouTube video downloader with PyQt6
- **Tech**: Python, PyQt6
- **Last Commit**: 2024-06-12
- **Freshness**: Uses PyQt6 (modern). However, YouTube downloaders often break due to YouTube API changes. The underlying library (likely `pytube` or `yt-dlp`) needs to be kept up to date.
- **Improvements**: Add `requirements.txt`. Specify which YouTube download library is used. Consider using `yt-dlp` (actively maintained) instead of `pytube` (often broken). Add error handling for unavailable videos.

### 13. colab_google
- **Description**: Collection of Google Colab notebooks (29+ notebooks)
- **Tech**: Python, Jupyter/Colab notebooks
- **Last Commit**: 2026-01-01
- **Status**: Active. Large collection of various experiments.
- **Improvements**: Add a README.md with an index/description of each notebook. Organize notebooks into folders by topic. Add a table of contents.

### 14. CurvedTerrain_2D_001
- **Description**: Simple curved terrain 2D example with Godot 4.3 dev
- **Tech**: Godot 4.x, GDScript
- **Last Commit**: 2024-05-06
- **Freshness**: Built for Godot 4.3 dev. Godot 4.4 is now stable.
- **Improvements**: Test and update for Godot 4.4 stable. Add more README documentation.

### 15. cut_sprites_masks
- **Description**: Unknown (empty repo, no README)
- **Status**: Empty. Should be archived or populated.

### 16. delete_files_regular_expresion_catafest
- **Description**: Python utility for deleting files using regular expressions
- **Tech**: Python
- **Last Commit**: 2024-06-12
- **Improvements**: Add `requirements.txt`. Add safety checks (dry-run mode, confirmation prompts). Improve error handling. Add unit tests.

### 17. devpost_hackathon_2025
- **Description**: YouTube Data Analysis Agent Workflow for Devpost hackathon
- **Tech**: Python, YouTube Data API, Google Colab
- **Last Commit**: 2025-06-20
- **Status**: Active, recent hackathon project.
- **Improvements**: Convert agent classes to use a proper agent framework (LangChain, CrewAI). Add proper error handling for API failures. Add visualization output.

### 18. django_chart
- **Description**: Django project with charting
- **Tech**: Python, Django (version unspecified in deps)
- **Last Commit**: 2020-01-25
- **Freshness**: Very outdated. Django has moved from 3.x to 5.x. Contains `db.sqlite3` committed (bad practice).
- **Improvements**: Update to Django 5.x. Remove `db.sqlite3` from repo. Add `requirements.txt`. Add `.gitignore`. Update `settings.py` for modern Django practices.

### 19. django_test_001
- **Description**: Django testing project with blog and admin
- **Tech**: Python, Django, django_otp
- **Last Commit**: 2024-06-12
- **Freshness**: Contains `myvenv` folder (virtual env committed). No `requirements.txt`.
- **Improvements**: Remove `myvenv` from repo. Add proper `requirements.txt`. Add `.gitignore`. Update Django to 5.x. Remove hardcoded credentials from README.

### 20. django_test_002
- **Description**: Simple calendar with Django
- **Tech**: Python, Django 3.0.7, Pipenv
- **Last Commit**: 2024-06-12
- **Freshness**: Django 3.0.7 is EOL (end of life). Current is Django 5.x. `pytz` is replaced by `zoneinfo` in modern Python.
- **Improvements**: Update Django to 5.x. Replace `pytz` with built-in `zoneinfo`. Update `asgiref` and `sqlparse`. Consider using `pyproject.toml` instead of Pipfile.

### 21. drawio_diagrams
- **Description**: Repository for diagrams created with draw.io
- **Tech**: draw.io/diagrams.net
- **Last Commit**: 2023-04-24
- **Improvements**: Add more diagrams. Organize into folders. Add PNG exports for easy viewing on GitHub.

### 22. fasm_editor
- **Description**: FASM (Flat Assembler) editor for Linux
- **Tech**: C# / .NET, GTK#
- **Last Commit**: 2024-11-18
- **Freshness**: Updated for .NET 9.0 locally. GTK# is outdated; consider GTK4 bindings.
- **Improvements**: Push the .NET 9.0 updates to the repo. Migrate from GTK# to Avalonia UI or GTK4 bindings for cross-platform support. Add build instructions.

### 23. FileDialogExample
- **Description**: Godot file dialog example with C#
- **Tech**: Godot 4.x, C#, GDScript
- **Last Commit**: 2023-06-05
- **Improvements**: Update for latest Godot 4.4. Add more documentation on the C#/GDScript hybrid approach.

### 24. flask_yt
- **Description**: Flask app to search YouTube using API v3
- **Tech**: Python, Flask, YouTube Data API v3
- **Last Commit**: 2019-08-16
- **Freshness**: Very outdated. Flask has moved to 3.x. No `requirements.txt` visible.
- **Improvements**: Update to Flask 3.x. Add `requirements.txt`. Use environment variables properly with `python-dotenv`. Add error handling. Update YouTube API client library.

### 25. Godot4MainMenu001
- **Description**: Godot 4 main menu example with C#
- **Tech**: Godot 4.x, C#
- **Last Commit**: 2023-08-30
- **Freshness**: Contains compiled binaries (`.exe`, `.pck`) which should not be in the repo.
- **Improvements**: Remove compiled binaries from repo. Add `.gitignore` for Godot build outputs. Update for Godot 4.4.

### 26. Godot-TypewriterEffect
- **Description**: Empty repo (duplicate of TypewriterEffect?)
- **Status**: Empty. Should be archived or merged with TypewriterEffect.

### 27. golang_tests
- **Description**: Go language tests (Fibonacci sequence)
- **Tech**: Go
- **Last Commit**: 2017-12-19
- **Freshness**: Extremely outdated. Go has evolved significantly since 2017 (modules, generics, etc.).
- **Improvements**: Update to use Go modules (`go.mod`). Add more examples. Update to modern Go idioms. The README lists items 2-7 as empty.

### 28. modelviewer_Pepsi_3D
- **Description**: 3D model viewer for a Pepsi model using model-viewer
- **Tech**: HTML, CSS, JavaScript, Google model-viewer
- **Last Commit**: 2022-05-15
- **Freshness**: `model-viewer` is actively maintained. Should update to latest version.
- **Improvements**: Update `model-viewer` to latest version. Add responsive design improvements. Add loading states.

### 29. my_flask
- **Description**: Flask application with CRUD, file upload, blueprints
- **Tech**: Python, Flask, SQLAlchemy, WTForms, Flask-Migrate
- **Last Commit**: 2019-09-13
- **Freshness**: Very outdated. Contains `.env` file committed (security risk!). Contains `.sqlite` and `.db` files committed.
- **Improvements**: CRITICAL: Remove `.env` file and database files from repo. Update Flask to 3.x. Update all dependencies. Add proper `.gitignore`. Restructure with application factory pattern.

### 30. nextjs-blog-theme
- **Description**: Next.js blog theme (Netlify template)
- **Tech**: Next.js (latest), React 18, Tailwind CSS, Cypress, MDX
- **Last Commit**: 2022-08-04
- **Freshness**: Uses `next: "latest"` which is risky. Should pin version. `eslint: "<8.0.0"` is very outdated (current is 9.x). `next-mdx-remote: "^3.0.1"` is outdated (current is v5).
- **Improvements**: Pin Next.js version. Update to Next.js 15 with App Router. Update eslint to v9. Update `next-mdx-remote` to v5. Update Cypress. Consider migrating from Netlify-specific config.

### 31. nextjsthreejs001
- **Description**: Next.js with Three.js integration
- **Tech**: Next.js 13.2.4, React 18.2.0, Three.js ^0.155.0
- **Last Commit**: 2023-08-21
- **Freshness**: Next.js is at 15.x (was 13.2.4). Three.js is at r170+ (was 0.155). Very outdated.
- **Improvements**: Update Next.js to 15.x (or at least 14.x) with App Router. Update Three.js to latest. Consider using `@react-three/fiber` and `@react-three/drei` for React integration.

### 32. ParticlesTests
- **Description**: Particle effects testing with Godot 4.1.x
- **Tech**: Godot 4.1.x, GDScript
- **Last Commit**: 2023-09-09
- **Improvements**: Update for Godot 4.4. Add more particle examples. Add screenshots/videos for each effect.

### 33. planet
- **Description**: Planet aggregator (RSS feed aggregator)
- **Tech**: Python (Planet Venus fork)
- **Last Commit**: 2019-03-20
- **Freshness**: Planet Venus is abandoned. Modern alternatives: Miniflux, FreshRSS, or custom RSS with `feedparser`.
- **Improvements**: Archive or rewrite using modern RSS tools. The Planet Venus project is no longer maintained.

### 34. projects_mono
- **Description**: Mono/C# projects
- **Tech**: C#, Mono
- **Last Commit**: 2020-10-11
- **Freshness**: Mono is being replaced by .NET 6/7/8/9 cross-platform. 
- **Improvements**: Migrate to .NET 9. Add README. Add project descriptions.

### 35. pygame_gui_001
- **Description**: Simple test with pygame_gui and SQLite
- **Tech**: Python, pygame_gui, SQLite
- **Last Commit**: 2024-06-12
- **Improvements**: Add `requirements.txt`. Add setup instructions. Document the SQLite schema.

### 36. pygame-medic-snake
- **Description**: Snake game variant with medical theme
- **Tech**: Python, pygame
- **Last Commit**: 2019-12-28
- **Freshness**: pygame is still maintained (v2.6). Code likely works but may need pygame 2.x updates.
- **Improvements**: Update for pygame 2.x API changes. Add `requirements.txt`. Add game screenshots. Improve game loop with delta time.

### 37. radio-online-catafest
- **Description**: ncurses-based online radio player for Linux
- **Tech**: C, ncurses, mpg123/ffmpeg
- **Last Commit**: 2024-02-27
- **Improvements**: Add more radio channels. Add a Makefile for building. Add volume control. Consider a TUI framework like `notcurses` for better rendering.

### 38. ShadersTests
- **Description**: Shader testing with Godot 4.1.x
- **Tech**: Godot 4.1.x, GLSL shaders
- **Last Commit**: 2023-09-21
- **Improvements**: Update for Godot 4.4. Add more shader examples. Document each shader's purpose and parameters.

### 39. skills-introduction-to-github
- **Description**: GitHub Skills exercise (forked template)
- **Tech**: Markdown, GitHub Actions
- **Last Commit**: 2025-04-08
- **Status**: Tutorial/learning repo. No improvements needed.

### 40. Sprite2D_001
- **Description**: Godot Sprite2D example
- **Tech**: Godot 4.x, GDScript
- **Last Commit**: 2023-09-05
- **Improvements**: Update for Godot 4.4. Add more documentation.

### 41. test_static_001
- **Description**: Testing static website (minimal)
- **Last Commit**: 2023-10-28
- **Status**: Nearly empty. Archive or populate.

### 42. TypewriterEffect
- **Description**: Godot typewriter effect example with C#
- **Tech**: Godot 4.x, C#
- **Last Commit**: 2023-06-03
- **Improvements**: Update for Godot 4.4. Merge with or archive `Godot-TypewriterEffect` (duplicate).

### 43. UnityProjects
- **Description**: Unity projects collection
- **Tech**: Unity, C#
- **Last Commit**: 2021-07-10
- **Freshness**: No README. Unity has moved through several major versions.
- **Improvements**: Add README. Update for current Unity LTS. Document project contents.

### 44. vercel001
- **Description**: Empty Vercel project
- **Status**: Empty. Archive or populate.

---

## Recommendations

### Critical Issues (Fix Immediately)

1. **my_flask**: `.env` file with credentials committed to repo. Remove immediately and rotate any exposed secrets.
2. **django_test_001**: Hardcoded admin credentials in README (`username catafest password admin76`).
3. **django_chart**: `db.sqlite3` committed. May contain sensitive data.
4. **Godot4MainMenu001**: Compiled binaries (`.exe`, `.pck`) should not be in source control.

### Repos to Archive (Empty or Abandoned)

These repos have no meaningful content or have been abandoned for 5+ years:
- `cut_sprites_masks` (empty)
- `Godot-TypewriterEffect` (empty, duplicate)
- `vercel001` (empty)
- `test_static_001` (nearly empty)
- `catafest_pelican` (nearly empty)
- `golang_tests` (single file, 8+ years old)
- `planet` (abandoned upstream project)

### Dependency Updates Needed (by priority)

| Repository | Current | Latest | Priority |
|-----------|---------|--------|----------|
| django_test_002 | Django 3.0.7 | Django 5.x | HIGH (EOL) |
| django_chart | Django ~3.x | Django 5.x | HIGH (EOL) |
| my_flask | Flask ~1.x | Flask 3.x | HIGH |
| flask_yt | Flask ~1.x | Flask 3.x | HIGH |
| nextjsthreejs001 | Next.js 13.2.4 | Next.js 15.x | MEDIUM |
| nextjs-blog-theme | next-mdx-remote 3.x | v5.x | MEDIUM |
| catafest_browser | PyQt5 | PyQt6 | MEDIUM |
| Alia | PyQt5, Python 3.7 | PyQt6, Python 3.12 | MEDIUM |
| catafest_blender_start | Blender 2.8 API | Blender 4.x API | MEDIUM |
| Airtable001 | airtable 0.11.4 | 0.12.x | LOW |

### General Improvements Across All Repos

1. **Add `.gitignore`** to all repos (many are missing it).
2. **Add `requirements.txt`** or `pyproject.toml` to all Python projects.
3. **Add LICENSE** files where missing.
4. **Improve README files**: Many repos have minimal or no documentation. Add installation instructions, usage examples, and screenshots.
5. **Remove committed artifacts**: Database files, virtual environments, compiled binaries, and `.env` files should never be in source control.
6. **Add CI/CD**: Consider adding GitHub Actions for linting and testing on at least the active projects.
7. **Consolidate duplicates**: Merge `TypewriterEffect` and `Godot-TypewriterEffect`. Consider consolidating small Godot examples into one repo.

### Tech Stack Modernization Path

| Area | Current Stack | Recommended Modern Stack |
|------|--------------|-------------------------|
| Python GUI | PyQt5 | PyQt6 or PySide6 |
| Web Backend | Flask 1.x, Django 3.x | Flask 3.x, Django 5.x, or FastAPI |
| Frontend | Next.js 13 (Pages Router) | Next.js 15 (App Router) |
| Game Engine | Godot 4.1 | Godot 4.4 |
| 3D Addon | Blender 2.8 | Blender 4.x Extensions |
| .NET | Mono, .NET Framework | .NET 9 |
| Go | Pre-modules Go | Go 1.22+ with modules |
| Package Mgmt | pip + requirements.txt | uv or poetry with pyproject.toml |

---

*This analysis was generated by scanning all 44 repositories in the catafest GitHub account. For questions or updates, open an issue on the catafest/catafest repository.*
