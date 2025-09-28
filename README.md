# Dev Container

This repository contains a pre-built dev container image for use with Visual Studio Code. It is designed to provide a consistent development environment for working on projects that require specific dependencies and configurations.

## Images

Below are the available dev container images:

| Image Name | Description |
|------------|-------------|
| `base` | A minimal base image with essential tools and libraries. |
| `bun` | An image with Bun.js pre-installed for JavaScript and TypeScript development. |
| `go` | An image with Go programming language pre-installed for Go development. |
| `node` | An image with Node.js pre-installed for JavaScript development. |
| `rust` | An image with Rust programming language pre-installed for Rust development. |
| `svelte` | An image with Bun.js and Svelte tools pre-installed for Svelte development. |

## Usage

To use one of the dev container images, you can specify the image in your `.devcontainer/devcontainer.json` file. For example, to use the `node` image, your configuration would look like this:

```json
{
  "name": "Node Dev Container",
  "image": "ghcr.io/sansathan/devcontainer-node:latest",
}
```

You can replace `node` with any of the other available images as needed.
