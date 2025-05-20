# Function: <code>invalidate_other_asid</code>

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
In arch/x86/mm/init_64.c (ffffffff81070b9e)
Location: arch/x86/include/asm/tlbflush.h:298
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff826c388b)
Location: arch/x86/include/asm/tlbflush.h:298
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff8107a0f1)
Location: arch/x86/include/asm/tlbflush.h:298
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cd7f)
Location: arch/x86/include/asm/tlbflush.h:298
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
In arch/x86/mm/init_64.c (ffffffff8107393e)
Location: arch/x86/include/asm/tlbflush.h:343
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff826edb10)
Location: arch/x86/include/asm/tlbflush.h:343
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff8107cea1)
Location: arch/x86/include/asm/tlbflush.h:343
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fd91)
Location: arch/x86/include/asm/tlbflush.h:343
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
In arch/x86/mm/init_64.c (ffffffff81079b8e)
Location: arch/x86/include/asm/tlbflush.h:331
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828a46a2)
Location: arch/x86/include/asm/tlbflush.h:331
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107da9e)
Location: arch/x86/include/asm/tlbflush.h:331
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810838e1)
Location: arch/x86/include/asm/tlbflush.h:331
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810868d1)
Location: arch/x86/include/asm/tlbflush.h:331
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
In arch/x86/mm/init_64.c (ffffffff8107d8ae)
Location: arch/x86/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb6f)
Location: arch/x86/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108139e)
Location: arch/x86/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087581)
Location: arch/x86/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a513)
Location: arch/x86/include/asm/tlbflush.h:333
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
In arch/x86/mm/init_64.c (ffffffff8107e93e)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828c300a)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108245e)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81088271)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b183)
Location: arch/x86/include/asm/tlbflush.h:349
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
In arch/x86/mm/init_64.c (ffffffff8107d93e)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828adfe0)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108145e)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087271)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a143)
Location: arch/x86/include/asm/tlbflush.h:349
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
In arch/x86/mm/init_64.c (ffffffff8106ca24)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828a61e3)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107046e)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81075e41)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff81078be3)
Location: arch/x86/include/asm/tlbflush.h:349
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
In arch/x86/mm/init_64.c (ffffffff8107d8ee)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0edf)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108140e)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087221)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0f3)
Location: arch/x86/include/asm/tlbflush.h:349
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
In arch/x86/mm/init_64.c (ffffffff8107f9de)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828c402a)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108352e)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81089351)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c393)
Location: arch/x86/include/asm/tlbflush.h:349
Inline: True
```
</details>
</li>
</ul>

## Differences
