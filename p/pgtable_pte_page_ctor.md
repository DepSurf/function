# Function: <code>pgtable_pte_page_ctor</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087460)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089910)
Location: include/linux/mm.h:2235
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089b01)
Location: include/linux/mm.h:2240
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a7c0)
Location: include/linux/mm.h:2248
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81099d40)
Location: include/linux/mm.h:2277
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810acd6f)
Location: include/linux/mm.h:2355
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c6dff)
Location: include/linux/mm.h:2519
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ca54f)
Location: include/linux/mm.h:2833
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100ae408)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pgd_pgtable_alloc
```
```
In mm/memory.c (ffff8000102f979c)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffff800010356d9c)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/mmu.c (c1508c98)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:late_alloc
```
```
In mm/memory.c (c051bb8c)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
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
In arch/powerpc/mm/pgtable-frag.c (c0000000000892dc)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
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
In mm/memory.c (ffffffe0002096d6)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81086460)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff810751e0)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81086410)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81088550)
Location: include/linux/mm.h:1969
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
</ul>

## Differences
