# Function: <code>sched_offline_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0530)
Location: kernel/sched/core.c:7754
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_offline
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
```
**Symbols:**

```
ffffffff810b0530-ffffffff810b05ea: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3160)
Location: kernel/sched/core.c:7784
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810b3160-ffffffff810b31d2: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9750)
Location: kernel/sched/core.c:7937
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810b9750-ffffffff810b97c2: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4330)
Location: kernel/sched/core.c:6151
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810b4330-ffffffff810b43a2: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb5e0)
Location: kernel/sched/core.c:6219
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810bb5e0-ffffffff810bb652: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2a90)
Location: kernel/sched/core.c:6339
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810c2a90-ffffffff810c2b02: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbd90)
Location: kernel/sched/core.c:6320
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810cbd90-ffffffff810cbe02: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3e30)
Location: kernel/sched/core.c:6795
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810d3e30-ffffffff810d3ea2: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de350)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810de350-ffffffff810de3c2: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd475)
Location: kernel/sched/core.c:7232
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
Direct callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810e6920-ffffffff810e6995: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9d55)
Location: kernel/sched/core.c:8197
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
Direct callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810e4820-ffffffff810e4895: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db8d5)
Location: kernel/sched/core.c:8566
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
Direct callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810e67e0-ffffffff810e6855: sched_offline_group (STB_GLOBAL)
```
</details>
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
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013de60)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffff80001013de60-ffff80001013df3c: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038dda4)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
**Symbols:**

```
c038dda4-c038de0c: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018ce80)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
c00000000018ce80-c00000000018cf28: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ecc20)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffe0000ecc20-ffffffe0000ecc90: sched_offline_group (STB_GLOBAL)
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
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8540)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810d8540-ffffffff810d85b2: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6f50)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810c6f50-ffffffff810c6fc2: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4cf0)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810d4cf0-ffffffff810d4d62: sched_offline_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_offline_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0120)
Location: kernel/sched/core.c:6998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
**Symbols:**

```
ffffffff810e0120-ffffffff810e0192: sched_offline_group (STB_GLOBAL)
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
