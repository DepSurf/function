# Function: <code>dt_mem_next_cell</code>

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
u64 dt_mem_next_cell(int s, const __be32 **cellp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114ab014)
Location: drivers/of/fdt.c:985
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:early_init_dt_scan_usablemem
  - arch/arm64/mm/init.c:early_init_dt_scan_usablemem
  - arch/arm64/mm/init.c:early_init_dt_scan_elfcorehdr
  - arch/arm64/mm/init.c:early_init_dt_scan_elfcorehdr
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffff8000114ab014-ffff8000114ab050: dt_mem_next_cell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 dt_mem_next_cell(int s, const __be32 **cellp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15af574)
Location: drivers/of/fdt.c:985
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem
  - arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c15af574-c15af5c4: dt_mem_next_cell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 dt_mem_next_cell(int s, const __be32 **cellp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013bb070)
Location: drivers/of/fdt.c:985
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_drmem_lmb
  - arch/powerpc/kernel/prom.c:early_init_drmem_lmb
  - arch/powerpc/kernel/prom.c:early_init_drmem_lmb
  - arch/powerpc/mm/drmem.c:init_drmem_lmb_size
  - arch/powerpc/mm/drmem.c:read_drconf_v2_cell
  - arch/powerpc/mm/drmem.c:read_drconf_v1_cell
  - arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
c0000000013bb070-c0000000013bb0bc: dt_mem_next_cell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 dt_mem_next_cell(int s, const __be32 **cellp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003b326)
Location: drivers/of/fdt.c:985
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:early_init_dt_scan_memory
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
**Symbols:**

```
ffffffe00003b326-ffffffe00003b360: dt_mem_next_cell (STB_GLOBAL)
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
