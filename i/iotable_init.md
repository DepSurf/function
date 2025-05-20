# Function: <code>iotable_init</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iotable_init(struct map_desc *io_desc, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/mmu.c (c1508d28)
Location: arch/arm/mm/mmu.c:990
Inline: False
Direct callers:
  - arch/arm/kernel/bios32.c:pci_map_io_early
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mach-exynos/exynos.c:exynos_fdt_map_chipid
  - arch/arm/mach-hisi/hisilicon.c:hi3620_map_io
  - arch/arm/mach-imx/platsmp.c:imx_scu_map_io
  - arch/arm/mach-omap2/io.c:ti81xx_map_io
  - arch/arm/mach-omap2/io.c:dra7xx_map_io
  - arch/arm/mach-omap2/io.c:omap4_map_io
  - arch/arm/mach-omap2/io.c:am33xx_map_io
  - arch/arm/mach-omap2/io.c:omap3_map_io
  - arch/arm/mach-omap2/omap4-common.c:omap_barriers_init
  - arch/arm/mach-shmobile/setup-sh73a0.c:sh73a0_map_io
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_map_io
  - arch/arm/mach-tegra/io.c:tegra_map_common_io
```
**Symbols:**

```
c1508d28-c1508e24: iotable_init (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
