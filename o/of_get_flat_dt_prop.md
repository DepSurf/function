# Function: <code>of_get_flat_dt_prop</code>

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
const void *of_get_flat_dt_prop(long unsigned int node, const char *name, int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aa898)
Location: drivers/of/fdt.c:710
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:early_init_dt_scan_usablemem
  - arch/arm64/mm/init.c:early_init_dt_scan_elfcorehdr
  - arch/arm/xen/enlighten.c:fdt_find_hyper_node
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/coherent.c:rmem_dma_setup
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffff8000114aa898-ffff8000114aa8e4: of_get_flat_dt_prop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *of_get_flat_dt_prop(long unsigned int node, const char *name, int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15aed9c)
Location: drivers/of/fdt.c:710
Inline: False
Direct callers:
  - arch/arm/kernel/devtree.c:setup_machine_fdt
  - arch/arm/mach-exynos/exynos.c:exynos_fdt_map_chipid
  - arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem
  - arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem
  - arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/coherent.c:rmem_dma_setup
  - kernel/dma/coherent.c:rmem_dma_setup
  - kernel/dma/coherent.c:rmem_dma_setup
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c15aed9c-c15aedd4: of_get_flat_dt_prop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *of_get_flat_dt_prop(long unsigned int node, const char *name, int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013ba72c)
Location: drivers/of/fdt.c:710
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/rtas.c:early_init_dt_scan_rtas
  - arch/powerpc/kernel/rtas.c:early_init_dt_scan_rtas
  - arch/powerpc/kernel/rtas.c:early_init_dt_scan_rtas
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:cpufeatures_deps_enable
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init
  - arch/powerpc/kernel/dt_cpu_ftrs.c:fdt_find_cpu_features
  - arch/powerpc/kernel/epapr_paravirt.c:early_init_dt_scan_epapr
  - arch/powerpc/mm/init_64.c:mmu_early_init_devtree
  - arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early
  - arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early
  - arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early
  - arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_pftsize
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_pftsize
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_page_sizes
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_page_sizes
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_seg_sizes
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_seg_sizes
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix_dt_scan_page_sizes
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix_dt_scan_page_sizes
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix_dt_scan_page_sizes
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
  - arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal
  - arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan
  - arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan
  - arch/powerpc/platforms/pseries/firmware.c:probe_fw_features
  - arch/powerpc/platforms/pseries/firmware.c:probe_fw_features
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan
  - kernel/dma/coherent.c:rmem_dma_setup
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c0000000013ba72c-c0000000013ba77c: of_get_flat_dt_prop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const void *of_get_flat_dt_prop(long unsigned int node, const char *name, int *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003ac1c)
Location: drivers/of/fdt.c:710
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/contiguous.c:rmem_cma_setup
  - kernel/dma/coherent.c:rmem_dma_setup
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:of_flat_dt_match_machine
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:of_flat_dt_get_machine_name
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffffffe00003ac1c-ffffffe00003ac60: of_get_flat_dt_prop (STB_GLOBAL)
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
