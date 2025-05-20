# Function: <code>__traceiter_sched_pi_setprio</code>

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
int __traceiter_sched_pi_setprio(void *__data, struct task_struct *tsk, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6630)
Location: include/trace/events/sched.h:527
Inline: False
```
**Symbols:**

```
ffffffff810d6630-ffffffff810d6677: __traceiter_sched_pi_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sched_pi_setprio(void *__data, struct task_struct *tsk, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8310)
Location: include/trace/events/sched.h:527
Inline: False
```
**Symbols:**

```
ffffffff810d8310-ffffffff810d8355: __traceiter_sched_pi_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sched_pi_setprio(void *__data, struct task_struct *tsk, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ebba0)
Location: include/trace/events/sched.h:525
Inline: False
```
**Symbols:**

```
ffffffff810ebba0-ffffffff810ebbe5: __traceiter_sched_pi_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sched_pi_setprio(void *__data, struct task_struct *tsk, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81106c30)
Location: include/trace/events/sched.h:528
Inline: False
```
**Symbols:**

```
ffffffff81106c30-ffffffff81106c7f: __traceiter_sched_pi_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sched_pi_setprio(void *__data, struct task_struct *tsk, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112ca50)
Location: include/trace/events/sched.h:528
Inline: False
```
**Symbols:**

```
ffffffff8112ca50-ffffffff8112ca9f: __traceiter_sched_pi_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sched_pi_setprio(void *__data, struct task_struct *tsk, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81139c70)
Location: include/trace/events/sched.h:528
Inline: False
```
**Symbols:**

```
ffffffff81139c70-ffffffff81139cbf: __traceiter_sched_pi_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sched_pi_setprio(void *__data, struct task_struct *tsk, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144a40)
Location: include/trace/events/sched.h:525
Inline: False
```
**Symbols:**

```
ffffffff81144a40-ffffffff81144a8f: __traceiter_sched_pi_setprio (STB_GLOBAL)
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
