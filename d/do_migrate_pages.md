# Function: <code>do_migrate_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e1440)
Location: mm/mempolicy.c:988
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:SyS_migrate_pages
```
**Symbols:**

```
ffffffff811e1440-ffffffff811e163a: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ffe30)
Location: mm/mempolicy.c:1020
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:SyS_migrate_pages
```
**Symbols:**

```
ffffffff811ffe30-ffffffff8120001d: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81211950)
Location: mm/mempolicy.c:1022
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:SYSC_migrate_pages
```
**Symbols:**

```
ffffffff81211950-ffffffff81211bd8: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8121bed0)
Location: mm/mempolicy.c:950
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:SYSC_migrate_pages
```
**Symbols:**

```
ffffffff8121b820-ffffffff8121baa0: do_migrate_pages.part.30 (STB_LOCAL)
ffffffff8121d270-ffffffff8121d2af: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81237157)
Location: mm/mempolicy.c:1004
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:SYSC_migrate_pages
```
**Symbols:**

```
ffffffff81236b20-ffffffff81236da0: do_migrate_pages.part.32 (STB_LOCAL)
ffffffff81238460-ffffffff8123849f: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8125a30d)
Location: mm/mempolicy.c:980
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff81259af0-ffffffff81259d60: do_migrate_pages.part.35 (STB_LOCAL)
ffffffff8125b9d0-ffffffff8125ba0f: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8126e19d)
Location: mm/mempolicy.c:1020
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff8126db00-ffffffff8126dd70: do_migrate_pages.part.37 (STB_LOCAL)
ffffffff81270290-ffffffff812702cf: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812897e2)
Location: mm/mempolicy.c:1058
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff81289160-ffffffff812893c6: do_migrate_pages.part.0 (STB_LOCAL)
ffffffff8128b8a0-ffffffff8128b8e1: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81299329)
Location: mm/mempolicy.c:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff81298cf0-ffffffff81298f56: do_migrate_pages.part.0 (STB_LOCAL)
ffffffff8129b410-ffffffff8129b451: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812cd49d)
Location: mm/mempolicy.c:1128
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff812cce30-ffffffff812cd0a2: do_migrate_pages.part.0 (STB_LOCAL)
ffffffff812ce6c0-ffffffff812ce701: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d9650)
Location: mm/mempolicy.c:1110
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff812d9650-ffffffff812d9934: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e0ed0)
Location: mm/mempolicy.c:1120
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff812e0ed0-ffffffff812e11b6: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813281a0)
Location: mm/mempolicy.c:1091
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff813281a0-ffffffff81328486: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813973b0)
Location: mm/mempolicy.c:1087
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff813973b0-ffffffff813976c5: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81416f90)
Location: mm/mempolicy.c:1103
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff81416f90-ffffffff8141729c: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144a520)
Location: mm/mempolicy.c:1109
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff8144a520-ffffffff8144a82e: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81483fa0)
Location: mm/mempolicy.c:1067
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff81483fa0-ffffffff81484238: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffff800010337d84)
Location: mm/mempolicy.c:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffff800010337588-ffff800010337820: do_migrate_pages.part.0 (STB_LOCAL)
ffff80001033a2d0-ffff80001033a324: do_migrate_pages (STB_GLOBAL)
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/mempolicy.h:285
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (c000000000412c64)
Location: mm/mempolicy.c:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
c000000000412490-c000000000412774: do_migrate_pages.part.0 (STB_LOCAL)
c000000000414990-c000000000414a30: do_migrate_pages (STB_GLOBAL)
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/mempolicy.h:285
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81291909)
Location: mm/mempolicy.c:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff812912d0-ffffffff81291536: do_migrate_pages.part.0 (STB_LOCAL)
ffffffff812939f0-ffffffff81293a31: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81283589)
Location: mm/mempolicy.c:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff81282f50-ffffffff812831b6: do_migrate_pages.part.0 (STB_LOCAL)
ffffffff81285600-ffffffff81285641: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8128f719)
Location: mm/mempolicy.c:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff8128f0e0-ffffffff8128f346: do_migrate_pages.part.0 (STB_LOCAL)
ffffffff81291800-ffffffff81291841: do_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_migrate_pages(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8129fbc7)
Location: mm/mempolicy.c:1059
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff8129f560-ffffffff8129f7c6: do_migrate_pages.part.0 (STB_LOCAL)
ffffffff812a1610-ffffffff812a1651: do_migrate_pages (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
