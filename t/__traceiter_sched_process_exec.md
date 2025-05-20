# Function: <code>__traceiter_sched_process_exec</code>

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
int __traceiter_sched_process_exec(void *__data, struct task_struct *p, pid_t old_pid, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6430)
Location: include/trace/events/sched.h:399
Inline: False
```
**Symbols:**

```
ffffffff810d6430-ffffffff810d6481: __traceiter_sched_process_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sched_process_exec(void *__data, struct task_struct *p, pid_t old_pid, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8130)
Location: include/trace/events/sched.h:399
Inline: False
```
**Symbols:**

```
ffffffff810d8130-ffffffff810d817f: __traceiter_sched_process_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sched_process_exec(void *__data, struct task_struct *p, pid_t old_pid, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810eb9c0)
Location: include/trace/events/sched.h:397
Inline: False
```
**Symbols:**

```
ffffffff810eb9c0-ffffffff810eba0f: __traceiter_sched_process_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sched_process_exec(void *__data, struct task_struct *p, pid_t old_pid, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81106a30)
Location: include/trace/events/sched.h:400
Inline: False
```
**Symbols:**

```
ffffffff81106a30-ffffffff81106a8b: __traceiter_sched_process_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sched_process_exec(void *__data, struct task_struct *p, pid_t old_pid, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112c7f0)
Location: include/trace/events/sched.h:400
Inline: False
```
**Symbols:**

```
ffffffff8112c7f0-ffffffff8112c84b: __traceiter_sched_process_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sched_process_exec(void *__data, struct task_struct *p, pid_t old_pid, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811399b0)
Location: include/trace/events/sched.h:400
Inline: False
```
**Symbols:**

```
ffffffff811399b0-ffffffff81139a0b: __traceiter_sched_process_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sched_process_exec(void *__data, struct task_struct *p, pid_t old_pid, struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811447b0)
Location: include/trace/events/sched.h:400
Inline: False
```
**Symbols:**

```
ffffffff811447b0-ffffffff8114480b: __traceiter_sched_process_exec (STB_GLOBAL)
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
