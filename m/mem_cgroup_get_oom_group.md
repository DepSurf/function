# Function: <code>mem_cgroup_get_oom_group</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81299ec0)
Location: mm/memcontrol.c:1812
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81299ec0-ffffffff81299f48: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5180)
Location: mm/memcontrol.c:2013
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812b5180-ffffffff812b520f: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6c70)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812c6c70-ffffffff812c6cff: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc410)
Location: mm/memcontrol.c:1895
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812fc410-ffffffff812fc513: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308620)
Location: mm/memcontrol.c:2084
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81308620-ffffffff81308743: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130eda0)
Location: mm/memcontrol.c:1907
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8130eda0-ffffffff8130eec3: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1959
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81cc2ac2-ffffffff81cc2ad7: mem_cgroup_get_oom_group.cold (STB_LOCAL)
ffffffff81359c10-ffffffff81359d4f: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1968
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81e7503f-ffffffff81e75054: mem_cgroup_get_oom_group.cold (STB_LOCAL)
ffffffff813d1c80-ffffffff813d1dee: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2028
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff820681c7-ffffffff820681dc: mem_cgroup_get_oom_group.cold (STB_LOCAL)
ffffffff81457300-ffffffff81457463: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2048
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff820e7ab1-ffffffff820e7ac6: mem_cgroup_get_oom_group.cold (STB_LOCAL)
ffffffff8148cb60-ffffffff8148ccc3: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2120
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff821c47da-ffffffff821c47ef: mem_cgroup_get_oom_group.cold (STB_LOCAL)
ffffffff814bc4a0-ffffffff814bc603: mem_cgroup_get_oom_group (STB_GLOBAL)
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
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103699d0)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffff8000103699d0-ffff800010369abc: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055ad1c)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c055ad1c-c055ae28: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000458440)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c000000000458440-c000000000458580: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002472a2)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffe0002472a2-ffffffe000247368: mem_cgroup_get_oom_group (STB_GLOBAL)
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
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf250)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812bf250-ffffffff812bf2df: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0340)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812b0340-ffffffff812b03cf: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd060)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812bd060-ffffffff812bd0ef: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_get_oom_group(struct task_struct *victim, struct mem_cgroup *oom_domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd860)
Location: mm/memcontrol.c:2029
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812cd860-ffffffff812cd926: mem_cgroup_get_oom_group (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
