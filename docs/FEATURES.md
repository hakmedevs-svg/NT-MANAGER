# Feature Overview

This document describes the intended product scope for NT MANAGER. The repository currently contains documentation only; none of the application capabilities below are verified as implemented or available for download.

## Project Manager

**Goal:** Keep project workflows, project-specific configuration, and build outputs organized in one workspace.

A future implementation could support project discovery, project summaries, and per-project tool settings. Supported project types and operating systems have not yet been established.

## Advanced Build System

**Goal:** Guide developers through supported project builds, with less manual terminal work.

Potential workflows include Android Studio projects, Android application builds, other supported software projects, and projects developed with VS Code. VS Code is an editor workflow—not, by itself, a build system. A practical build still depends on each project's own toolchain and configuration.

Planned build-management concepts include configurable environments, project-specific tool versions, build configuration, organized outputs, diagnostics, and actionable error reporting. The envisioned flow is **Settings → Build Tools → choose a compatible tool version → configure the environment → start a build**. Compatibility must be established through testing; universal or error-free build support is not promised.

## Android Tools

**Goal:** Provide an accessible home for relevant Android development workflows. The exact tools, integrations, and supported Android project formats remain to be determined.

## Application Signing

**Goal:** Help developers configure and review Android application signing workflows.

Potential areas include APK signing, keystore configuration, signature verification, output management, and Android signing schemes supported by the eventual toolchain. Signing depends on project configuration and tool support. Keystores and signing credentials must be protected and must never be published in source control.

## Login UI Injection

**Goal:** Support controlled customization of login-screen UI resources for projects that are explicitly supported.

A future workflow may import a design, configure resources, integrate screens, validate dependencies, and leave authentication configuration under developer control. Importing a UI does not create secure authentication or an authentication backend. Developers remain responsible for authentication logic, identity verification, authorization, secure session management, and server-side validation.

## APK Analysis and Decompilation

**Goal:** Help with application inspection and debugging where supported. Potential workflows include:

- APK and package-information inspection.
- Manifest, resource, and project-structure examination.
- Resource management and decompiled-source exploration where supported.
- Analysis and debugging workflows.

Tool support and results may vary. Inspect only applications you own or are authorized to analyze, and respect applicable law, licenses, and privacy obligations.

## Proposed navigation

Project Manager · Build Center · Android Tools · Application Signing · Login UI Injection · APK Analyzer · Decompilation Tools · Build Tools Manager · Settings · About NT MANAGER.

## Availability

These descriptions are a product direction, not a feature-completion checklist. Actual behavior, compatibility, system requirements, and supported workflows will be documented after implementation and testing. Refer to [Releases](../RELEASES.md) for confirmed release information.
