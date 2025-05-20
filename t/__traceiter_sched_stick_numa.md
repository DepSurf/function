# Function: <code>__traceiter_sched_stick_numa</code>

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
int __traceiter_sched_stick_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6720)
Location: include/trace/events/sched.h:650
Inline: False
```
**Symbols:**

```
ffffffff810d6720-ffffffff810d677b: __traceiter_sched_stick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sched_stick_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d83f0)
Location: include/trace/events/sched.h:650
Inline: False
```
**Symbols:**

```
ffffffff810d83f0-ffffffff810d8449: __traceiter_sched_stick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sched_stick_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ebc80)
Location: include/trace/events/sched.h:648
Inline: False
```
**Symbols:**

```
ffffffff810ebc80-ffffffff810ebcd9: __traceiter_sched_stick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sched_stick_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81106d30)
Location: include/trace/events/sched.h:651
Inline: False
```
**Symbols:**

```
ffffffff81106d30-ffffffff81106d98: __traceiter_sched_stick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sched_stick_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112cb80)
Location: include/trace/events/sched.h:651
Inline: False
```
**Symbols:**

```
ffffffff8112cb80-ffffffff8112cbe8: __traceiter_sched_stick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sched_stick_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81139dc0)
Location: include/trace/events/sched.h:651
Inline: False
```
**Symbols:**

```
ffffffff81139dc0-ffffffff81139e28: __traceiter_sched_stick_numa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sched_stick_numa(void *__data, struct task_struct *src_tsk, int src_cpu, struct task_struct *dst_tsk, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144b90)
Location: include/trace/events/sched.h:648
Inline: False
```
**Symbols:**

```
ffffffff81144b90-ffffffff81144bf8: __traceiter_sched_stick_numa (STB_GLOBAL)
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
