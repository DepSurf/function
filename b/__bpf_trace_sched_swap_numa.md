# Function: <code>__bpf_trace_sched_swap_numa</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba2e0)
Location: include/trace/events/sched.h:516
Inline: False
```
**Symbols:**

```
ffffffff810ba2e0-ffffffff810ba2f0: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c33e0)
Location: include/trace/events/sched.h:531
Inline: False
```
**Symbols:**

```
ffffffff810c33e0-ffffffff810c33f0: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c94e0)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
ffffffff810c94e0-ffffffff810c94f0: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d25b0)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
ffffffff810d25b0-ffffffff810d25c0: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010132ad0)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
ffff800010132ad0-ffff800010132aec: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03821f8)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
c03821f8-c038223c: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017d190)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
c00000000017d190-c00000000017d1c4: __bpf_trace_sched_swap_numa (STB_LOCAL)
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
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc930)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
ffffffff810cc930-ffffffff810cc940: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb130)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
ffffffff810bb130-ffffffff810bb140: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbe50)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
ffffffff810cbe50-ffffffff810cbe60: __bpf_trace_sched_swap_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_sched_swap_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d43b0)
Location: include/trace/events/sched.h:538
Inline: False
```
**Symbols:**

```
ffffffff810d43b0-ffffffff810d43c0: __bpf_trace_sched_swap_numa (STB_LOCAL)
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
