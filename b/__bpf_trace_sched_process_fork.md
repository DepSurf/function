# Function: <code>__bpf_trace_sched_process_fork</code>

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
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba2c0)
Location: include/trace/events/sched.h:273
Inline: True
```
**Symbols:**

```
ffffffff810ba2c0-ffffffff810ba2cb: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c33c0)
Location: include/trace/events/sched.h:288
Inline: True
```
**Symbols:**

```
ffffffff810c33c0-ffffffff810c33cb: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c94b0)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
ffffffff810c94b0-ffffffff810c94bb: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2580)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
ffffffff810d2580-ffffffff810d258b: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc490)
Location: include/trace/events/sched.h:287
Inline: True
```
**Symbols:**

```
ffffffff810dc490-ffffffff810dc49b: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:371
Inline: False
```
**Symbols:**

```
ffffffff810d97e0-ffffffff810d97eb: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:371
Inline: False
```
**Symbols:**

```
ffffffff810db0a0-ffffffff810db0ab: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:369
Inline: False
```
**Symbols:**

```
ffffffff810eee80-ffffffff810eee8b: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:372
Inline: False
```
**Symbols:**

```
ffffffff8110c020-ffffffff8110c035: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:372
Inline: False
```
**Symbols:**

```
ffffffff81132440-ffffffff81132455: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:372
Inline: False
```
**Symbols:**

```
ffffffff811409f0-ffffffff81140a05: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:372
Inline: False
```
**Symbols:**

```
ffffffff8114bb80-ffffffff8114bb95: __bpf_trace_sched_process_fork (STB_LOCAL)
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
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010132aa0)
Location: include/trace/events/sched.h:287
Inline: True
```
**Symbols:**

```
ffff800010132aa0-ffff800010132ab4: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382188)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
c0382188-c03821b0: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017d100)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
c00000000017d100-c00000000017d12c: __bpf_trace_sched_process_fork (STB_LOCAL)
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
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc900)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
ffffffff810cc900-ffffffff810cc90b: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb100)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
ffffffff810bb100-ffffffff810bb10b: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbe20)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
ffffffff810cbe20-ffffffff810cbe2b: __bpf_trace_sched_process_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_sched_process_fork(void *__data, struct task_struct *parent, struct task_struct *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4380)
Location: include/trace/events/sched.h:287
Inline: False
```
**Symbols:**

```
ffffffff810d4380-ffffffff810d438b: __bpf_trace_sched_process_fork (STB_LOCAL)
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
