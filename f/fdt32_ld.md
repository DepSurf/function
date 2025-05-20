# Function: <code>fdt32_ld</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/machine_kexec_file.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In arch/arm64/mm/mmu.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In drivers/firmware/efi/libstub/fdt.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt_ro.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt_rw.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt_sw.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In drivers/of/fdt.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
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
In drivers/of/fdt.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt_ro.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt_rw.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/prom.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In arch/powerpc/kernel/machine_kexec_file_64.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In arch/powerpc/kernel/kexec_elf_64.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In drivers/of/fdt.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt_ro.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
```
In lib/fdt_rw.c (0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/init.c (ffffffe000003bf0)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:setup_bootmem
```
```
In drivers/of/fdt.c (ffffffe00003a874)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
Inline callers:
  - drivers/of/fdt.c:of_fdt_raw_init
  - drivers/of/fdt.c:unflatten_and_copy_device_tree
  - drivers/of/fdt.c:early_init_dt_verify
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_fdt_reserve_self
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:__unflatten_device_tree
```
```
In drivers/of/overlay.c (ffffffe00072b2f8)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
Inline callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
```
In lib/fdt.c (ffffffe0008af770)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
Inline callers:
  - lib/fdt.c:fdt_move
  - lib/fdt.c:fdt_next_tag
  - lib/fdt.c:fdt_offset_ptr
  - lib/fdt.c:fdt_offset_ptr
  - lib/fdt.c:fdt_offset_ptr
  - lib/fdt.c:fdt_offset_ptr
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
  - lib/fdt.c:fdt_check_header
```
```
In lib/fdt_ro.c (ffffffe0008b0bf2)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_ro.c:fdt_get_phandle
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_getprop_by_offset
  - lib/fdt_ro.c:fdt_getprop_namelen
  - lib/fdt_ro.c:fdt_getprop_namelen
  - lib/fdt_ro.c:fdt_get_property_namelen
  - lib/fdt_ro.c:fdt_get_property_namelen_
  - lib/fdt_ro.c:fdt_get_property_by_offset
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_mem_rsv
  - lib/fdt_ro.c:fdt_mem_rsv
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_ro.c:fdt_get_string
```
```
In lib/fdt_rw.c (ffffffe0008b1efa)
Location: scripts/dtc/libfdt/libfdt.h:127
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
  - lib/fdt_rw.c:fdt_splice_
  - lib/fdt_rw.c:fdt_splice_
  - lib/fdt_rw.c:fdt_splice_
  - lib/fdt_rw.c:fdt_blocks_misordered_
  - lib/fdt_rw.c:fdt_blocks_misordered_
  - lib/fdt_rw.c:fdt_blocks_misordered_
  - lib/fdt_rw.c:fdt_blocks_misordered_
  - lib/fdt_rw.c:fdt_blocks_misordered_
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
