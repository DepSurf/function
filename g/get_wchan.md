# Function: <code>get_wchan</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810397e0)
Location: arch/x86/kernel/process.c:518
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810397e0-ffffffff81039899: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810387d0)
Location: arch/x86/kernel/process.c:521
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810387d0-ffffffff8103888c: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810381e0)
Location: arch/x86/kernel/process.c:484
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810381e0-ffffffff810382ed: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81036350)
Location: arch/x86/kernel/process.c:553
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81036350-ffffffff81036441: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810386e0)
Location: arch/x86/kernel/process.c:585
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810386e0-ffffffff810387d1: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039b90)
Location: arch/x86/kernel/process.c:730
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81039b90-ffffffff81039c82: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103b0f0)
Location: arch/x86/kernel/process.c:794
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8103b0f0-ffffffff8103b1dd: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d6d0)
Location: arch/x86/kernel/process.c:810
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8103d6d0-ffffffff8103d7b5: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103de90)
Location: arch/x86/kernel/process.c:810
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8103de90-ffffffff8103df75: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040f50)
Location: arch/x86/kernel/process.c:917
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81040f50-ffffffff81041043: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040eb0)
Location: arch/x86/kernel/process.c:917
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81040eb0-ffffffff81040fa3: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810428b0)
Location: arch/x86/kernel/process.c:929
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810428b0-ffffffff8104299f: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81048c20)
Location: arch/x86/kernel/process.c:946
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81048c20-ffffffff81048d0c: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81113810)
Location: kernel/sched/core.c:2042
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
```
**Symbols:**

```
ffffffff81113810-ffffffff8111388f: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113a990)
Location: kernel/sched/core.c:2030
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
```
**Symbols:**

```
ffffffff8113a990-ffffffff8113aa0f: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81149d30)
Location: kernel/sched/core.c:2052
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
```
**Symbols:**

```
ffffffff81149d30-ffffffff81149daf: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81155830)
Location: kernel/sched/core.c:2088
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
```
**Symbols:**

```
ffffffff81155830-ffffffff811558af: get_wchan (STB_GLOBAL)
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
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff8000100895c8)
Location: arch/arm64/kernel/process.c:532
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffff8000100895c8-ffff8000100896a8: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030b434)
Location: arch/arm/kernel/process.c:298
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c030b434-c030b528: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c0000000000228c0)
Location: arch/powerpc/kernel/process.c:2015
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c0000000000228c0-c000000000022a74: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/stacktrace.c (ffffffe0000b7370)
Location: arch/riscv/kernel/stacktrace.c:122
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffe0000b7370-ffffffe0000b73c6: get_wchan (STB_GLOBAL)
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
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e010)
Location: arch/x86/kernel/process.c:810
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8103e010-ffffffff8103e0f5: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102d820)
Location: arch/x86/kernel/process.c:810
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8102d820-ffffffff8102d905: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103de50)
Location: arch/x86/kernel/process.c:810
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8103de50-ffffffff8103df35: get_wchan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int get_wchan(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103efb0)
Location: arch/x86/kernel/process.c:810
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8103efb0-ffffffff8103f095: get_wchan (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
</li>
</ul>
</details>
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
