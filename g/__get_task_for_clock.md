# Function: <code>__get_task_for_clock</code>

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
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81143130)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
ffffffff81143130-ffffffff8114320c: __get_task_for_clock (STB_LOCAL)
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
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad1f8)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
ffff8000101ad1f8-ffff8000101ad2f0: __get_task_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f818c)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
c03f818c-c03f8290: __get_task_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000211430)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
c000000000211430-c00000000021158c: __get_task_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe000137268)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
ffffffe000137268-ffffffe000137328: __get_task_for_clock (STB_LOCAL)
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
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113b8e0)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
ffffffff8113b8e0-ffffffff8113b9bc: __get_task_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112e2a0)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
ffffffff8112e2a0-ffffffff8112e37c: __get_task_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81139600)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
ffffffff81139600-ffffffff811396dc: __get_task_for_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *__get_task_for_clock(const clockid_t clock, bool getref, bool gettime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811460a0)
Location: kernel/time/posix-cpu-timers.c:88
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres
```
**Symbols:**

```
ffffffff811460a0-ffffffff811461a3: __get_task_for_clock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
