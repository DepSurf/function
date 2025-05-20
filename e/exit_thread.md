# Function: <code>exit_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void exit_thread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039150)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81039150-ffffffff810391e3: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038180)
Location: arch/x86/kernel/process.c:101
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81038180-ffffffff8103820d: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81037c50)
Location: arch/x86/kernel/process.c:84
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81037c50-ffffffff81037cda: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81035d40)
Location: arch/x86/kernel/process.c:93
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81035d40-ffffffff81035dca: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038060)
Location: arch/x86/kernel/process.c:107
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81038060-ffffffff810380ea: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810391d0)
Location: arch/x86/kernel/process.c:107
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff810391d0-ffffffff8103925a: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103a430)
Location: arch/x86/kernel/process.c:110
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8103a430-ffffffff8103a4ba: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103c9f0)
Location: arch/x86/kernel/process.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8103c9f0-ffffffff8103ca7a: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d1b0)
Location: arch/x86/kernel/process.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8103d1b0-ffffffff8103d23a: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040050)
Location: arch/x86/kernel/process.c:102
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81040050-ffffffff81040096: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103ff90)
Location: arch/x86/kernel/process.c:102
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8103ff90-ffffffff8103ffd6: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81041920)
Location: arch/x86/kernel/process.c:97
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81041920-ffffffff81041966: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81047bb0)
Location: arch/x86/kernel/process.c:96
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81047bb0-ffffffff81047bf6: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81050e10)
Location: arch/x86/kernel/process.c:111
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81050e10-ffffffff81050e65: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105e3d0)
Location: arch/x86/kernel/process.c:111
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8105e3d0-ffffffff8105e425: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105fa10)
Location: arch/x86/kernel/process.c:115
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8105fa10-ffffffff8105fa65: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81066b00)
Location: arch/x86/kernel/process.c:116
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81066b00-ffffffff81066b53: exit_thread (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/sched/task.h:82
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched/task.h:82
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030b240)
Location: arch/arm/kernel/process.c:199
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c030b240-c030b26c: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/sched/task.h:82
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched/task.h:82
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/sched/task.h:82
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched/task.h:82
Inline: True
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
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d330)
Location: arch/x86/kernel/process.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8103d330-ffffffff8103d3ba: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102c9e0)
Location: arch/x86/kernel/process.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8102c9e0-ffffffff8102ca6a: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d170)
Location: arch/x86/kernel/process.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8103d170-ffffffff8103d1fa: exit_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void exit_thread(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e210)
Location: arch/x86/kernel/process.c:110
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8103e210-ffffffff8103e2b1: exit_thread (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
