# Function: <code>__bpf_trace_sched_move_task_template</code>

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
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba2a0)
Location: include/trace/events/sched.h:468
Inline: False
```
**Symbols:**

```
ffffffff810ba2a0-ffffffff810ba2af: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c33a0)
Location: include/trace/events/sched.h:483
Inline: False
```
**Symbols:**

```
ffffffff810c33a0-ffffffff810c33af: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9490)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
ffffffff810c9490-ffffffff810c949f: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2560)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
ffffffff810d2560-ffffffff810d256f: __bpf_trace_sched_move_task_template (STB_LOCAL)
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
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010132a68)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
ffff800010132a68-ffff800010132a84: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382128)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
c0382128-c0382160: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017d090)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
c00000000017d090-c00000000017d0c4: __bpf_trace_sched_move_task_template (STB_LOCAL)
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
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc8e0)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
ffffffff810cc8e0-ffffffff810cc8ef: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb0e0)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
ffffffff810bb0e0-ffffffff810bb0ef: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbe00)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
ffffffff810cbe00-ffffffff810cbe0f: __bpf_trace_sched_move_task_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_sched_move_task_template(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4360)
Location: include/trace/events/sched.h:490
Inline: False
```
**Symbols:**

```
ffffffff810d4360-ffffffff810d436f: __bpf_trace_sched_move_task_template (STB_LOCAL)
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
