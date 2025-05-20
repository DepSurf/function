# Function: <code>vma_soft_dirty_enabled</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b002f)
Location: mm/internal.h:833
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mmap.c (ffffffff813c8b49)
Location: mm/internal.h:833
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/mprotect.c (ffffffff813cdd6c)
Location: mm/internal.h:833
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/huge_memory.c (ffffffff8143f2c0)
Location: mm/internal.h:833
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
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
In mm/gup.c (ffffffff813e465b)
Location: mm/internal.h:1026
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mmap.c (ffffffff813fcdde)
Location: mm/internal.h:1026
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/mprotect.c (ffffffff8140272c)
Location: mm/internal.h:1026
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/huge_memory.c (ffffffff81474a81)
Location: mm/internal.h:1026
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
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
In mm/gup.c (ffffffff8140f006)
Location: mm/internal.h:1117
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mmap.c (ffffffff814297ae)
Location: mm/internal.h:1117
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/mprotect.c (ffffffff8142ed5c)
Location: mm/internal.h:1117
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/huge_memory.c (ffffffff814a41e8)
Location: mm/internal.h:1117
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
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
