# Function: <code>gpio_direction_output</code>

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
In drivers/pci/controller/dwc/pcie-kirin.c (ffff8000107367c8)
Location: include/asm-generic/gpio.h:74
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd3ec)
Location: include/asm-generic/gpio.h:74
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
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
In arch/arm/mach-mvebu/pm-board.c (c150e348)
Location: include/asm-generic/gpio.h:74
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
```
```
In drivers/tty/serial/omap-serial.c (c09a02a0)
Location: include/asm-generic/gpio.h:74
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab79f0)
Location: include/asm-generic/gpio.h:74
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
```
```
In sound/soc/soc-ac97.c (c0cbbd60)
Location: include/asm-generic/gpio.h:74
Inline: True
Inline callers:
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset
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
