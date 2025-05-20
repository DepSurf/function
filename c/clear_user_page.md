# Function: <code>clear_user_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c209b)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/huge_memory.c (ffffffff811f5628)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
```
In fs/dax.c (ffffffff8125df84)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ddc0e)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff8121a5b2)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81287d14)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811eda47)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff8122e9bb)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129c3af)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f89e3)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff8123865e)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812ab4ce)
Location: arch/x86/include/asm/page.h:24
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff81210c8d)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff81259b31)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff812cee14)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff812316ab)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff8127c48d)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f961b)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244e7b)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff81290b2f)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130d7bc)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256e39)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812a9e62)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff813359dd)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812653c9)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812bb3d2)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff813495dd)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812957a7)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812f0637)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In fs/dax.c (ffffffff8138e8af)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/memory.c (ffffffff812a0697)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812fbdc2)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff813a000d)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/memory.c (ffffffff812a5fd8)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff81302d0a)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff813a75a3)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/memory.c (ffffffff812e7458)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff8134c7ca)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff813f4d05)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff8131cafa)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81348629)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff813c4002)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff81467888)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff813906ab)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813c0b39)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff814477a7)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff814f7f48)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff813c3031)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813f58aa)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff8147d18d)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff8152f148)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff813edb4a)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8141f58a)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff814ac95c)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff81564028)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void clear_user_page(void *page, long unsigned int vaddr, struct page *pg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/mem.c (c0000000000870b0)
Location: arch/powerpc/mm/mem.c:539
Inline: False
Direct callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
**Symbols:**

```
c0000000000870b0-c00000000008712c: clear_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125da19)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812b39b2)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff81341bbd)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124fe69)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812a6944)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813324b1)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b7b9)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812b17c2)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff8133f68d)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126b174)
Location: arch/x86/include/asm/page.h:25
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812c1b31)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
```
In fs/dax.c (ffffffff8135305b)
Location: arch/x86/include/asm/page.h:25
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
