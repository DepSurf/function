# Function: <code>__bpf_trace_sched_migrate_task</code>

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
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba2b0)
Location: include/trace/events/sched.h:174
Inline: False
```
**Symbols:**

```
ffffffff810ba2b0-ffffffff810ba2bd: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c33b0)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810c33b0-ffffffff810c33bd: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c94a0)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810c94a0-ffffffff810c94ad: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2570)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810d2570-ffffffff810d257d: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc480)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810dc480-ffffffff810dc48d: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8c70)
Location: include/trace/events/sched.h:273
Inline: False
```
**Symbols:**

```
ffffffff810d8c70-ffffffff810d8c7d: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da5e0)
Location: include/trace/events/sched.h:273
Inline: True
```
**Symbols:**

```
ffffffff810da5e0-ffffffff810da5ed: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810edfc0)
Location: include/trace/events/sched.h:271
Inline: True
```
**Symbols:**

```
ffffffff810edfc0-ffffffff810edfcd: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110a6b0)
Location: include/trace/events/sched.h:274
Inline: True
```
**Symbols:**

```
ffffffff8110a6b0-ffffffff8110a6c7: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112f3e0)
Location: include/trace/events/sched.h:274
Inline: True
```
**Symbols:**

```
ffffffff8112f3e0-ffffffff8112f3f7: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ccb0)
Location: include/trace/events/sched.h:274
Inline: True
```
**Symbols:**

```
ffffffff8113ccb0-ffffffff8113ccc7: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81147df0)
Location: include/trace/events/sched.h:274
Inline: True
```
**Symbols:**

```
ffffffff81147df0-ffffffff81147e07: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010132a88)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffff800010132a88-ffff800010132aa0: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382160)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
c0382160-c0382188: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017d0d0)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
c00000000017d0d0-c00000000017d100: __bpf_trace_sched_migrate_task (STB_LOCAL)
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
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc8f0)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810cc8f0-ffffffff810cc8fd: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb0f0)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810bb0f0-ffffffff810bb0fd: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbe10)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810cbe10-ffffffff810cbe1d: __bpf_trace_sched_migrate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_sched_migrate_task(void *__data, struct task_struct *p, int dest_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4370)
Location: include/trace/events/sched.h:189
Inline: False
```
**Symbols:**

```
ffffffff810d4370-ffffffff810d437d: __bpf_trace_sched_migrate_task (STB_LOCAL)
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
