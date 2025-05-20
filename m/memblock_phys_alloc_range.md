# Function: <code>memblock_phys_alloc_range</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828d7216)
Location: mm/memblock.c:1411
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828d7216-ffffffff828d722a: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828df687)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828df687-ffffffff828df69b: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfcbbd)
Location: mm/memblock.c:1421
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff82cfcbbd-ffffffff82cfcbd4: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe95e6)
Location: mm/memblock.c:1380
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel_low
  - arch/x86/kernel/setup.c:relocate_initrd
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff82fe95e6-ffffffff82fe9657: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3c8f)
Location: mm/memblock.c:1381
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff831f3c8f-ffffffff831f3d00: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832d9fd5)
Location: mm/memblock.c:1416
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff832d9fd5-ffffffff832da046: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348f00d)
Location: mm/memblock.c:1423
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff8348f00d-ffffffff8348f08e: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec1480)
Location: mm/memblock.c:1441
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff83ec1480-ffffffff83ec1506: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6c90)
Location: mm/memblock.c:1463
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff836e6c90-ffffffff836e6d16: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83919240)
Location: mm/memblock.c:1521
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - kernel/crash_core.c:reserve_crashkernel_generic
  - kernel/crash_core.c:reserve_crashkernel_generic
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff83919240-ffffffff839192c6: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff800011458654)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:early_pgtable_alloc
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffff800011458654-ffff8000114586a4: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c15325d8)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/arm/mm/init.c:arm_memblock_steal
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
c15325d8-c1532604: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c000000001381ec0)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_initialize
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_initialize
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
c000000001381ec0-c000000001381ed8: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000016d4a)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/riscv/mm/init.c:create_pgd_mapping
  - arch/riscv/mm/init.c:create_pgd_mapping
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffe000016d4a-ffffffe000016d8e: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c853b)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828c853b-ffffffff828c854f: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c0c60)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828c0c60-ffffffff828c0c74: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828db2bb)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828db2bb-ffffffff828db2cf: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828e06dc)
Location: mm/memblock.c:1408
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff828e06dc-ffffffff828e06f0: memblock_phys_alloc_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
