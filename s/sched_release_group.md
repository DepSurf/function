# Function: <code>sched_release_group</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sched_release_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ef86d)
Location: kernel/sched/core.c:9794
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
ffffffff810fdd40-ffffffff810fddb0: sched_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sched_release_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110cadd)
Location: kernel/sched/core.c:10117
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_exit
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
**Symbols:**

```
ffffffff8111a7a0-ffffffff8111a81e: sched_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sched_release_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811330bd)
Location: kernel/sched/core.c:10297
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_exit
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
**Symbols:**

```
ffffffff81142080-ffffffff811420fe: sched_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sched_release_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811416ed)
Location: kernel/sched/core.c:10441
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_exit
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
**Symbols:**

```
ffffffff8114dd50-ffffffff8114ddce: sched_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sched_release_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114ca6d)
Location: kernel/sched/core.c:10405
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_exit
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
**Symbols:**

```
ffffffff81159b60-ffffffff81159bde: sched_release_group (STB_GLOBAL)
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
