# Function: <code>cpuset_force_rebuild</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811303f0)
Location: kernel/cgroup/cpuset.c:2265
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff811303f0-ffffffff81130402: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113d330)
Location: kernel/cgroup/cpuset.c:2275
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8113d330-ffffffff8113d342: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8114bc50)
Location: kernel/cgroup/cpuset.c:2276
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8114bc50-ffffffff8114bc62: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81157cf7)
Location: kernel/cgroup/cpuset.c:2960
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff811588a0-ffffffff811588b2: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811628b5)
Location: kernel/cgroup/cpuset.c:2915
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81164f60-ffffffff81164f72: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116e5cd)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81170e40-ffffffff81170e52: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811821cc)
Location: kernel/cgroup/cpuset.c:3005
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81182b10-ffffffff81182b22: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117f0ec)
Location: kernel/cgroup/cpuset.c:3028
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8117fa60-ffffffff8117fa72: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117f3ab)
Location: kernel/cgroup/cpuset.c:3028
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81180540-ffffffff81180552: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a756e)
Location: kernel/cgroup/cpuset.c:3085
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff811a8300-ffffffff811a8312: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d860f)
Location: kernel/cgroup/cpuset.c:3125
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff811d9430-ffffffff811d9446: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121d86f)
Location: kernel/cgroup/cpuset.c:3399
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8121e6f0-ffffffff8121e706: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff812338da)
Location: kernel/cgroup/cpuset.c:3588
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff812347e0-ffffffff812347f6: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8124d927)
Location: kernel/cgroup/cpuset.c:4418
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8124e400-ffffffff8124e416: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e2770)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffff8000101e4390-ffff8000101e43b4: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0424c40)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
c0425340-c0425368: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000250ebc)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
c000000000254b00-c000000000254b20: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe0001594ac)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffe00015a738-ffffffe00015a75c: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81166bed)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81169460-ffffffff81169472: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81159e21)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8115c660-ffffffff8115c672: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811649bd)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81167230-ffffffff81167242: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpuset_force_rebuild();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81171e56)
Location: kernel/cgroup/cpuset.c:3003
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81174870-ffffffff81174882: cpuset_force_rebuild (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
