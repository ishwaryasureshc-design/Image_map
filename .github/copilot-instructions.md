# Copilot Instructions for AI Coding Agents

## Project Overview
This is a Django web application for displaying details about places around the user's home, using an interactive image map. The main app is `ishu_app` inside the `ishwarya` Django project.

## Architecture & Key Components
- **Django Project Structure**: 
  - `ishwarya/` contains the Django project settings, URLs, and WSGI/ASGI entry points.
  - `ishu_app/` is the main Django app, with models, views, admin, and static files.
- **Static Map Integration**:
  - The interactive map is implemented in `static/map.html` using the `<map>` and `<area>` HTML tags.
  - Clickable regions are defined for different places; each region can link to a separate HTML page or Django view.
- **Database**:
  - Uses SQLite (`db.sqlite3`). Models are defined in `ishu_app/models.py`.
- **Admin Interface**:
  - Django admin is enabled for managing data. Register models in `admin.py`.

## Developer Workflows
- **Run the Development Server**:
  - Activate the virtual environment in `ishu/` (use `Scripts/Activate.ps1` for PowerShell).
  - Start server: `python manage.py runserver` from the `ishwarya/` directory.
- **Migrations**:
  - Make model changes in `ishu_app/models.py`.
  - Run `python manage.py makemigrations` and `python manage.py migrate`.
- **Testing**:
  - Tests are in `ishu_app/tests.py`. Run with `python manage.py test`.
- **Static Files**:
  - Place HTML and images in `ishu_app/static/`. Reference them in templates or directly.

## Project-Specific Patterns & Conventions
- **HTML Image Map**:
  - Use `<map>` and `<area>` tags in `map.html` for interactive regions.
  - Each region should correspond to a place and link to details (HTML or Django view).
- **App Naming**:
  - Main app is `ishu_app`. Project is `ishwarya`.
- **Virtual Environment**:
  - Use the provided venv in `ishu/` for all Python/Django commands.
- **File Organization**:
  - Keep static files in `static/` inside the app directory.
  - Django settings, URLs, and entry points are in `ishwarya/ishwarya/`.

## Integration Points
- **External Dependencies**:
  - Django, sqlparse, asgiref, tzdata (see `Lib/site-packages/`).
- **No custom build scripts or nonstandard commands detected.**

## Example Workflow
```powershell
cd ishwarya
..\ishu\Scripts\Activate.ps1
python manage.py runserver
```

## Key Files & Directories
- `ishwarya/ishwarya/settings.py` – Django settings
- `ishwarya/ishwarya/urls.py` – URL routing
- `ishwarya/ishu_app/models.py` – Data models
- `ishwarya/ishu_app/static/map.html` – Interactive map
- `ishwarya/ishu_app/views.py` – App logic

---
**For AI agents:**
- Follow Django conventions unless project-specific patterns are noted above.
- When adding new places, update both the image map and corresponding detail pages/views.
- Use the provided virtual environment for all Python operations.
- Reference static files using Django's static file handling if using templates.
