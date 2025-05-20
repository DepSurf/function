# Function: <code>e820_add_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void e820_add_region(u64 start, u64 size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67a8d)
Location: arch/x86/kernel/e820.c:129
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:__append_e820_map
  - arch/x86/kernel/e820.c:e820_remove_range
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_stolen
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff81f67a8d-ffffffff81f67aa7: e820_add_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void e820_add_region(u64 start, u64 size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8f935)
Location: arch/x86/kernel/e820.c:129
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820_remove_range
  - arch/x86/kernel/e820.c:__append_e820_map
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff81f8f935-ffffffff81f8f94f: e820_add_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void e820_add_region(u64 start, u64 size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fcad08)
Location: arch/x86/kernel/e820.c:131
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:e820_remove_range
  - arch/x86/kernel/e820.c:__append_e820_map
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff81fcad08-ffffffff81fcad22: e820_add_region (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
