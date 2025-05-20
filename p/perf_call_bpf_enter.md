# Function: <code>perf_call_bpf_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81187cfc)
Location: kernel/trace/trace_syscalls.c:563
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8119736e)
Location: kernel/trace/trace_syscalls.c:563
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a54e1)
Location: kernel/trace/trace_syscalls.c:563
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b2be0)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811b2be0-ffffffff811b2c3e: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811be010)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811be010-ffffffff811be06e: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811d7650)
Location: kernel/trace/trace_syscalls.c:574
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811d7650-ffffffff811d76b6: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811d4720)
Location: kernel/trace/trace_syscalls.c:574
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811d4720-ffffffff811d4786: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811d5db0)
Location: kernel/trace/trace_syscalls.c:570
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811d5db0-ffffffff811d5e16: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81202b60)
Location: kernel/trace/trace_syscalls.c:568
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff81202b60-ffffffff81202c00: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8123e330)
Location: kernel/trace/trace_syscalls.c:555
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff8123e330-ffffffff8123e3e2: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8128bd00)
Location: kernel/trace/trace_syscalls.c:553
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff8128bd00-ffffffff8128bdb2: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812a8c10)
Location: kernel/trace/trace_syscalls.c:553
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff812a8c10-ffffffff812a8cc2: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812c4920)
Location: kernel/trace/trace_syscalls.c:553
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff812c4920-ffffffff812c49d1: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffff80001023d348)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffff80001023d348-ffff80001023d3d0: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c04791ec)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (c0000000002cd070)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
c0000000002cd070-c0000000002cd10c: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b6630)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811b6630-ffffffff811b668e: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a9430)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811a9430-ffffffff811a948e: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b4400)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811b4400-ffffffff811b445e: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811c24a0)
Location: kernel/trace/trace_syscalls.c:565
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
```
**Symbols:**

```
ffffffff811c24a0-ffffffff811c24fe: perf_call_bpf_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
