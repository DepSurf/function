# Function: <code>trace_call_bpf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81166fe0)
Location: kernel/trace/bpf_trace.c:32
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
```
**Symbols:**

```
ffffffff81166fe0-ffffffff8116701f: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174400)
Location: kernel/trace/bpf_trace.c:30
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff81174400-ffffffff81174442: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117fe80)
Location: kernel/trace/bpf_trace.c:32
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff8117fe80-ffffffff8117fec2: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182d20)
Location: kernel/trace/bpf_trace.c:32
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff81182d20-ffffffff81182d63: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811907b0)
Location: kernel/trace/bpf_trace.c:34
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811907b0-ffffffff8119082d: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5680)
Location: kernel/trace/bpf_trace.c:40
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811a5680-ffffffff811a56fd: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b37f0)
Location: kernel/trace/bpf_trace.c:74
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811b37f0-ffffffff811b388d: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2540)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811c2540-ffffffff811c2634: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cdcb0)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811cdcb0-ffffffff811cdda4: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ea3c0)
Location: kernel/trace/bpf_trace.c:79
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff811ea3c0-ffffffff811ea4b7: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8390)
Location: kernel/trace/bpf_trace.c:95
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff811e8390-ffffffff811e8481: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9180)
Location: kernel/trace/bpf_trace.c:95
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff811e9180-ffffffff811e926a: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121a5f0)
Location: kernel/trace/bpf_trace.c:95
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff8121a5f0-ffffffff8121a732: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812591e0)
Location: kernel/trace/bpf_trace.c:100
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff812591e0-ffffffff81259341: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a91f0)
Location: kernel/trace/bpf_trace.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff812a91f0-ffffffff812a934e: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cba00)
Location: kernel/trace/bpf_trace.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff812cba00-ffffffff812cbb5c: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e8cc0)
Location: kernel/trace/bpf_trace.c:111
Inline: False
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffffffff812e8cc0-ffffffff812e8e61: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024d518)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/events/core.c:perf_trace_run_bpf_submit
```
**Symbols:**

```
ffff80001024d518-ffff80001024d660: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c04808b4)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
**Symbols:**

```
c04808b4-c0480aa0: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e98f0)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
**Symbols:**

```
c0000000002e98f0-c0000000002e9afc: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/trace_events.h:489
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/trace_events.h:489
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c62d0)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811c62d0-ffffffff811c63c4: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b90b0)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811b90b0-ffffffff811b91a4: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c40a0)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811c40a0-ffffffff811c4194: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int trace_call_bpf(struct trace_event_call *call, void *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d1980)
Location: kernel/trace/bpf_trace.c:79
Inline: True
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
**Symbols:**

```
ffffffff811d1980-ffffffff811d1ab6: trace_call_bpf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_event_call *call</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog *prog</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
