# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Setup

This is a Node.js project using:

- **Package Manager**: pnpm (v10.12.1+)
- **Node Version**: v22.16.0 (specified in .node-version)
- **Module Type**: ESM (type: "module" in package.json)

## Development Environment

- **Editor Config**: 2-space indentation, LF line endings, max line length 120, UTF-8 encoding
- **NPM Config**: Uses exact versions (save-prefix="")

## Current State

This is a minimal project setup with no source code, build scripts, or dependencies yet. The package.json contains empty
scripts, dependencies, and devDependencies objects.

## Common Commands

Since no scripts are defined yet, use standard pnpm commands:

- `pnpm install` - Install dependencies
- `pnpm add <package>` - Add dependencies
- `pnpm add -D <package>` - Add dev dependencies

## File Structure

The project currently contains only configuration files:

- Standard Node.js project files (package.json, pnpm-lock.yaml, .node-version)
- Editor configuration (.editorconfig, .npmrc)
- License (MIT) and basic README
- IntelliJ IDEA configuration (waffle.iml)
