# AI-Powered PR Reviewer

An AI-powered GitHub bot that automatically reviews pull requests, detects logic, style, and security issues, and posts contextual feedback directly on the PR.

This project simulates a **real-world engineering workflow** where AI performs the first-pass code review, reducing the load on senior developers.

---

## Project Overview

### Problem
Engineering teams spend significant time reviewing pull requests for:

- Basic logic issues
- Code style violations
- Security risks
- Simple improvements

This slows down development and consumes senior engineering time.

### Solution
An AI-powered code reviewer that:

1. Detects pull request events
2. Fetches changed code
3. Sends the diff to an AI model
4. Generates review comments
5. Posts feedback directly on the pull request

---

## Key Features

- GitHub webhook integration
- Automatic PR diff analysis
- AI-generated code review
- Logic, style, and security checks
- Automated PR comments

---

## System Architecture

