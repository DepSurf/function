# Function: <code>bpf_prog_has_trampoline</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_prog_has_trampoline(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a95a0)
Location: kernel/bpf/trampoline.c:30
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
```
**Symbols:**

```
ffffffff812a95a0-ffffffff812a95df: bpf_prog_has_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_prog_has_trampoline(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308820)
Location: kernel/bpf/trampoline.c:108
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
```
**Symbols:**

```
ffffffff81308820-ffffffff8130885f: bpf_prog_has_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_prog_has_trampoline(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81337740)
Location: kernel/bpf/trampoline.c:107
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
```
**Symbols:**

```
ffffffff81337740-ffffffff8133777f: bpf_prog_has_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_prog_has_trampoline(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135d580)
Location: kernel/bpf/trampoline.c:107
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
```
**Symbols:**

```
ffffffff8135d580-ffffffff8135d5bf: bpf_prog_has_trampoline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
