# Build Guide

## Current build status

There is no application source code or build configuration in this repository, so NT MANAGER itself cannot currently be built from this checkout. No language, framework, SDK version, build command, or output artifact has been established. The project is currently documentation-only.

## Intended project build workflow

The product vision includes a guided build workflow for supported projects. A future implementation is intended to help a developer:

1. Open a project and review its existing build configuration.
2. Identify the build tools and versions required by that project.
3. Select compatible tools through **Settings → Build Tools** where that workflow is supported.
4. Review environment settings and project-specific configuration before building.
5. Start the build and inspect diagnostics, errors, and organized output.

This describes a proposed workflow, not an available feature. Compatibility depends on the target project, dependencies, toolchain, platform, and configuration. Builds are not guaranteed to succeed, and VS Code use alone does not determine a project's build system.

## Signing and APK analysis

Signing instructions, supported Android signing schemes, secure keystore handling, APK inspection tools, and decompilation capabilities will be documented only after the relevant implementation and supported toolchain are known. Test signing workflows with non-production credentials. Do not commit keystores, passwords, signing properties, private application data, or other secrets.

Only analyze APKs you own or are authorized to inspect.
