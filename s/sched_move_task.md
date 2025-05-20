# Function: <code>sched_move_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0600)
Location: kernel/sched/core.c:7774
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810b0600-ffffffff810b080c: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b31f0)
Location: kernel/sched/core.c:7826
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810b31f0-ffffffff810b330e: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b97e0)
Location: kernel/sched/core.c:7979
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810b97e0-ffffffff810b9954: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b43c0)
Location: kernel/sched/core.c:6193
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810b43c0-ffffffff810b4512: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb670)
Location: kernel/sched/core.c:6261
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810bb670-ffffffff810bb7ea: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2b20)
Location: kernel/sched/core.c:6381
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810c2b20-ffffffff810c2c81: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbe20)
Location: kernel/sched/core.c:6362
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810cbe20-ffffffff810cbf71: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3ec0)
Location: kernel/sched/core.c:6837
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810d3ec0-ffffffff810d43d5: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de3e0)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810de3e0-ffffffff810de9e3: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e69a0)
Location: kernel/sched/core.c:7274
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810e69a0-ffffffff810e6ba7: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e48a0)
Location: kernel/sched/core.c:8239
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810e48a0-ffffffff810e4ac0: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6860)
Location: kernel/sched/core.c:8608
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810e6860-ffffffff810e6a80: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fddb0)
Location: kernel/sched/core.c:9846
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810fddb0-ffffffff810fe02b: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8111a820)
Location: kernel/sched/core.c:10169
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff8111a820-ffffffff8111aaa2: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81142110)
Location: kernel/sched/core.c:10349
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff81142110-ffffffff81142433: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114dde0)
Location: kernel/sched/core.c:10499
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff8114dde0-ffffffff8114e14a: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81159bf0)
Location: kernel/sched/core.c:10463
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff81159bf0-ffffffff81159f8c: sched_move_task (STB_GLOBAL)
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
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013df70)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffff80001013df70-ffff80001013e100: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038de28)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
c038de28-c038e434: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018cf50)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
c00000000018cf50-c00000000018d65c: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000eccba)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffe0000eccba-ffffffe0000ece20: sched_move_task (STB_GLOBAL)
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
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d85d0)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810d85d0-ffffffff810d8bd5: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6fe0)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810c6fe0-ffffffff810c75e3: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4d80)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810d4d80-ffffffff810d4f14: sched_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_move_task(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e01b0)
Location: kernel/sched/core.c:7040
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:sched_autogroup_exit_task
```
**Symbols:**

```
ffffffff810e01b0-ffffffff810e07b3: sched_move_task (STB_GLOBAL)
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
