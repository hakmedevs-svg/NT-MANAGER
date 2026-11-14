# Build Guide

## Current build information

An Android package named **`NT.MANAGER.apk`** is attached to the NT MANAGER [GitHub release](https://github.com/hakmedevs-svg/NT-MANAGER/releases/tag/untagged-e141f93576a0dfda6ab3). GitHub currently marks that release as a draft. The repository itself does not contain application source code or build configuration, so the APK cannot be rebuilt from this checkout.

The release currently has no version tag, publication date, build instructions, or verified compatibility information. Refer to the release page or contact the developer for details. Do not infer the APK's build environment or Android requirements from the filename.

## Intended project build workflow

The product vision includes a guided build workflow for supported projects. A future implementation is intended to help a developer:

1. Open a project and review its existing build configuration.
2. Identify the build tools and versions required by that project.
3. Select compatible tools through **Settings → Build Tools** where that workflow is supported.
4. Review environment settings and project-specific configuration before building.
5. Start the build and inspect diagnostics, errors, and organized output.

This describes a proposed workflow, not an available feature verified in this source repository. Compatibility depends on the target project, dependencies, toolchain, platform, and configuration. Builds are not guaranteed to succeed, and VS Code use alone does not determine a project's build system.

## Signing and APK analysis

Signing instructions, supported Android signing schemes, secure keystore handling, APK inspection tools, and decompilation capabilities will be documented only after the relevant implementation and supported toolchain are known. Test signing workflows with non-production credentials. Do not commit keystores, passwords, signing properties, private application data, or other secrets.

Only analyze APKs you own or are authorized to inspect.
