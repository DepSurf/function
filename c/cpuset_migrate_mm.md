# Function: <code>cpuset_migrate_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111ba30)
Location: kernel/cpuset.c:1001
Inline: False
Direct callers:
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8111ba30-ffffffff8111bac1: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81123920)
Location: kernel/cpuset.c:1012
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81123920-ffffffff811239b1: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112b490)
Location: kernel/cpuset.c:1012
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8112b490-ffffffff8112b662: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112cad0)
Location: kernel/cgroup/cpuset.c:1015
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8112cad0-ffffffff8112cca2: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81139980)
Location: kernel/cgroup/cpuset.c:1026
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81139980-ffffffff81139b52: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81148160)
Location: kernel/cgroup/cpuset.c:1027
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81148160-ffffffff81148332: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81153d40)
Location: kernel/cgroup/cpuset.c:1550
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81153d40-ffffffff81153f12: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811602a0)
Location: kernel/cgroup/cpuset.c:1511
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811602a0-ffffffff81160463: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116bf70)
Location: kernel/cgroup/cpuset.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8116bf70-ffffffff8116c133: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117d990)
Location: kernel/cgroup/cpuset.c:1587
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8117d990-ffffffff8117db53: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117a7e0)
Location: kernel/cgroup/cpuset.c:1610
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8117a7e0-ffffffff8117a9a3: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117b360)
Location: kernel/cgroup/cpuset.c:1610
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8117b360-ffffffff8117b523: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a4931)
Location: kernel/cgroup/cpuset.c:1656
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811a2eb0-ffffffff811a3073: cpuset_migrate_mm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d5d48)
Location: kernel/cgroup/cpuset.c:1694
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811d3f30-ffffffff811d4109: cpuset_migrate_mm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8121aa50)
Location: kernel/cgroup/cpuset.c:1883
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81217d00-ffffffff81217ed9: cpuset_migrate_mm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81230b38)
Location: kernel/cgroup/cpuset.c:1918
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8122d520-ffffffff8122d6f9: cpuset_migrate_mm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff812495c8)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff812457f0-ffffffff812459f8: cpuset_migrate_mm.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e0278)
Location: kernel/cgroup/cpuset.c:1585
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffff8000101e0278-ffff8000101e0310: cpuset_migrate_mm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c04218e0)
Location: kernel/cgroup/cpuset.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
c04218e0-c0421978: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024f840)
Location: kernel/cgroup/cpuset.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
c00000000024f840-c00000000024f978: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000157130)
Location: kernel/cgroup/cpuset.c:1585
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffe000157130-ffffffe0001571c2: cpuset_migrate_mm.isra.0 (STB_LOCAL)
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
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81164590)
Location: kernel/cgroup/cpuset.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81164590-ffffffff81164753: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811577e0)
Location: kernel/cgroup/cpuset.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811577e0-ffffffff811579a3: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81162360)
Location: kernel/cgroup/cpuset.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81162360-ffffffff81162523: cpuset_migrate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpuset_migrate_mm(struct mm_struct *mm, const nodemask_t *from, const nodemask_t *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116f8e0)
Location: kernel/cgroup/cpuset.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8116f8e0-ffffffff8116faa3: cpuset_migrate_mm (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
