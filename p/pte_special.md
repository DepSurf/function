# Function: <code>pte_special</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:140
Inline: True
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
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:151
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:151
Inline: True
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
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:151
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:151
Inline: True
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
```
In mm/memory.c (ffffffff8120a21d)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory.c:_vm_normal_page
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
In mm/gup.c (ffffffff81226b1a)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff8122b062)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory.c:_vm_normal_page
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
In mm/gup.c (ffffffff81239c1b)
Location: arch/x86/include/asm/pgtable.h:185
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff8123e422)
Location: arch/x86/include/asm/pgtable.h:185
Inline: True
Inline callers:
  - mm/memory.c:_vm_normal_page
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
In mm/gup.c (ffffffff8124b01d)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff812502b2)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff812c445f)
Location: arch/x86/include/asm/pgtable.h:202
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
In mm/gup.c (ffffffff8125950d)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff8125e862)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff812d5e9e)
Location: arch/x86/include/asm/pgtable.h:202
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
In mm/gup.c (ffffffff81288179)
Location: arch/x86/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff8128eb52)
Location: arch/x86/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff8130af1f)
Location: arch/x86/include/asm/pgtable.h:204
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
In mm/gup.c (ffffffff81291e61)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff81299702)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff81316def)
Location: arch/x86/include/asm/pgtable.h:203
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
In mm/gup.c (ffffffff8129797f)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff8129e91f)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff8131d016)
Location: arch/x86/include/asm/pgtable.h:203
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
In mm/gup.c (ffffffff812d8398)
Location: arch/x86/include/asm/pgtable.h:174
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff812dfb5f)
Location: arch/x86/include/asm/pgtable.h:174
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
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
In mm/gup.c (ffffffff81338293)
Location: arch/x86/include/asm/pgtable.h:177
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813400df)
Location: arch/x86/include/asm/pgtable.h:177
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
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
In mm/vmscan.c (ffffffff81378267)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
```
```
In mm/gup.c (ffffffff813afa69)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813b8055)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
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
In mm/vmscan.c (ffffffff813abab7)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
```
```
In mm/gup.c (ffffffff813e41c1)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813ece25)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
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
In mm/vmscan.c (ffffffff813d61d7)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
```
```
In mm/gup.c (ffffffff8140ea54)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff81418385)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/mce_power.c (c00000000003a400)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:490
Inline: True
Inline callers:
  - arch/powerpc/kernel/mce_power.c:addr_to_pfn
```
```
In arch/powerpc/mm/pgtable.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:490
Inline: True
```
```
In mm/gup.c (c0000000003b6a8c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:490
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (c0000000003bdbf8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:490
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (c000000000470274)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:490
Inline: True
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
In mm/memory.c (ffffffe0002073f4)
Location: arch/riscv/include/asm/pgtable.h:240
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffe0002520f2)
Location: arch/riscv/include/asm/pgtable.h:240
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff81251b5d)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81256eb2)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff812ce47e)
Location: arch/x86/include/asm/pgtable.h:202
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
In mm/gup.c (ffffffff81244a4c)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81249804)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff812bf1e6)
Location: arch/x86/include/asm/pgtable.h:202
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
In mm/gup.c (ffffffff8124f8fd)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81254c52)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff812cc28e)
Location: arch/x86/include/asm/pgtable.h:202
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
In mm/gup.c (ffffffff8125f297)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff812646d2)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/hmm.c (ffffffff812dcfe2)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
```
</details>
</li>
</ul>

## Differences
