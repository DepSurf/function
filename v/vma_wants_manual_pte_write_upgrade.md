# Function: <code>vma_wants_manual_pte_write_upgrade</code>

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
In mm/memory.c (ffffffff813bc9b6)
Location: include/linux/mm.h:2162
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff813cf477)
Location: include/linux/mm.h:2162
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/huge_memory.c (ffffffff8143f74d)
Location: include/linux/mm.h:2162
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff813f13bc)
Location: include/linux/mm.h:2485
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81403ecf)
Location: include/linux/mm.h:2485
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/huge_memory.c (ffffffff81474f8d)
Location: include/linux/mm.h:2485
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff814a256f)
Location: include/linux/mm.h:2485
Inline: True
Inline callers:
  - mm/userfaultfd.c:uffd_wp_range
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
In mm/memory.c (ffffffff8141c184)
Location: include/linux/mm.h:2534
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff814303e5)
Location: include/linux/mm.h:2534
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/huge_memory.c (ffffffff814a44c6)
Location: include/linux/mm.h:2534
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff814d262f)
Location: include/linux/mm.h:2534
Inline: True
Inline callers:
  - mm/userfaultfd.c:uffd_wp_range
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
