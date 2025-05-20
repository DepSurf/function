# Function: <code>pte_to_pagemap_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812783bd)
Location: fs/proc/task_mmu.c:1064
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812a4e5a)
Location: fs/proc/task_mmu.c:1172
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812ba7bf)
Location: fs/proc/task_mmu.c:1165
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812c8521)
Location: fs/proc/task_mmu.c:1177
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812ec6de)
Location: fs/proc/task_mmu.c:1260
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81319eee)
Location: fs/proc/task_mmu.c:1248
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81330fbe)
Location: fs/proc/task_mmu.c:1254
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81358dba)
Location: fs/proc/task_mmu.c:1319
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8137100a)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b7c20)
Location: fs/proc/task_mmu.c:1301
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff813b7c20-ffffffff813b7e4a: pte_to_pagemap_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c96b0)
Location: fs/proc/task_mmu.c:1367
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff813c96b0-ffffffff813c98da: pte_to_pagemap_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813d07b0)
Location: fs/proc/task_mmu.c:1365
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff813d07b0-ffffffff813d09c7: pte_to_pagemap_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1382
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff81421de0-ffffffff81422086: pte_to_pagemap_entry (STB_LOCAL)
ffffffff81cc7fb6-ffffffff81cc7fdf: pte_to_pagemap_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1398
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff8149b000-ffffffff8149b37e: pte_to_pagemap_entry (STB_LOCAL)
ffffffff81e7ab7c-ffffffff81e7aba5: pte_to_pagemap_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1415
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff8152e910-ffffffff8152ed11: pte_to_pagemap_entry (STB_LOCAL)
ffffffff8206ba17-ffffffff8206ba41: pte_to_pagemap_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1412
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff81566c30-ffffffff8156702c: pte_to_pagemap_entry (STB_LOCAL)
ffffffff820eb8b1-ffffffff820eb8db: pte_to_pagemap_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pagemap_entry_t pte_to_pagemap_entry(struct pagemapread *pm, struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1404
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff8159f1b0-ffffffff8159f546: pte_to_pagemap_entry (STB_LOCAL)
ffffffff821c8b5d-ffffffff821c8b87: pte_to_pagemap_entry.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff8000104395a8)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In fs/proc/task_mmu.c (c06012d8)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054d054)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In fs/proc/task_mmu.c (ffffffe0002d353a)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813695ea)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81359303)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813670ba)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8137a709)
Location: fs/proc/task_mmu.c:1327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
