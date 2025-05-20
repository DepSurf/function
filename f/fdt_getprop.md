# Function: <code>fdt_getprop</code>

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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const void *fdt_getprop(const void *fdt, int nodeoffset, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143f290)
Location: scripts/dtc/libfdt/fdt_ro.c:480
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_stringlist_get
  - lib/fdt_ro.c:fdt_stringlist_search
  - lib/fdt_ro.c:fdt_stringlist_count
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_get_phandle
Direct callers:
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
  - lib/fdt_wip.c:fdt_setprop_inplace
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_is_compatible
  - drivers/of/fdt.c:of_get_flat_dt_prop
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_stringlist_get
  - lib/fdt_ro.c:fdt_stringlist_search
  - lib/fdt_ro.c:fdt_stringlist_count
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
ffff800010d86018-ffff800010d86068: fdt_getprop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *fdt_getprop(const void *fdt, int nodeoffset, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e81028)
Location: scripts/dtc/libfdt/fdt_ro.c:480
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_is_compatible
  - drivers/of/fdt.c:of_get_flat_dt_prop
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt_address.c:of_flat_dt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_stringlist_get
  - lib/fdt_ro.c:fdt_stringlist_search
  - lib/fdt_ro.c:fdt_stringlist_count
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
c0e81028-c0e81070: fdt_getprop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *fdt_getprop(const void *fdt, int nodeoffset, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5720)
Location: scripts/dtc/libfdt/fdt_ro.c:480
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt
  - arch/powerpc/kernel/ima_kexec.c:remove_ima_buffer
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_is_compatible
  - drivers/of/fdt.c:of_get_flat_dt_prop
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_stringlist_get
  - lib/fdt_ro.c:fdt_stringlist_search
  - lib/fdt_ro.c:fdt_stringlist_count
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
c000000000ec5720-c000000000ec5780: fdt_getprop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const void *fdt_getprop(const void *fdt, int nodeoffset, const char *name, int *lenp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b0af6)
Location: scripts/dtc/libfdt/fdt_ro.c:480
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_node_check_compatible
  - lib/fdt_ro.c:fdt_stringlist_get
  - lib/fdt_ro.c:fdt_stringlist_search
  - lib/fdt_ro.c:fdt_stringlist_count
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_get_phandle
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_is_compatible
  - drivers/of/fdt.c:of_get_flat_dt_prop
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_translate_address
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - lib/fdt_wip.c:fdt_setprop_inplace
```
**Symbols:**

```
ffffffe0008b01d6-ffffffe0008b021c: fdt_getprop (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
