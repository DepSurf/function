# Function: <code>memblock_phys_alloc</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc(phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828bdf80)
Location: mm/memblock.c:1334
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828bdf80-ffffffff828bdf92: memblock_phys_alloc (STB_GLOBAL)
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
In arch/x86/kernel/e820.c (ffffffff828a942c)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff8290e459)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff828ac490)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff82917e72)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff82cd19be)
Location: include/linux/memblock.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff82d2a2a2)
Location: include/linux/memblock.h:357
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff82fbd81b)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff830189b9)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff831c7f2f)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff832239a3)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff832a9112)
Location: include/linux/memblock.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff8330d7a9)
Location: include/linux/memblock.h:391
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff8345878f)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff834c74d5)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff83e77b62)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In arch/x86/platform/efi/memmap.c (ffffffff83ea1595)
Location: include/linux/memblock.h:407
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff83699ff2)
Location: include/linux/memblock.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In arch/x86/platform/efi/memmap.c (ffffffff836c57e5)
Location: include/linux/memblock.h:406
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff838c9d72)
Location: include/linux/memblock.h:418
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In arch/x86/platform/efi/memmap.c (ffffffff838f63e5)
Location: include/linux/memblock.h:418
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
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
In arch/arm64/mm/mmu.c (ffff800011437b7c)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:early_pgtable_alloc
```
```
In drivers/firmware/efi/memmap.c (ffff8000114a67a0)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/arm/mm/init.c (c1507590)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/arm/mm/init.c:arm_memblock_steal
```
```
In drivers/firmware/efi/memmap.c (c15a8b6c)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/riscv/mm/init.c (ffffffe0000037cc)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:create_pgd_mapping
  - arch/riscv/mm/init.c:create_pgd_mapping
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
In arch/x86/kernel/e820.c (ffffffff8289a4a2)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff828fd278)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff82892760)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff828f4b14)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff828ad482)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff829124a7)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
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
In arch/x86/kernel/e820.c (ffffffff828ad4a0)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
```
In drivers/firmware/efi/memmap.c (ffffffff82918ed4)
Location: include/linux/memblock.h:354
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
