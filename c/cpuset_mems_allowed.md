# Function: <code>cpuset_mems_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111d660)
Location: kernel/cpuset.c:2449
Inline: False
Direct callers:
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/mempolicy.c:__mpol_dup
  - mm/migrate.c:SyS_move_pages
```
**Symbols:**

```
ffffffff8111d660-ffffffff8111d6d6: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81125500)
Location: kernel/cpuset.c:2470
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
```
**Symbols:**

```
ffffffff81125500-ffffffff81125576: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112ee60)
Location: kernel/cpuset.c:2470
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
```
**Symbols:**

```
ffffffff8112ee60-ffffffff8112ef6f: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811304f0)
Location: kernel/cgroup/cpuset.c:2470
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
```
**Symbols:**

```
ffffffff811304f0-ffffffff811305fe: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113d420)
Location: kernel/cgroup/cpuset.c:2474
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
```
**Symbols:**

```
ffffffff8113d420-ffffffff8113d52e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8114bd40)
Location: kernel/cgroup/cpuset.c:2475
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8114bd40-ffffffff8114be4e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81158990)
Location: kernel/cgroup/cpuset.c:3283
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81158990-ffffffff81158a9e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81165070)
Location: kernel/cgroup/cpuset.c:3251
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81165070-ffffffff8116518e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81170f50)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81170f50-ffffffff8117106e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81182c20)
Location: kernel/cgroup/cpuset.c:3341
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81182c20-ffffffff81182d7c: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117fb70)
Location: kernel/cgroup/cpuset.c:3364
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff8117fb70-ffffffff8117fcd1: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81180650)
Location: kernel/cgroup/cpuset.c:3364
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff81180650-ffffffff811807b1: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a8440)
Location: kernel/cgroup/cpuset.c:3446
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff811a8440-ffffffff811a85a1: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d9590)
Location: kernel/cgroup/cpuset.c:3492
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff811d9590-ffffffff811d9717: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121e990)
Location: kernel/cgroup/cpuset.c:3797
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff8121e990-ffffffff8121eb17: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81234a80)
Location: kernel/cgroup/cpuset.c:3989
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff81234a80-ffffffff81234c07: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8124e6a0)
Location: kernel/cgroup/cpuset.c:4830
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:find_mm_struct
```
**Symbols:**

```
ffffffff8124e6a0-ffffffff8124e827: cpuset_mems_allowed (STB_GLOBAL)
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
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e4540)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffff8000101e4540-ffff8000101e4628: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0425470)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
```
**Symbols:**

```
c0425470-c04254f4: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c000000000254cd0)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
c000000000254cd0-c000000000254da8: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe00015a87e)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
```
**Symbols:**

```
ffffffe00015a87e-ffffffe00015a8e0: cpuset_mems_allowed (STB_GLOBAL)
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
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81169570)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81169570-ffffffff8116968e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8115c770)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8115c770-ffffffff8115c88e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81167340)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81167340-ffffffff8116745e: cpuset_mems_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
nodemask_t cpuset_mems_allowed(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811749a0)
Location: kernel/cgroup/cpuset.c:3339
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff811749a0-ffffffff81174ac8: cpuset_mems_allowed (STB_GLOBAL)
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
