# Function: <code>e820__range_add</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab4b5)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff820ab4b5-ffffffff820ab4d4: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b1c8b)
Location: arch/x86/kernel/e820.c:168
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff826b1c8b-ffffffff826b1caa: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826db362)
Location: arch/x86/kernel/e820.c:169
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff826db362-ffffffff826db381: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891749)
Location: arch/x86/kernel/e820.c:168
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff82891749-ffffffff82891768: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a8cc1)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828a8cc1-ffffffff828a8ce0: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828abd25)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828abd25-ffffffff828abd44: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd1030)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
```
**Symbols:**

```
ffffffff82cd1030-ffffffff82cd104f: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbce70)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
```
**Symbols:**

```
ffffffff82fbce70-ffffffff82fbce8f: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c7581)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff831c7581-ffffffff831c75a0: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a8475)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff832a8475-ffffffff832a8494: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8345790d)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff8345790d-ffffffff83457938: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e7827c)
Location: arch/x86/kernel/e820.c:182
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff83e76370-ffffffff83e763e5: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8369a740)
Location: arch/x86/kernel/e820.c:182
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff83698280-ffffffff83698391: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838ca4c0)
Location: arch/x86/kernel/e820.c:182
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff838c8000-ffffffff838c8111: e820__range_add (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82899d37)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff82899d37-ffffffff82899d56: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891ff5)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff82891ff5-ffffffff82892014: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828acd17)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828acd17-ffffffff828acd36: e820__range_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828acd35)
Location: arch/x86/kernel/e820.c:182
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__append_e820_table
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828acd35-ffffffff828acd54: e820__range_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
