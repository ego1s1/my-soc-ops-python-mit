# Soc Ops - Agent Instructions

## Mandatory Development Checklist
- [ ] Lint: `uv run ruff check .`
- [ ] Test: `uv run pytest`
- [ ] Build: `uv sync`

## Project Overview
Soc Ops is a social bingo game built with FastAPI and HTMX for in-person networking events.

## Tech Stack
- Backend: FastAPI with session management
- Frontend: HTMX + Jinja2 templates
- Testing: pytest
- Linting: ruff (Python 3.13+)

## Key Commands
- Dev server: `uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000`
- Tests: `uv run pytest`
- Lint: `uv run ruff check .`
- Sync deps: `uv sync`

## Architecture
- Session-based game state (Starlette sessions)
- HTMX for progressive enhancement
- Component-based templates in `app/templates/components/`
- Game logic in `app/game_logic.py`
- Pydantic models in `app/models.py`

## Key Files
- `app/main.py`: FastAPI routes
- `app/game_service.py`: Session management
- `app/game_logic.py`: Bingo logic
- `app/templates/`: Jinja2 templates
- `app/static/`: CSS, JS
- `tests/`: pytest files

## Conventions
- Use `uv` for all Python ops
- FastAPI async patterns
- HTMX for dynamic updates
- Functional programming in game logic

## Pitfalls
- No VS Code Simple Browser - use external browser
- Python 3.13+ required
- Session state not persistent across restarts

## Custom Agents
See `.github/agents/` for TDD, UI review, and quiz master agents.

## Documentation
- [Workshop](workshop/) - Lab guides
- [README](README.md) - Overview
- [Contributing](CONTRIBUTING.md) - Guidelines
