# Function: <code>e820__update_table</code>

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
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab593)
Location: arch/x86/kernel/e820.c:272
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff820ab593-ffffffff820ab7bf: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b1d69)
Location: arch/x86/kernel/e820.c:292
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff826b1d69-ffffffff826b1f95: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826db440)
Location: arch/x86/kernel/e820.c:294
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff826db440-ffffffff826db661: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891827)
Location: arch/x86/kernel/e820.c:293
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff82891827-ffffffff82891a48: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a8d98)
Location: arch/x86/kernel/e820.c:307
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828a8d98-ffffffff828a8fa5: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828abdfc)
Location: arch/x86/kernel/e820.c:307
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828abdfc-ffffffff828ac009: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd1107)
Location: arch/x86/kernel/e820.c:308
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
```
**Symbols:**

```
ffffffff82cd1107-ffffffff82cd1319: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbcf47)
Location: arch/x86/kernel/e820.c:322
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
```
**Symbols:**

```
ffffffff82fbcf47-ffffffff82fbd169: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c7658)
Location: arch/x86/kernel/e820.c:322
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff831c7658-ffffffff831c787a: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a854c)
Location: arch/x86/kernel/e820.c:322
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff832a854c-ffffffff832a8a61: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83457a08)
Location: arch/x86/kernel/e820.c:322
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff83457a08-ffffffff83458041: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e764b0)
Location: arch/x86/kernel/e820.c:322
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff83e764b0-ffffffff83e7706d: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83698500)
Location: arch/x86/kernel/e820.c:322
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff83698500-ffffffff836990c8: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838c8280)
Location: arch/x86/kernel/e820.c:322
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff838c8280-ffffffff838c8e48: e820__update_table (STB_GLOBAL)
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
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82899e0e)
Location: arch/x86/kernel/e820.c:307
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff82899e0e-ffffffff8289a01b: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828920cc)
Location: arch/x86/kernel/e820.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828920cc-ffffffff828922d9: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828acdee)
Location: arch/x86/kernel/e820.c:307
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828acdee-ffffffff828acffb: e820__update_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int e820__update_table(struct e820_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ace0c)
Location: arch/x86/kernel/e820.c:307
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__memory_setup_extended
  - arch/x86/kernel/e820.c:e820__update_table_print
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff828ace0c-ffffffff828ad019: e820__update_table (STB_GLOBAL)
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
