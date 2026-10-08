# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Prerequisites: Python 3.10+, Git.

&#x09;mkdir \~/projects/csc10014

&#x09;cd \~/projects/csc10014

&#x09;git clone https://github.com/<your_github_account_name>/lab01-<your_github_account_name>.git

&#x09;cd lab01-<your_github_account_name>
&#x09;Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

&#x09;python -m venv .venv

&#x09;.venv\\Scripts\\Activate.ps1

&#x09;Remove-Item -Recurse -Force .venv

&#x09;py -m venv .venv

&#x09;.\\.venv\\Scripts\\Activate.ps1

&#x09;pip install -r requirements.txt

TODO (Lab 1): write the exact steps a new teammate needs, from a fresh machine to
running the app and the tests. Your partner will follow them without your help.

## Run

&#x09;python -m assistant "where is the IT helpdesk?"

## Test

&#x09;pytest -q

## Project structure



## Troubleshooting

\- If "mkdir \~/projects/csc10014" "already exists", move to next step.

\- If "python -m venv .venv" and ".venv\\Scripts\\Activate.ps1" run out red, do "Remove-Item -Recurse -Force .venv" and then "py -m venv .venv".

