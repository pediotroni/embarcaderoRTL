# Embarcadero RTL Recovery Archive

A personal archive created from practical experience with Windows applications developed using Delphi and Embarcadero development tools.

## Purpose

Over the years, applications that had previously worked correctly could stop starting after unrelated changes to the Windows environment. Runtime dependencies could be deleted, damaged, replaced, or otherwise become unavailable.

This repository was originally created as a convenient personal collection of runtime files that could help diagnose and recover such applications without having to search for individual dependencies one by one.

The repository is now maintained as **documentation and a record of that experience**. Proprietary or otherwise uncertain third-party runtime files are intentionally not distributed here.

## Why Runtime Dependencies Can Matter

A Delphi/Embarcadero application may depend on runtime libraries or packages in addition to its own executable.

A previously working application can therefore fail after:

- system maintenance or recovery;
- removal or replacement of software;
- accidental deletion or corruption of runtime files;
- changes to the application environment;
- hardware or operating-system changes.

When troubleshooting such a failure, the correct dependency and compatible version should be identified rather than replacing files solely because they have the same filename.

## Repository Scope

This repository is:

- a personal technical archive;
- a record of practical Windows/Delphi deployment experience;
- intended to document runtime-dependency recovery issues;
- independent of Embarcadero.

This repository is **not**:

- an official Embarcadero repository;
- a replacement for a Delphi or RAD Studio installation;
- a source of proprietary Embarcadero runtime files;
- a guarantee that a particular runtime file is compatible with a particular application.

## Redistribution

Files that may be proprietary to Embarcadero or another third party are not distributed in this repository.

The absence of a file from this repository is intentional. If an application requires a Delphi/Embarcadero runtime dependency, obtain the appropriate file from the application's licensed development environment, an authorized installation, or another source that is legally permitted to provide it.

The repository owner does not claim ownership of third-party software or grant any license to use, modify, or redistribute third-party software.

Users are responsible for complying with the applicable license, EULA, deployment terms, and other legal conditions for the software they use.

## Troubleshooting Guidance

When an existing application reports a missing runtime dependency:

1. Record the exact filename and error message.
2. Identify the Delphi/RAD Studio version used to build the application, if possible.
3. Determine whether the application uses runtime packages.
4. Obtain the required dependency from an appropriate licensed or authorized source.
5. Back up existing files before replacing anything.
6. Avoid overwriting unrelated system files.
7. Test the application after restoring the correct dependency.

## Background

This repository originated from a simple practical problem.

When software was installed for users, it could continue working until a later Windows problem or unrelated software change affected its runtime dependencies. Recovering the application could then require finding which file was missing, locating the correct version, and checking additional dependencies.

The original archive was intended to make that recovery process easier.

The public repository no longer distributes those runtime files. Instead, it preserves the technical context and the lessons learned from maintaining such applications.

## Disclaimer

This repository is provided for documentation and reference purposes.

No compatibility, availability, ownership, or redistribution rights are implied for third-party software mentioned or discussed here.

For current licensing, deployment, and redistribution requirements, consult the official documentation and license terms applicable to the specific Delphi/RAD Studio version and software involved.
