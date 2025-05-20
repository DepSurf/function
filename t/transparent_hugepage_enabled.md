# Function: <code>transparent_hugepage_enabled</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f58cd)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81234de0)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120e642)
Location: include/linux/huge_mm.h:95
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812533dc)
Location: include/linux/huge_mm.h:95
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122fe95)
Location: include/linux/huge_mm.h:96
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81277923)
Location: include/linux/huge_mm.h:96
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81288e80)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81288e80-ffffffff81288f14: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a3af0)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812a3af0-ffffffff812a3bd0: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b4ff0)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812b4ff0-ffffffff812b50d0: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ea520)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812ea520-ffffffff812ea619: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f5980)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812f5980-ffffffff812f5a79: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103562f8)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffff8000103562f8-ffff8000103563dc: transparent_hugepage_enabled (STB_GLOBAL)
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
In fs/proc/task_mmu.c (0)
Location: include/linux/huge_mm.h:300
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043d510)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
c00000000043d510-c00000000043d67c: transparent_hugepage_enabled (STB_GLOBAL)
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
In fs/proc/task_mmu.c (0)
Location: include/linux/huge_mm.h:300
Inline: True
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
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad5d0)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812ad5d0-ffffffff812ad6b0: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129ec50)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8129ec50-ffffffff8129ed30: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ab3e0)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812ab3e0-ffffffff812ab4c0: transparent_hugepage_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bb730)
Location: mm/huge_memory.c:65
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812bb730-ffffffff812bb810: transparent_hugepage_enabled (STB_GLOBAL)
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
