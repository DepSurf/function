# Function: <code>of_scan_flat_dt</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_scan_flat_dt(int (*it)(long unsigned int, const char *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aa688)
Location: drivers/of/fdt.c:629
Inline: False
Direct callers:
  - arch/arm64/kernel/acpi.c:acpi_boot_table_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm/xen/enlighten.c:xen_early_init
  - drivers/firmware/efi/efi.c:efi_get_fdt_params
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
ffff8000114aa688-ffff8000114aa788: of_scan_flat_dt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_scan_flat_dt(int (*it)(long unsigned int, const char *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15aeba4)
Location: drivers/of/fdt.c:629
Inline: False
Direct callers:
  - arch/arm/mach-exynos/exynos.c:exynos_init_io
  - arch/arm/mach-mvebu/board-v7.c:mvebu_memblock_reserve
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_reserve
  - drivers/firmware/efi/efi.c:efi_get_fdt_params
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
c15aeba4-c15aeca8: of_scan_flat_dt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_scan_flat_dt(int (*it)(long unsigned int, const char *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013ba474)
Location: drivers/of/fdt.c:629
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_get_first_memblock_info
  - arch/powerpc/kernel/prom.c:early_get_first_memblock_info
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init
  - arch/powerpc/kernel/epapr_paravirt.c:epapr_paravirt_early_init
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_devtree
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_devtree
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_devtree
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_initialize
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__early_init_devtree
  - arch/powerpc/platforms/pseries/firmware.c:pseries_probe_fw_features
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
c0000000013ba474-c0000000013ba5cc: of_scan_flat_dt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_scan_flat_dt(int (*it)(long unsigned int, const char *, int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003aa62)
Location: drivers/of/fdt.c:629
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_dt_scan_nodes
  - drivers/of/fdt.c:early_init_fdt_scan_reserved_mem
```
**Symbols:**

```
ffffffe00003aa62-ffffffe00003ab22: of_scan_flat_dt (STB_GLOBAL)
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
