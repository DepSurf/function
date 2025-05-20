# Function: <code>__flush_tlb_one_kernel</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81070b8f)
Location: arch/x86/include/asm/tlbflush.h:440
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff826c387c)
Location: arch/x86/include/asm/tlbflush.h:440
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff8107a0e2)
Location: arch/x86/include/asm/tlbflush.h:440
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cd6d)
Location: arch/x86/include/asm/tlbflush.h:440
Inline: True
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
In arch/x86/mm/init_64.c (ffffffff8107392f)
Location: arch/x86/include/asm/tlbflush.h:485
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff826edb01)
Location: arch/x86/include/asm/tlbflush.h:485
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff8107ce92)
Location: arch/x86/include/asm/tlbflush.h:485
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fd81)
Location: arch/x86/include/asm/tlbflush.h:485
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
In arch/x86/mm/init_64.c (ffffffff81079b7f)
Location: arch/x86/include/asm/tlbflush.h:479
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4693)
Location: arch/x86/include/asm/tlbflush.h:479
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107da8b)
Location: arch/x86/include/asm/tlbflush.h:479
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810838d2)
Location: arch/x86/include/asm/tlbflush.h:479
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810868c1)
Location: arch/x86/include/asm/tlbflush.h:479
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
In arch/x86/mm/init_64.c (ffffffff8107d89f)
Location: arch/x86/include/asm/tlbflush.h:481
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb60)
Location: arch/x86/include/asm/tlbflush.h:481
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108138b)
Location: arch/x86/include/asm/tlbflush.h:481
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087572)
Location: arch/x86/include/asm/tlbflush.h:481
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a503)
Location: arch/x86/include/asm/tlbflush.h:481
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
In arch/x86/mm/init_64.c (ffffffff8107e92f)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2ffb)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108244b)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81088262)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b173)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d92f)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828adfd1)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108144b)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087262)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a133)
Location: arch/x86/include/asm/tlbflush.h:497
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
In arch/x86/mm/init_64.c (ffffffff8106ca18)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828a61d7)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107045b)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81075e32)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff81078bd3)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
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
In arch/x86/mm/init_64.c (ffffffff8107d8df)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0ed0)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810813fb)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087212)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0e3)
Location: arch/x86/include/asm/tlbflush.h:497
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
In arch/x86/mm/init_64.c (ffffffff8107f9cf)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828c401b)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108351b)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81089342)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c383)
Location: arch/x86/include/asm/tlbflush.h:497
Inline: True
```
</details>
</li>
</ul>

## Differences
