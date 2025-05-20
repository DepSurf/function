# Function: <code>mmiocpy</code>

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

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - fs/libfs.c:memory_read_from_io_buffer
  - fs/pstore/ram_core.c:persistent_ram_write
  - fs/pstore/ram_core.c:persistent_ram_write
  - fs/pstore/ram_core.c:persistent_ram_save_old
  - fs/pstore/ram_core.c:persistent_ram_save_old
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:edma_execute
  - drivers/dma/ti/edma.c:edma_free_slot
  - drivers/dma/ti/edma.c:edma_alloc_slot
  - drivers/misc/sram.c:sram_write
  - drivers/misc/sram.c:sram_read
  - drivers/mtd/maps/map_funcs.c:simple_map_copy_to
  - drivers/mtd/maps/map_funcs.c:simple_map_copy_from
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
  - sound/core/memory.c:copy_from_user_toio
  - sound/core/memory.c:copy_to_user_fromio
```
**Symbols:**

```
c0e7e0a0-c0e7e3d0: mmiocpy (STB_GLOBAL)
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
