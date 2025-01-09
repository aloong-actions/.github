# Aloong Actions

This organization is a collection of useful GitHub Actions for enhancing your development workflow. These actions are designed to improve security, automation, and team collaboration.

## Available Actions

### [Jenkins Job Trigger](https://github.com/aloong-actions/jenkins-job-trigger)
[![CI](https://github.com/aloong-actions/jenkins-job-trigger/actions/workflows/cicd.yml/badge.svg)](https://github.com/aloong-actions/jenkins-job-trigger/actions/workflows/cicd.yml)

A Go-based action that triggers Jenkins jobs and waits for their completion. This action provides seamless integration between GitHub and Jenkins, making it perfect for CI/CD pipelines that span both platforms.

### [Repo Force Sync](https://github.com/aloong-actions/repo-force-sync-action)
A specialized action for synchronizing two independent repositories using force push. It features branch-specific synchronization controlled by a whitelist, making it ideal for maintaining mirror repositories or managing code distribution across multiple repositories.

> ⚠️ **Warning**: This action uses force push which will overwrite the destination branch. Always backup your repository before use.

### [Gitleaks](https://github.com/aloong-actions/gitleaks)
[![CI](https://github.com/aloong-actions/gitleaks/actions/workflows/ci.yml/badge.svg)](https://github.com/aloong-actions/gitleaks/actions/workflows/ci.yml)

A security-focused action that scans your repository for hardcoded secrets using the powerful Gitleaks tool. It helps prevent accidental exposure of sensitive information like API keys, passwords, and tokens in your codebase.

### [Teams Deploy Card](https://github.com/aloong-actions/teams-deploy-card)
[![CI](https://github.com/aloong-actions/teams-deploy-card/actions/workflows/ci.yml/badge.svg)](https://github.com/aloong-actions/teams-deploy-card/actions/workflows/ci.yml)

An enhanced Microsoft Teams notification action that provides comprehensive deployment cards. It improves upon the original ms-teams-deploy-card with better actor detection, improved layout, and additional workflow notifications for committers.

## Getting Started

Each action has its own documentation with detailed usage instructions. Click on the action links above to learn more about their specific features and configuration options.
