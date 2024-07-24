# Bun Crash Course | JavaScript Runtime, Bundler & Transpiler

- JavaScript Runtime & Toolkit

* <https://www.youtube.com/watch?v=U4JVw8K19uY>
* <https://bun.sh/>

* What Is Bun?

  - A JavaScript runtime built from scratch to serve the modern JavaScript ecosystem.
  - Includes a native bundler, transpiler, task runner and npm client.
  - Written in the Zig programming language
  - Drop-In replacement for Node.js/Fully compatible with Node APIs

* 3 Major Design Goals

  1. Speed
     - Faster than Node and Deno
     - Extends the JavaScriptCore Engine
     - Little Dependencies
  2. Elegant APIs
     - Minimal set of highly optimized APIs for performing common tasks.
  3. Cohesive DX
     - Complete toolkit for both server-side and frontend

* Features and Advantages

  - Speed and Performance
  - Drop-In Node Compatiblity
  - Works With node_modules
  - Native NPM Client
  - No Module Madness
  - Web-Standard APIs
  - TypeScript Out of the Box
  - JSX
  - Watch Mode
  - Environment Variables
  - Integrated Bundler
  - SQLite Database

* Installation

  - Windows users need to use WSL
  - Install via CURL

  ```bash
  curl -fsSL https://bun.sh/install.sh | bash
  ```

  - Install via NPM

  ```bash
  npm install -g bun
  ```

  ```bash
  bun init
  ```

  ```bash
  bun run index.ts
  ```

  ```bash
  bun --watch index.ts
  ```

  ```bash
  bun --hot index.ts
  ```

  ```bash
  bunx cowsay Hello Bun
  ```

  ```bash
  bun test
  ```

  ```bash
  bun install axios
  ```

  ```bash
  bun build ./src/index.ts --outfile=./dist/bundle.js
  ```

  ```bash
  bun build ./src/index.ts --outfile=./dist/bundle.js --watch
  ```

  ```bash
   bun install react react-dom
  ```
