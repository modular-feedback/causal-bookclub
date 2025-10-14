# Causal AI Book Club

## Purpose

This is a sharing ground for anyone in the Hope, Power, and Healthcare Causal AI Book Club.

## Environment

All dependencies for this project are self-contained in the `uv.lock` file. Here's how to know your environment exactly mirrors the original environment.

1. Install uv

    MacOS or Linux

    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

    Windows

    ```powershell
    powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
    ```

2. Run `uv sync`, which installs all the dependencies in the lock file

    ```bash
    uv sync
    ```

Now everyone in the group is running the same packages, versions, and libraries!
