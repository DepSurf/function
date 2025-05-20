# Function: <code>transhuge_vma_enabled</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281f4a)
Location: include/linux/huge_mm.h:133
Inline: True
Inline callers:
  - mm/shmem.c:shmem_huge_enabled
```
```
In mm/memory.c (ffffffff812a4085)
Location: include/linux/huge_mm.h:133
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812fbd55)
Location: include/linux/huge_mm.h:133
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff81302085)
Location: include/linux/huge_mm.h:133
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
In mm/memory.c (ffffffff812e53b1)
Location: include/linux/huge_mm.h:133
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81345b65)
Location: include/linux/huge_mm.h:133
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff8134bee5)
Location: include/linux/huge_mm.h:133
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
In mm/memory.c (ffffffff813476aa)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff813bbc8e)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_active
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff813c60e5)
Location: include/linux/huge_mm.h:134
Inline: True
```
</details>
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
