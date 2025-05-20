# Function: <code>check_thread_timers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f3914)
Location: kernel/time/posix-cpu-timers.c:858
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810faa54)
Location: kernel/time/posix-cpu-timers.c:828
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811083d4)
Location: kernel/time/posix-cpu-timers.c:824
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8110a658)
Location: kernel/time/posix-cpu-timers.c:798
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81115808)
Location: kernel/time/posix-cpu-timers.c:799
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81121fc2)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112d6e2)
Location: kernel/time/posix-cpu-timers.c:808
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811380e5)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811441c5)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_thread_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81153330-ffffffff8115349b: check_thread_timers (STB_LOCAL)
ffffffff81153f4a-ffffffff81153fb6: check_thread_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void check_thread_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:831
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:handle_posix_cpu_timers
```
**Symbols:**

```
ffffffff8114f5f0-ffffffff8114f75b: check_thread_timers (STB_LOCAL)
ffffffff81be3a7b-ffffffff81be3ae7: check_thread_timers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81150cb6)
Location: kernel/time/posix-cpu-timers.c:831
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81175086)
Location: kernel/time/posix-cpu-timers.c:889
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811aa33e)
Location: kernel/time/posix-cpu-timers.c:896
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea35e)
Location: kernel/time/posix-cpu-timers.c:896
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fea7e)
Location: kernel/time/posix-cpu-timers.c:897
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void check_thread_timers(struct task_struct *tsk, struct list_head *firing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:897
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
**Symbols:**

```
ffffffff81214a00-ffffffff81214c5e: check_thread_timers (STB_LOCAL)
ffffffff821b5cc7-ffffffff821b5cdc: check_thread_timers.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ae750)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f97f4)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000212d00)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe0001381e0)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113c975)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112f3e5)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113a695)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81147155)
Location: kernel/time/posix-cpu-timers.c:826
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
