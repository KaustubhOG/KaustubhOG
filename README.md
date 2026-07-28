# Kaustubh Shivarkar

Security researcher finding critical bugs | Contributing to Rust OSS | Rust • Anchor • Web3

---

### Open Source Contributions

**[boa](https://github.com/boa-dev/boa)** — Embeddable JavaScript engine written in Rust.
- Led the `EngineError::Panic` migration — converting internal panics across builtins (array, string, regexp, proxy, promise, typed_array, generator, bigint, eval, intl, vm/opcode, module/source, object) into recoverable errors.
- Built out WinterTC compliance — new `boa_wintertc` crate, migrating `console`, `atob`/`btoa`, `structuredClone`, `queueMicrotask`, timers, and more from `boa_runtime`.
- Implemented safe wrappers: `JsWeakMap`, `JsWeakSet`, `JsAsyncGenerator`, `JsGeneratorFunction`.

**[omniqueue-rs](https://github.com/svix/omniqueue-rs)** — Queue abstraction layer for Rust (Redis, RabbitMQ, SQS, GCP Pub/Sub).
- Expanded test coverage across the in-memory, RabbitMQ, SQS, and GCP Pub/Sub backends.
- Fixed outdated README/doc code snippets and cleaned up backend configuration.

---

### Security Research

[**Security_vuln_Profile**](https://github.com/KaustubhOG/Security_vuln_Profile) — A record of vulnerabilities discovered and responsibly disclosed across live platforms.

```
Severity    Total    Triaged
────────────────────────────
Critical      3         2
High          3         1
Medium        1         0
```

Findings include SQL Injection, Remote Code Execution, OTP Bypass, Reflected XSS, IDOR, and Stack Trace Exposure. Technical details withheld to protect affected systems.

[**CTF_Exclusive**](https://github.com/KaustubhOG/CTF_Exclusive) — Writeups and scripts from CTF competitions including picoCTF and PortSwigger Web Security Academy, covering web exploitation and general security skills.
