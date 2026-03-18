# Asteroids Game

This project was built as part of the **Boot.dev second guided project**.

It is a small Python arcade-style game inspired by Asteroids, created for learning and practice. The project uses `pygame` for gameplay and `uv` for virtual environment and dependency management.

## Prerequisites

Make sure the following are available on your machine:

- Python 3
- `uv`

## Install `uv` on Linux

If `uv` is not installed yet, run:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh


# Clone the repo
git clone https://github.com/farhanaftab25/asteroids-game.git
cd asteroids-game

# Create and activate virtual environment
uv venv
source .venv/bin/activate

# Sync dependencies and start the game
uv sync
python main.py
