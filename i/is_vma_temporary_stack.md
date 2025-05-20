# Function: <code>is_vma_temporary_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811ca3f5)
Location: mm/rmap.c:1434
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811cb600-ffffffff811cb626: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e68c5)
Location: mm/rmap.c:1591
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811e8810-ffffffff811e8836: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f7c65)
Location: mm/rmap.c:1590
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811f9b70-ffffffff811f9b96: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81202e25)
Location: mm/rmap.c:1527
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812048d0-ffffffff812048f6: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121bb65)
Location: mm/rmap.c:1611
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8121d880-ffffffff8121d8a6: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123d9b5)
Location: mm/rmap.c:1629
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8123f730-ffffffff8123f756: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81251f85)
Location: mm/rmap.c:1664
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffffffff81253e30-ffffffff81253e56: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812642c5)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffffffff812660e0-ffffffff81266109: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81272b35)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffffffff81274a00-ffffffff81274a29: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010308620)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffff80001030a638-ffff80001030a680: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0525630)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
**Symbols:**

```
c0526b54-c0526b84: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d75a8)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
c0000000003da240-c0000000003da278: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000212eb4)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
**Symbols:**

```
ffffffe0002142b4-ffffffe0002142ea: is_vma_temporary_stack (STB_GLOBAL)
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
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b185)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffffffff8126d050-ffffffff8126d079: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125d265)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffffffff8125f080-ffffffff8125f0a9: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81268f25)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffffffff8126adf0-ffffffff8126ae19: is_vma_temporary_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_vma_temporary_stack(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812788b5)
Location: mm/rmap.c:1674
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
**Symbols:**

```
ffffffff8127a770-ffffffff8127a799: is_vma_temporary_stack (STB_GLOBAL)
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
