# Function: <code>pm_runtime_resume_and_get</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/arizona-irq.c (ffffffff817edf8b)
Location: include/linux/pm_runtime.h:397
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/usb/core/hub.c (ffffffff818a9a8a)
Location: include/linux/pm_runtime.h:397
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193e99a)
Location: include/linux/pm_runtime.h:407
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/mmc/core/sdio.c (ffffffff81a46633)
Location: include/linux/pm_runtime.h:407
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167ecc)
Location: include/linux/pm_runtime.h:436
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/clk/clk.c (ffffffff818aba32)
Location: include/linux/pm_runtime.h:436
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81a4d529)
Location: include/linux/pm_runtime.h:436
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81a50279)
Location: include/linux/pm_runtime.h:436
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a8104c)
Location: include/linux/pm_runtime.h:436
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
```
In drivers/usb/core/hub.c (ffffffff81a969d2)
Location: include/linux/pm_runtime.h:436
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb4203)
Location: include/linux/pm_runtime.h:436
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119c37c)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/clk/clk.c (ffffffff819f7132)
Location: include/linux/pm_runtime.h:440
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81bd7770)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/spi/spi-mem.c (ffffffff81bd93e9)
Location: include/linux/pm_runtime.h:440
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c19582)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58863)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae1cc)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/clk/clk.c (ffffffff81a3f332)
Location: include/linux/pm_runtime.h:440
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81c2e1bc)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fde9)
Location: include/linux/pm_runtime.h:440
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c805a2)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc31f3)
Location: include/linux/pm_runtime.h:440
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bddcc)
Location: include/linux/pm_runtime.h:438
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/clk/clk.c (ffffffff81a8ac62)
Location: include/linux/pm_runtime.h:438
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81ce0c0c)
Location: include/linux/pm_runtime.h:438
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2ca9)
Location: include/linux/pm_runtime.h:438
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d34f72)
Location: include/linux/pm_runtime.h:438
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7bad3)
Location: include/linux/pm_runtime.h:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
</details>
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
