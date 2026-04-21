# Contributing to LlamaPen

Thank you for being interested in contributing to LlamaPen. Below are instructions on how to get a development build of LlamaPen running locally.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Download](#download)
- [Running](#running)
- [DX & Tips](#dx--tips)

## Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/downloads)
- [Bun](https://bun.sh/) (1.3+ tested)

Optionally, you may also want to download [Docker](https://www.docker.com/) if you plan on building a docker after your changes.

## Download

First, clone the repo:

```bash
git clone https://github.com/ImDarkTom/LlamaPen
cd LlamaPen
```

Then install dependencies:

```bash
bun install
```

## Running

To start a dev server, run the following command:

```bash
bun dev
```

By default the dev server will be in watch mode, meaning any changes you make will automatically restart the server.

## DX & Tips

This project includes a `.vscode` folder. If you are using VSCode you may want to install the extensions from the `.vscode/extensions.json` file. 
