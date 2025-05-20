# Function: <code>__flush_tlb_single</code>

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
In arch/x86/kernel/acpi/apei.c (ffffffff8104fe69)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_flush_tlb_one
```
```
In arch/x86/mm/init_64.c (ffffffff8106967e)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
```
In arch/x86/mm/ioremap.c (ffffffff81f7800a)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff81072399)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81072ffc)
Location: arch/x86/include/asm/paravirt.h:328
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
In arch/x86/kernel/acpi/apei.c (ffffffff8104ffe9)
Location: arch/x86/include/asm/paravirt.h:318
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_flush_tlb_one
```
```
In arch/x86/mm/init_64.c (ffffffff8106940e)
Location: arch/x86/include/asm/paravirt.h:318
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0762)
Location: arch/x86/include/asm/paravirt.h:318
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff81072069)
Location: arch/x86/include/asm/paravirt.h:318
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810745c5)
Location: arch/x86/include/asm/paravirt.h:318
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
In arch/x86/kernel/acpi/apei.c (ffffffff81052809)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_flush_tlb_one
```
```
In arch/x86/mm/init_64.c (ffffffff8106cfee)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbcd3)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff81075bd9)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/mm/kmmio.c (ffffffff81078145)
Location: arch/x86/include/asm/paravirt.h:309
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
In arch/x86/kernel/acpi/apei.c (ffffffff81052329)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_flush_tlb_one
```
```
In arch/x86/mm/init_64.c (ffffffff8106c12f)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcca0)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/tlb.c (ffffffff81074529)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810769c9)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
</details>
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
