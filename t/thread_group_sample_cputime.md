# Function: <code>thread_group_sample_cputime</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81144020)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81144020-ffffffff81144064: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81153ae0)
Location: kernel/time/posix-cpu-timers.c:267
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81153ae0-ffffffff81153b24: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114ff50)
Location: kernel/time/posix-cpu-timers.c:267
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff8114ff50-ffffffff8114ff94: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81151380)
Location: kernel/time/posix-cpu-timers.c:267
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81151380-ffffffff811513c4: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81175750)
Location: kernel/time/posix-cpu-timers.c:267
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81175750-ffffffff81175794: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811aa6c0)
Location: kernel/time/posix-cpu-timers.c:274
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff811aa6c0-ffffffff811aa712: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea770)
Location: kernel/time/posix-cpu-timers.c:274
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff811ea770-ffffffff811ea7c2: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811feea0)
Location: kernel/time/posix-cpu-timers.c:273
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff811feea0-ffffffff811feef2: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81215220)
Location: kernel/time/posix-cpu-timers.c:273
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81215220-ffffffff81215272: thread_group_sample_cputime (STB_GLOBAL)
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
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ae590)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffff8000101ae590-ffff8000101ae5e4: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f958c)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
c03f958c-c03f9618: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000212b20)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
c000000000212b20-c000000000212b84: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013807c)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffe00013807c-ffffffe0001380c2: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113c7d0)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff8113c7d0-ffffffff8113c814: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112f270)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff8112f270-ffffffff8112f2b4: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113a4f0)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff8113a4f0-ffffffff8113a534: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void thread_group_sample_cputime(struct task_struct *tsk, u64 *samples);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81146fb0)
Location: kernel/time/posix-cpu-timers.c:277
Inline: False
Direct callers:
  - kernel/time/itimer.c:get_cpu_itimer
```
**Symbols:**

```
ffffffff81146fb0-ffffffff81146ff4: thread_group_sample_cputime (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
