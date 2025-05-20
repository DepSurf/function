# Function: <code>__traceiter_sched_move_numa</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_sched_move_numa(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d66c0)
Location: include/trace/events/sched.h:578
Inline: False
```
**Symbols:**

```
ffffffff810d66c0-ffffffff810d6711: __traceiter_sched_move_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sched_move_numa(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d83a0)
Location: include/trace/events/sched.h:578
Inline: False
```
**Symbols:**

```
ffffffff810d83a0-ffffffff810d83ef: __traceiter_sched_move_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sched_move_numa(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ebc30)
Location: include/trace/events/sched.h:576
Inline: False
```
**Symbols:**

```
ffffffff810ebc30-ffffffff810ebc7f: __traceiter_sched_move_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sched_move_numa(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81106cd0)
Location: include/trace/events/sched.h:579
Inline: False
```
**Symbols:**

```
ffffffff81106cd0-ffffffff81106d2b: __traceiter_sched_move_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sched_move_numa(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112cb10)
Location: include/trace/events/sched.h:579
Inline: False
```
**Symbols:**

```
ffffffff8112cb10-ffffffff8112cb6b: __traceiter_sched_move_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sched_move_numa(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81139d30)
Location: include/trace/events/sched.h:579
Inline: False
```
**Symbols:**

```
ffffffff81139d30-ffffffff81139d8b: __traceiter_sched_move_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sched_move_numa(void *__data, struct task_struct *tsk, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144b00)
Location: include/trace/events/sched.h:576
Inline: False
```
**Symbols:**

```
ffffffff81144b00-ffffffff81144b5b: __traceiter_sched_move_numa (STB_GLOBAL)
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
