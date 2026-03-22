## Selected Contributions:

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/66798">[PR #66798] </a>Rewrite: Architectural documentation</strong> </summary>
  <sub>Refactors and clarifies architecture docs for easier onboarding and maintenance.</sub></details>

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/64771">[PR #64771] </a>Check segments prior to mkfs</summary>
    <sub>Converts the SeaStore init path to coroutines up to <code>mkfs</code> and adds a pre‑mkfs segment‑count validation to prevent formatting on invalid device.</sub>
</details>

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/66506">[PR #66506] </a></strong>Verify crc prior to complete_io</summary>
  <sub>Moves CRC verification stage to avoid races where an extent becomes fully loaded after a partial read. <br>With this fix, CRC is only checked when a full load is intended.</sub></details>

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/49594">[PR #49594] </a>Recovery: Partial object support</strong> </summary>
  <sub>Enables partial‑object repair to reduce data movement and speed up recovery.</sub>
</details>

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/61740">[PR #61740] </a>Upgrade clang 14->19</strong> </summary>
  <sub>Pulls Clang 19 via the LLVM installer for the project's CI/builds and prefers it in compiler discovery. <br>This patch unlocks full C++20 support and resolve Clang‑14 build issues.</sub></details>
</details>

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/61637">[PR #61637] </a>CMakeLists: Fallback to RelWithDebInfo</summary>
  <sub>Sets the fallback <code>CMAKE_BUILD_TYPE</code> to <code>RelWithDebInfo</code> when not specified for the Ceph project.</sub>
</details>

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/66229">[PR #66229] </a>ceph.spec.in: Include Crimson by default</summary>
  <sub>Ships Crimson in the default RPM build and manages <code>ceph-osd-classic</code>/<code>ceph-osd-crimson</code> via <code>update-alternatives</code>.<br> Classic remains the default, switching to Crimson is an explicit one‑liner.</sub></details>

<details>
  <summary><a href="https://github.com/ceph/ceph/pull/46419">[PR #46419] </a>Snapshot I/O path (copy‑on‑write)</summary>
  <sub>Implements snapshot‑correct write semantics and clone behavior in Crimson.</sub>
</details>

<details>
<summary><a href="https://github.com/ceph/ceph/pulls?q=is%3Apr+author%3AMatan-B">[All recent PR List] </a></summary>
</details>

---

## Speaking

- **Cephalocon 2025 (Vancouver)** [Re‑Architecting Ceph, One Crimson‑OSD at a Time](https://www.youtube.com/watch?v=up7idfajZgE)
- **Cephalocon 2024 (Geneva)** [Crimson Project Update (Tentacle)](https://www.youtube.com/watch?v=IsV3WWN-YeE)
- **Cephalocon 2023 (Amsterdam)** [From Classical to the Future](https://www.youtube.com/watch?v=8N_1WAEPw0o)
- **Ceph Day London 2024 (Canonical)** [Crimson Project Update (Squid)](https://www.youtube.com/watch?v=QjFliCekAlo)

---

## Code Walkthroughs & Documentation

- [Code Walkthroughs: Crimson](https://www.youtube.com/watch?v=rtkrHk6grsg) Recording
- [Snaps (CLONE_OVERLAP)](https://docs.ceph.com/en/latest/dev/osd_internals/snaps/#clone-overlap)
- [Seastore](https://docs.ceph.com/en/latest/dev/crimson/seastore/)

---

## Blog Posts

- [A Crimson colored Tentacle](https://ceph.io/en/news/blog/2025/crimson-T-release/)
- [Crimson Project Page](https://ceph.io/en/news/crimson/)
- [GSoC 2021](https://matan-b.github.io/2021/08/13/google-summer-of-code-2021-with-Ceph/)

---

## Stats

[![Matan's GitHub stats](https://github-stats-extended.vercel.app/api?username=matan-b&hide=contribs,issues,stars&hide_rank=true&include_all_commits=true&hide_title=true)](https://github.com/stats-organization/github-stats-extended)

