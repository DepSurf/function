# Function: <code>__bpf_trace_xdp_cpumap_kthread</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1020)
Location: include/trace/events/xdp.h:162
Inline: True
```
**Symbols:**

```
ffffffff811b1020-ffffffff811b1034: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bf6a0)
Location: include/trace/events/xdp.h:161
Inline: True
```
**Symbols:**

```
ffffffff811bf6a0-ffffffff811bf6b4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811cfc20)
Location: include/trace/events/xdp.h:189
Inline: False
```
**Symbols:**

```
ffffffff811cfc20-ffffffff811cfc34: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dc1c0)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
ffffffff811dc1c0-ffffffff811dc1d4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8d90)
Location: include/trace/events/xdp.h:177
Inline: True
```
**Symbols:**

```
ffffffff811f8d90-ffffffff811f8da4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched, struct xdp_cpumap_stats *xdp_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7df0)
Location: include/trace/events/xdp.h:177
Inline: False
```
**Symbols:**

```
ffffffff811f7df0-ffffffff811f7e04: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched, struct xdp_cpumap_stats *xdp_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8bd0)
Location: include/trace/events/xdp.h:185
Inline: False
```
**Symbols:**

```
ffffffff811f8bd0-ffffffff811f8be4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched, struct xdp_cpumap_stats *xdp_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122a1c0)
Location: include/trace/events/xdp.h:189
Inline: False
```
**Symbols:**

```
ffffffff8122a1c0-ffffffff8122a1d4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched, struct xdp_cpumap_stats *xdp_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126bbe0)
Location: include/trace/events/xdp.h:189
Inline: False
```
**Symbols:**

```
ffffffff8126bbe0-ffffffff8126bc06: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched, struct xdp_cpumap_stats *xdp_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c0df0)
Location: include/trace/events/xdp.h:189
Inline: False
```
**Symbols:**

```
ffffffff812c0df0-ffffffff812c0e16: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched, struct xdp_cpumap_stats *xdp_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e7ba0)
Location: include/trace/events/xdp.h:189
Inline: False
```
**Symbols:**

```
ffffffff812e7ba0-ffffffff812e7bc6: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched, struct xdp_cpumap_stats *xdp_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81305e90)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
ffffffff81305e90-ffffffff81305eb6: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
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
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025c278)
Location: include/trace/events/xdp.h:190
Inline: True
```
**Symbols:**

```
ffff80001025c278-ffff80001025c29c: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0490190)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
c0490190-c04901d4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003011a0)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
c0000000003011a0-c0000000003011d4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d47e0)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
ffffffff811d47e0-ffffffff811d47f4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c75a0)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
ffffffff811c75a0-ffffffff811c75b4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d25b0)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
ffffffff811d25b0-ffffffff811d25c4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_xdp_cpumap_kthread(void *__data, int map_id, unsigned int processed, unsigned int drops, int sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e08a0)
Location: include/trace/events/xdp.h:190
Inline: False
```
**Symbols:**

```
ffffffff811e08a0-ffffffff811e08b4: __bpf_trace_xdp_cpumap_kthread (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_cpumap_stats *xdp_stats</code>
</li>
</ul>
</details>
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
