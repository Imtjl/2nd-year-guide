# Contributing to the Project

- [RU](#RU)
- [EN](#EN)

<a id="EN"></a>

Thank you for your interest in contributing to this project! Here are some
guidelines to help you get started.

## Markdown Formatting with Prettier

This project uses [Prettier](https://prettier.io/) to automatically format
Markdown files.

## Setup

0. **Fork this repository**

1. **Clone your forked repository:**

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

2. **Install [Bun](https://bun.sh/docs/installation)** (a.k.a. faster npm)

3. **Install dependencies:**

```bash
bun install
```

Now Prettier will automatically format Markdown files on each commit. This is
done using Husky and lint-staged.

If you want to manually use prettier, run:

```bash
bun x prettier --write "**/*.md"
```

Enjoy!
