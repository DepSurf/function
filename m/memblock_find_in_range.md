# Function: <code>memblock_find_in_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181e2b6)
Location: mm/memblock.c:264
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/numa.c:numa_set_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
**Symbols:**

```
ffffffff8181e2b6-ffffffff8181e31b: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898766)
Location: mm/memblock.c:260
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_set_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81898766-ffffffff818987cb: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cce0e)
Location: mm/memblock.c:260
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff818cce0e-ffffffff818cce73: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81904284)
Location: mm/memblock.c:248
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81904284-ffffffff819042e9: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e28d)
Location: mm/memblock.c:248
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff8198e28d-ffffffff8198e2f2: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eab10)
Location: mm/memblock.c:251
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff819eab10-ffffffff819eab75: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a25d6f)
Location: mm/memblock.c:328
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81a25d6f-ffffffff81a25dd2: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a9648e)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81a9648e-ffffffff81a964f6: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81acdd65)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81acdd65-ffffffff81acddcd: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc674d)
Location: mm/memblock.c:331
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel_low
  - arch/x86/kernel/setup.c:relocate_initrd
  - arch/x86/kernel/aperture_64.c:allocate_aperture
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81bc674d-ffffffff81bc67b5: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3f46f)
Location: mm/memblock.c:316
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/aperture_64.c:allocate_aperture
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81c3f46f-ffffffff81c3f4d7: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31535)
Location: mm/memblock.c:316
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81c31535-ffffffff81c31598: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff81d4fece)
Location: mm/memblock.c:318
Inline: True
Direct callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
**Symbols:**

```
ffffffff81d4fece-ffffffff81d4ff2b: memblock_find_in_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff81f1ff0c)
Location: mm/memblock.c:318
Inline: True
Direct callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
**Symbols:**

```
ffffffff81f1ff0c-ffffffff81f1ff7b: memblock_find_in_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff820c9300)
Location: mm/memblock.c:322
Inline: True
Direct callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
**Symbols:**

```
ffffffff820c9300-ffffffff820c93aa: memblock_find_in_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff8214d560)
Location: mm/memblock.c:322
Inline: True
Direct callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
**Symbols:**

```
ffffffff8214d560-ffffffff8214d60a: memblock_find_in_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff82230110)
Location: mm/memblock.c:328
Inline: True
Direct callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
**Symbols:**

```
ffffffff82230110-ffffffff822301ba: memblock_find_in_range.constprop.0 (STB_LOCAL)
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031bfd0)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/numa.c:numa_init
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
ffff80001031bfd0-ffff80001031c064: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0535f08)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
c0535f08-c0535fa0: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003efc10)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/powerpc/kernel/fadump.c:fadump_reserve_mem
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
c0000000003efc10-c0000000003efcd8: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000048080)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
ffffffe000048080-ffffffe0000480f0: memblock_find_in_range (STB_GLOBAL)
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6cbd5)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81a6cbd5-ffffffff81a6cc3d: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a2911c)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
**Symbols:**

```
ffffffff81a2911c-ffffffff81a29184: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad8fe5)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81ad8fe5-ffffffff81ad904d: memblock_find_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae549b)
Location: mm/memblock.c:335
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/setup.c:reserve_crashkernel
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/numa.c:numa_alloc_distance
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81ae549b-ffffffff81ae5503: memblock_find_in_range (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
