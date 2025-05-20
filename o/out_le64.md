# Function: <code>out_le64</code>

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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/xive/common.c (c0000000000bcc04)
Location: arch/powerpc/include/asm/io.h:181
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_cause_ipi
```
```
In arch/powerpc/platforms/powernv/eeh-powernv.c (c0000000000dc3d8)
Location: arch/powerpc/include/asm/io.h:181
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_set_inbB
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_set_inbA
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_set_outb
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e2a7c)
Location: arch/powerpc/include/asm/io.h:181
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
```
```
In lib/iomap.c (c0000000007e6b8c)
Location: arch/powerpc/include/asm/io.h:181
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (c000000000847d18)
Location: arch/powerpc/include/asm/io.h:181
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0c30)
Location: arch/powerpc/include/asm/io.h:181
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (c000000000a05d3c)
Location: arch/powerpc/include/asm/io.h:181
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
</details>
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
