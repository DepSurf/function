# Function: <code>vma_is_temporary_stack</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812947a1)
Location: include/linux/mm.h:622
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (ffffffff812a3905)
Location: include/linux/mm.h:622
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff812ea5a1)
Location: include/linux/mm.h:622
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/khugepaged.c (ffffffff812efc58)
Location: include/linux/mm.h:622
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129f021)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (ffffffff812af1d5)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff812f5a01)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/khugepaged.c (ffffffff812fb32c)
Location: include/linux/mm.h:655
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a40a0)
Location: include/linux/mm.h:678
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (ffffffff812b46d5)
Location: include/linux/mm.h:678
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff812fbd70)
Location: include/linux/mm.h:678
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff813020fc)
Location: include/linux/mm.h:678
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e53cc)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (ffffffff812f62b5)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff81345b80)
Location: include/linux/mm.h:679
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff8134bf78)
Location: include/linux/mm.h:679
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813476c5)
Location: include/linux/mm.h:631
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/rmap.c (ffffffff8135a4f5)
Location: include/linux/mm.h:631
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff813bbce7)
Location: include/linux/mm.h:631
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff813c61af)
Location: include/linux/mm.h:631
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d5015)
Location: include/linux/mm.h:641
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff8143e202)
Location: include/linux/mm.h:641
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_vma_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81409ed5)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff81473a73)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_vma_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81436705)
Location: include/linux/mm.h:908
Inline: True
Inline callers:
  - mm/rmap.c:invalid_migration_vma
```
```
In mm/huge_memory.c (ffffffff814a2f55)
Location: include/linux/mm.h:908
Inline: True
Inline callers:
  - mm/huge_memory.c:__thp_vma_allowable_orders
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
