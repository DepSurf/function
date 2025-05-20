# Function: <code>in_le64</code>

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
In arch/powerpc/sysdev/xive/common.c (c0000000000bcac8)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_esb_read
```
```
In arch/powerpc/sysdev/xive/native.c (c0000000000bfc4c)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_teardown_cpu
  - arch/powerpc/sysdev/xive/native.c:xive_native_setup_cpu
```
```
In arch/powerpc/platforms/powernv/rng.c (c00000000135cc78)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init
  - arch/powerpc/platforms/powernv/rng.c:powernv_get_random_long
```
```
In arch/powerpc/platforms/powernv/eeh-powernv.c (c0000000000dc4b0)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_get_inbB
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_get_inbA
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_get_outb
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e2980)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:vas_paste_crb
```
```
In arch/powerpc/platforms/powernv/vas-debug.c (c0000000000e4d20)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_show
```
```
In lib/iomap.c (c0000000007e6310)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (c000000000848e98)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0ec0)
Location: arch/powerpc/include/asm/io.h:182
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
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
