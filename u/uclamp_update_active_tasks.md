# Function: <code>uclamp_update_active_tasks</code>

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
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4e50)
Location: kernel/sched/core.c:1078
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810d4e50-ffffffff810d52ff: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df7c0)
Location: kernel/sched/core.c:1144
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810df7c0-ffffffff810df8d7: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcab0)
Location: kernel/sched/core.c:1303
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810dcab0-ffffffff810dcbc7: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de680)
Location: kernel/sched/core.c:1319
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810de680-ffffffff810de784: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f3510)
Location: kernel/sched/core.c:1686
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810f3510-ffffffff810f361a: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110f530)
Location: kernel/sched/core.c:1729
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff8110f530-ffffffff8110f665: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81136390)
Location: kernel/sched/core.c:1717
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff81136390-ffffffff811364c5: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811453c0)
Location: kernel/sched/core.c:1739
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff811453c0-ffffffff8114550d: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811508e0)
Location: kernel/sched/core.c:1780
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff811508e0-ffffffff81150a2d: uclamp_update_active_tasks (STB_LOCAL)
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
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010135a28)
Location: kernel/sched/core.c:1078
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffff800010135a28-ffff800010135e30: uclamp_update_active_tasks (STB_LOCAL)
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
In kernel/sched/core.c (c0384ad8)
Location: kernel/sched/core.c:1078
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000180820)
Location: kernel/sched/core.c:1078
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
c000000000180820-c000000000180db8: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf140)
Location: kernel/sched/core.c:1078
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810cf140-ffffffff810cf5f1: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bda10)
Location: kernel/sched/core.c:1078
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810bda10-ffffffff810bdebf: uclamp_update_active_tasks (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uclamp_update_active_tasks(struct cgroup_subsys_state *css, unsigned int clamps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6cd0)
Location: kernel/sched/core.c:1078
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
```
**Symbols:**

```
ffffffff810d6cd0-ffffffff810d715b: uclamp_update_active_tasks (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int clamps</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
