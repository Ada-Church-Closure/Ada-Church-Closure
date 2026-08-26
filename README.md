<p align="center">
  <a href="https://github.com/denvercoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&pause=1000&color=000000&width=500&lines=My+Heart+Is+In+The+Work!" alt="Typing SVG" />
  </a>
</p>

**Status**  : CS Undergrad · Member of [valkey-io](https://github.com/valkey-io).

**Focus** : Systems Infrastructure, Distributed Protocols, and Low-Level Software/Hardware.

**Spoken**  : Fluent in English & Japanese, I love learning different languages.

**Ethos**   : Play the long game. Do the hard, right things.

### Linux Kernel Work

- [`bpf: Annotate bpf_obj_memcpy with data_race`](https://lore.kernel.org/bpf/20260822-bpf-kcsan-obj-memcpy-v3-1-4227b2edd8b4@proton.me/) — Addressed a syzbot KCSAN report by annotating intentional concurrent writes in lockless BPF map-value updates. **Merged into [`bpf-next`](https://git.kernel.org/bpf/bpf-next/c/5e289c5a4a52)**.
- [`rhashtable` / `TP-BPF lockdep investigation and test`](https://lore.kernel.org/all/20260803-fix-lock-tracepoint-bpf-lockdep-v1-1-91fb7afb526a@gmail.com/)
  — Investigated a syzbot report, proposed an RFC, analyzed BPF locking contexts,
  and validated the revised fix with `PROVE_LOCKING` and the reproducer.

### Recent Merged PRs

<!-- BEGIN_RECENT_PRS -->
- [Fix flaky multi-part AOF manifest tests](https://github.com/valkey-io/valkey/pull/4491) in **valkey-io/valkey**
- [Skip IO-thread write-done client re-lookup unless update_state sync-invokes handlers (9.0)](https://github.com/valkey-io/valkey/pull/4452) in **valkey-io/valkey**
- [Skip IO-thread read-done followup unless update_state sync-invokes handlers (9.0)](https://github.com/valkey-io/valkey/pull/4414) in **valkey-io/valkey**
- [Skip IO-thread read-done followup unless update_state sync-invokes handlers](https://github.com/valkey-io/valkey/pull/4401) in **valkey-io/valkey**
- [Fix re-entry into processPendingCommandAndInputBuffer on blocked clients](https://github.com/valkey-io/valkey/pull/4376) in **valkey-io/valkey**
- [Fix frozen monotonic clock on unsynchronised TSC hosts](https://github.com/valkey-io/valkey/pull/4346) in **valkey-io/valkey**
- [Fix slow-clocksource check for HW monotonic clock and non-x86 advisories](https://github.com/valkey-io/valkey/pull/4272) in **valkey-io/valkey**
- [Fix RESP3 push frame torn apart on self-publish with copy avoidance](https://github.com/valkey-io/valkey/pull/4253) in **valkey-io/valkey**
- [Fix/ready key blocked client uaf](https://github.com/valkey-io/valkey/pull/4212) in **valkey-io/valkey**
- [Prevent double-free of the module timer when the callback stops it](https://github.com/valkey-io/valkey/pull/4211) in **valkey-io/valkey**
- [Check and reject invalid slot import job names](https://github.com/valkey-io/valkey/pull/4210) in **valkey-io/valkey**
- [Raft Cluster: Implement Non-voting Members](https://github.com/valkey-io/valkey/pull/4094) in **valkey-io/valkey**
- [tests/rdma: add valkey-benchmark --rdma stress for RDMA + IO threads](https://github.com/valkey-io/valkey/pull/4025) in **valkey-io/valkey**
- [[llvm-exegesis] Add did-you-mean hint for unknown opcodes](https://github.com/llvm/llvm-project/pull/203463) in **llvm/llvm-project**
- [Raft Cluster: Implement Pre-Vote protocol to prevent term inflation](https://github.com/valkey-io/valkey/pull/3931) in **valkey-io/valkey**
- [add/CVE-2026-25243 Invalid Memory Access in Redis RESTORE Command May Lead to Remote Code Execution](https://github.com/Unclecheng-li/poc-lab/pull/6) in **Unclecheng-li/poc-lab**
- [add/CVE-2026-27623-valkey-dos](https://github.com/Unclecheng-li/poc-lab/pull/4) in **Unclecheng-li/poc-lab**
- [Fix RDMA + IO threads re-entrancy and busy-loop via connection postpone masks](https://github.com/valkey-io/valkey/pull/3611) in **valkey-io/valkey**
- [valkey-benchmark: centralize RDMA WRITABLE kick via createFileEvent](https://github.com/valkey-io/valkey/pull/3492) in **valkey-io/valkey**
- [Fixes server crash when RDMA benchmark clients disconnect](https://github.com/valkey-io/valkey/pull/3448) in **valkey-io/valkey**
- [Fix RDMA + IO threads re-entrancy via connection postpone masks (9.0)](https://github.com/valkey-io/valkey/pull/3335) in **valkey-io/valkey**
- [Implement runtime dynamic loading for RDMA libraries](https://github.com/valkey-io/libvalkey/pull/284) in **valkey-io/libvalkey**
- [Lazy loading of RDMA libs in CLI/Benchmark when building as module](https://github.com/valkey-io/valkey/pull/3072) in **valkey-io/valkey**
- [enforce 64‑bit off_t regardless of include order; prevent LTO type mismatch (Fixes #2938)](https://github.com/valkey-io/valkey/pull/2943) in **valkey-io/valkey**
- [mysql-proxy: skip admin for no-FROM multi-expression selects; add tests](https://github.com/apache/shardingsphere/pull/37391) in **apache/shardingsphere**
<!-- END_RECENT_PRS -->

![Valkey](https://img.shields.io/badge/Valkey-Contributor-003545?style=for-the-badge&logo=redis&logoColor=white)

![Linux Kernel Contributor](https://img.shields.io/badge/Linux_Kernel-Contributor-E5A50A?style=for-the-badge&logo=linux&logoColor=white)

![LLVM](https://img.shields.io/badge/LLVM-Contributor-000000?style=for-the-badge&logo=llvm&logoColor=white)

![ShardingSphere](https://img.shields.io/badge/Apache_ShardingSphere-Contributor-E16223?style=for-the-badge&logo=apache&logoColor=white)
