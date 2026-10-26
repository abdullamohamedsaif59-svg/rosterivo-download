# ROSTERIVO — office pilot build, 26 October 2026

**ROSTERIVO_OfficeDownload_20261026_staging.zip** — 49.4 MiB

```
SHA-256  f3d70897cb749b1145df952919bc8619a3cb7033dfd7de0710ea45c8a7f704e5
```

Windows desktop application. No installer: unzip it, keep the folder
together, and run **Rosterivo.exe**. The PC needs an internet connection
and nothing else — no Python, no database, nothing to install.

---

## What to do, in order

**One person — the coordinator — presses Create Account.** That makes the
company and makes them its owner. It is the only time anybody should press
it.

**Everybody else presses "I was invited to a company."** The coordinator
invites each colleague from **Settings → People → Invite someone**, which
hands back a link to pass on. The colleague pastes it, chooses a name and a
password, and presses Join Company.

Entering an employee is **not** the same as adding a user. An employee is a
workforce record; a user is somebody who signs in. A person can be one, the
other, or both.

## This build

* Joining a company from inside the application, with invitations an owner
  hands over — no email service needed.
* An invitation can be used once, by the person it was addressed to. An
  existing ROSTERIVO account is reached only by its own password.
* Every window fits a 1366×768 laptop, including at 125% scaling.
* The Overtime section, and the refreshed interface.

## What it connects to

The ROSTERIVO **test** service. This is a pilot build for learning the
application: the data entered is test data.

## Checking what you downloaded

```powershell
Get-FileHash .\ROSTERIVO_OfficeDownload_20261026_staging.zip -Algorithm SHA256
```

The result should match the SHA-256 above, character for character. If it
does not, do not run it — download it again.

## What is in this repository

The built application, and nothing else. No source code, no credentials,
and no company data of any kind.
