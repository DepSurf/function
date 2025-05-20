# Function: <code>__pte_alloc_one</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086755)
Location: include/asm-generic/pgalloc.h:59
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81087445)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff810898f5)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff81089ae5)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff8108a7a5)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff81099d25)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff810acd55)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff810c6de5)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff810ca535)
Location: include/asm-generic/pgalloc.h:59
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d29c5)
Location: include/asm-generic/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
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
In mm/memory.c (ffff8000102f9784)
Location: include/asm-generic/pgalloc.h:59
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffff800010356d80)
Location: include/asm-generic/pgalloc.h:59
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
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051bb60)
Location: include/asm-generic/pgalloc.h:59
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002096bc)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff81086445)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff810751c5)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff810863f5)
Location: include/asm-generic/pgalloc.h:59
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
In arch/x86/mm/pgtable.c (ffffffff81088535)
Location: include/asm-generic/pgalloc.h:59
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
</ul>

## Differences
