# Function: <code>my_zero_pfn</code>

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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:608
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:608
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable.h:608
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:608
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff812879e8)
Location: include/asm-generic/pgtable.h:608
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:621
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:621
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable.h:621
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:621
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff812b4d2b)
Location: include/asm-generic/pgtable.h:621
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:644
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:644
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable.h:644
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:644
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff812ca5bb)
Location: include/asm-generic/pgtable.h:644
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:749
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:749
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable.h:749
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:749
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff812d7b52)
Location: include/asm-generic/pgtable.h:749
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:794
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:794
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable.h:794
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:794
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff812fc232)
Location: include/asm-generic/pgtable.h:794
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff8122e927)
Location: include/asm-generic/pgtable.h:837
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/huge_memory.c (ffffffff81277431)
Location: include/asm-generic/pgtable.h:837
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81289ec2)
Location: include/asm-generic/pgtable.h:837
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff81290a06)
Location: include/asm-generic/pgtable.h:837
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff812f9997)
Location: include/asm-generic/pgtable.h:837
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff81329dbb)
Location: include/asm-generic/pgtable.h:837
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff81242863)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81288c37)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8129ee35)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff812a59d8)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff8130d9f9)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff81340beb)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff8124fe29)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812a389d)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812ba526)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff812c10cf)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff81335b4d)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff81368fb5)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff8125e3cc)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812b4d9d)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812cbc56)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff812d301f)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff8134974d)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff81381215)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff8128e566)
Location: include/linux/pgtable.h:1049
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812e8c23)
Location: include/linux/pgtable.h:1049
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/memory-failure.c (ffffffff813026ae)
Location: include/linux/pgtable.h:1049
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff81307e05)
Location: include/linux/pgtable.h:1049
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
```
```
In fs/dax.c (ffffffff8138d76f)
Location: include/linux/pgtable.h:1049
Inline: True
Inline callers:
  - fs/dax.c:dax_load_hole
```
```
In fs/proc/vmcore.c (ffffffff813cb445)
Location: include/linux/pgtable.h:1049
Inline: True
Inline callers:
  - fs/proc/vmcore.c:remap_oldmem_pfn_checked
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
In mm/memory.c (ffffffff812991c2)
Location: include/linux/pgtable.h:1139
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812f408c)
Location: include/linux/pgtable.h:1139
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/memory-failure.c (ffffffff8130e493)
Location: include/linux/pgtable.h:1139
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff81313bc6)
Location: include/linux/pgtable.h:1139
Inline: True
```
```
In fs/dax.c (ffffffff8139eeff)
Location: include/linux/pgtable.h:1139
Inline: True
Inline callers:
  - fs/dax.c:dax_load_hole
```
```
In fs/proc/vmcore.c (ffffffff813dd115)
Location: include/linux/pgtable.h:1139
Inline: True
Inline callers:
  - fs/proc/vmcore.c:remap_oldmem_pfn_checked
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
In mm/memory.c (ffffffff8129e487)
Location: include/linux/pgtable.h:1140
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812fa34d)
Location: include/linux/pgtable.h:1140
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/memory-failure.c (ffffffff81314a4f)
Location: include/linux/pgtable.h:1140
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff81319d66)
Location: include/linux/pgtable.h:1140
Inline: True
```
```
In fs/dax.c (ffffffff813a7794)
Location: include/linux/pgtable.h:1140
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/vmcore.c (ffffffff813e4303)
Location: include/linux/pgtable.h:1140
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff812df5c3)
Location: include/linux/pgtable.h:1159
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff813441ad)
Location: include/linux/pgtable.h:1159
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/memory-failure.c (ffffffff81360a93)
Location: include/linux/pgtable.h:1159
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366b16)
Location: include/linux/pgtable.h:1159
Inline: True
```
```
In fs/dax.c (ffffffff813f6922)
Location: include/linux/pgtable.h:1159
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
```
In fs/proc/vmcore.c (ffffffff81435eb3)
Location: include/linux/pgtable.h:1159
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff8133fb45)
Location: include/linux/pgtable.h:1221
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff813b9708)
Location: include/linux/pgtable.h:1221
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/memory-failure.c (ffffffff813dce49)
Location: include/linux/pgtable.h:1221
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff813e3f66)
Location: include/linux/pgtable.h:1221
Inline: True
```
```
In fs/dax.c (ffffffff81469176)
Location: include/linux/pgtable.h:1221
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
```
In fs/proc/vmcore.c (ffffffff814b02ce)
Location: include/linux/pgtable.h:1221
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff813b7a6f)
Location: include/linux/pgtable.h:1257
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff8143b9f9)
Location: include/linux/pgtable.h:1257
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8146b9d7)
Location: include/linux/pgtable.h:1257
Inline: True
```
```
In fs/dax.c (ffffffff814f9b12)
Location: include/linux/pgtable.h:1257
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
```
In fs/proc/vmcore.c (ffffffff81546b78)
Location: include/linux/pgtable.h:1257
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff813ec8c5)
Location: include/linux/pgtable.h:1242
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff81471346)
Location: include/linux/pgtable.h:1242
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814a0878)
Location: include/linux/pgtable.h:1242
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
```
```
In fs/dax.c (ffffffff81530fa2)
Location: include/linux/pgtable.h:1242
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
```
In fs/proc/vmcore.c (ffffffff8157e657)
Location: include/linux/pgtable.h:1242
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff8141fc2b)
Location: include/linux/pgtable.h:1352
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff814a0ee0)
Location: include/linux/pgtable.h:1352
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814d1325)
Location: include/linux/pgtable.h:1352
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
```
```
In fs/dax.c (ffffffff81565e82)
Location: include/linux/pgtable.h:1352
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
```
In fs/proc/vmcore.c (ffffffff815b7097)
Location: include/linux/pgtable.h:1352
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffff8000102f5e20)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffff800010356170)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffff80001036fe94)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffff800010378c2c)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffff80001040a168)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffff80001044eef4)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (c0517e7c)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/userfaultfd.c (c0563ff4)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/proc/vmcore.c (c0612420)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bd590)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (c00000000043c990)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (c000000000460cec)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (c00000000046b8e0)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (c00000000051636c)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (c000000000566ab8)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207110)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/userfaultfd.c (ffffffe0002504e8)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffe0002b3d1a)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
</details>
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
In mm/memory.c (ffffffff81256a1c)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812ad37d)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c4236)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff812cb5ff)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff81341d2d)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff813797f5)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff812493da)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff8129e258)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812b5276)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff812bc4ad)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff813326db)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff8136a2c5)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff812547bc)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812ab18d)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c2046)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff812c940f)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff8133f7fd)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff813772c5)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In mm/memory.c (ffffffff8126424d)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812bb4dd)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812d2ae1)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/userfaultfd.c (ffffffff812da0ef)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (ffffffff813531c9)
Location: include/asm-generic/pgtable.h:875
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff8138ad75)
Location: include/asm-generic/pgtable.h:875
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
</ul>

## Differences
