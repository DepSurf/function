# Function: <code>flush_tlb_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_tlb_page(struct vm_area_struct *vma, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072a40)
Location: arch/x86/mm/tlb.c:239
Inline: False
Direct callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
**Symbols:**

```
ffffffff81072a40-ffffffff81072ac5: flush_tlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_tlb_page(struct vm_area_struct *vma, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072a00)
Location: arch/x86/mm/tlb.c:359
Inline: False
Direct callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
**Symbols:**

```
ffffffff81072a00-ffffffff81072a85: flush_tlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_tlb_page(struct vm_area_struct *vma, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810765b0)
Location: arch/x86/mm/tlb.c:374
Inline: False
Direct callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
**Symbols:**

```
ffffffff810765b0-ffffffff81076632: flush_tlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202bb4)
Location: arch/x86/include/asm/tlbflush.h:251
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b91b)
Location: arch/x86/include/asm/tlbflush.h:519
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d701)
Location: arch/x86/include/asm/tlbflush.h:564
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251c51)
Location: arch/x86/include/asm/tlbflush.h:565
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263f22)
Location: arch/x86/include/asm/tlbflush.h:567
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/pgtable-generic.c (ffffffff81272792)
Location: arch/x86/include/asm/tlbflush.h:583
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/pgtable-generic.c (ffffffff812a3554)
Location: arch/x86/include/asm/tlbflush.h:233
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/memory.c (ffffffff8129bb87)
Location: arch/x86/include/asm/tlbflush.h:233
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff812aee34)
Location: arch/x86/include/asm/tlbflush.h:233
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/memory.c (ffffffff812a0c50)
Location: arch/x86/include/asm/tlbflush.h:237
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff812b4364)
Location: arch/x86/include/asm/tlbflush.h:237
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/memory.c (ffffffff812e1d70)
Location: arch/x86/include/asm/tlbflush.h:237
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff812f5f44)
Location: arch/x86/include/asm/tlbflush.h:237
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/memory.c (ffffffff81342cb0)
Location: arch/x86/include/asm/tlbflush.h:237
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff81359ee1)
Location: arch/x86/include/asm/tlbflush.h:237
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/memory.c (ffffffff813bace7)
Location: arch/x86/include/asm/tlbflush.h:238
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff813d4911)
Location: arch/x86/include/asm/tlbflush.h:238
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/memory.c (ffffffff813ef7f6)
Location: arch/x86/include/asm/tlbflush.h:251
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff814092e1)
Location: arch/x86/include/asm/tlbflush.h:251
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/memory.c (ffffffff814199d5)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff81435ad1)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In arch/arm64/mm/fault.c (ffff8000100ad288)
Location: arch/arm64/include/asm/tlbflush.h:167
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:ptep_set_access_flags
```
```
In mm/memory.c (ffff8000102f9fbc)
Location: arch/arm64/include/asm/tlbflush.h:167
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/pgtable-generic.c (ffff800010308028)
Location: arch/arm64/include/asm/tlbflush.h:167
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_tlb_page(struct vm_area_struct *vma, long unsigned int uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_tlb.c (c03140fc)
Location: arch/arm/kernel/smp_tlb.c:196
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush_young
  - mm/pgtable-generic.c:ptep_set_access_flags
```
**Symbols:**

```
c03140fc-c03141f8: flush_tlb_page (STB_GLOBAL)
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
In mm/memory.c (c0000000003c4270)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:121
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/pgtable-generic.c (c0000000003d7244)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:121
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush_young
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_tlb_page(struct vm_area_struct *vma, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba544)
Location: arch/riscv/mm/tlbflush.c:47
Inline: False
Direct callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
**Symbols:**

```
ffffffe0000ba544-ffffffe0000ba582: flush_tlb_page (STB_GLOBAL)
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
In mm/pgtable-generic.c (ffffffff8126ade2)
Location: arch/x86/include/asm/tlbflush.h:583
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/pgtable-generic.c (ffffffff8125ce12)
Location: arch/x86/include/asm/tlbflush.h:583
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/pgtable-generic.c (ffffffff81268b82)
Location: arch/x86/include/asm/tlbflush.h:583
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
In mm/pgtable-generic.c (ffffffff81278512)
Location: arch/x86/include/asm/tlbflush.h:583
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
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
</ul>
<b>Arch</b>
<ul>
</ul>
