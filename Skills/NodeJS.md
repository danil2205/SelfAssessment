## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js: 🎓 known
  - Stateful and stateless servers: 🖐️ used
  - Nonblocking I/O and blocking code
  - Event loop phases: 👂 heard
  - Event loop microtasks and macrotasks: 👂 heard
  - Garbage collection: 🎓 known
  - Node.js LTS schedule: 🎓 known
  - I/O-bound, CPU-bound, memory-bound tasks: 👂 heard
  - Interactive applications (close to real-time)
- Modularity, layers and dependencies
  - CommonJS modules: 🖐️ used
  - ECMAScript modules: 🖐️ used
  - Module `node:module`: 🖐️ used
  - Caching in CJS and ESM
  - Modules as singletons
  - Contexts and scripts module `node:vm`
  - Dependencies: `npm`, `node_modules`: 🖐️ used
  - Files `package.json`, `package-lock.json`: 🖐️ used
  - Module-based permissions model
  - Isolation with modularity
  - Dependency injection: 🖐️ used
  - DI containers
  - Coupling and cohesion
  - Framework agnostic approach
- Environment
  - Command line arguments: 🖐️ used
  - Node.js CLI
  - Process-based permissions
  - Graceful shutdown
  - Clustering: 👂 heard
  - Watch filesystem changes with --watch
- Internal API
  - Streams API: 👂 heard
  - Web Streams API
  - Crypto API: 🎓 known
  - Password hashing with crypto.scrypt: 🎓 known
  - Web Crypto API: 🎓 known
  - File system API (sync and async)
  - Copy folder recursively
  - Worker threads: 👂 heard
  - Performance hooks
  - Native fetch and nodejs/undici
  - async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - SharedArrayBuffer
  - Module `node:worker_threads`: 👂 heard
  - Module `node:child_process`: 👂 heard
  - MessageChannel, MessagePort: 👂 heard
  - BroadcastChannel: 👂 heard
  - Generating crypto random UUID: 🎓 known
  - Module `node:url` vs `new URL`
  - Module `node:assert`: 🖐️ used
  - Internationalization
  - Blob, File, Buffer, module `node:buffer`: 👂 heard
  - Module `node:zlib`
- Network
  - Endpoint throttling
  - ALPN
  - SNI callback
  - SSL certificates: 👂 heard
  - Protocol agnostic approach
  - Fetch API: 🖐️ used
  - IncomingMessage
  - HTTP(S): 👂 heard
  - TCP/SSL: 👂 heard
  - UDP: 👂 heard
  - TLS: 👂 heard
  - Websocket: 👂 heard
  - SSE
  - HTTP/3 (QUIC)
  - Long polling
  - REST: 🎓 known
  - RPC
  - Routing
  - DoS: 👂 heard
  - DDoS: 👂 heard
  - XSS: 🖐️ used
  - Path traversal
  - CSRF: 🖐️ used
  - DNS: 👂 heard
  - SQL injection: 🖐️ used
  - noDelay
  - keep-alive: 👂 heard
  - IP sticky sessions: 👂 heard
- Technique and tools
  - Native test runner
  - Logging: 🖐️ used
  - Application configuring: 🖐️ used
  - Testing: 🖐️ used
  - CI/CD: 🖐️ used
  - Readable: 🖐️ used
  - Writable: 🖐️ used
  - Transform
  - Back pressure
  - Buffer: 👂 heard
  - Console: 🖐️ used
  - Inspector
- Data access
  - Data access layer: 🖐️ used
  - Repository: 🖐️ used
  - Active record
  - Query builder
  - Object-Relational Mapping
  - CRUD: 🖐️ used
  - DTO: 🖐️ used
- Error handling and debugging
  - `Error`: 🖐️ used
  - `error.cause`: 🎓 known
  - `error.code`: 🖐️ used
  - `error.message`: 🖐️ used
  - `error.stack`: 🎓 known
  - `Error.captureStackTrace`: 🎓 known
  - How to avoid mixins
  - Uncaught exceptions: 🖐️ used
  - Heap dump
  - Debugging tools: 🎓 known
  - Flame graph
  - Memory leaks
  - Resource leaks
  - Data race
- Integrations and bindings
  - Native addons
  - `C` and `C++` addons
  - `Rust` addons
  - `Zig` addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI `C` and `C++`
  - NAPI `Rust`
  - NAPI `Zig`
  - Webassembly `WAT`
  - Webassembly `C` and `C++`
  - Webassembly `Rust`
  - Webassembly `Zig`
  - Webassembly `AssemblyScript`
  - Shared memory
  - V8 binary serialization
