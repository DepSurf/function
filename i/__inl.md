# Function: <code>__inl</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f3272)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cca65)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff81822f36)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8188d015)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188e14f)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192966b)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81acabfb)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae1fc2)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81bc3e10)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81efd49b)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff834d01c7)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81e41983)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
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
In lib/iomap.c (ffffffff817e51a2)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff818ebe25)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff81953ff6)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff819d4a5c)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d57c3)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a86087)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c5523b)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6d9c2)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81d69480)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d70ccf)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff83f14046)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8201c013)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
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
In lib/iomap.c (ffffffff818251e2)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192f35c)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff8199a3f8)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8214399a)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:io_idle
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1d113)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad1757)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc7bb)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd4fce)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81dd4970)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81dde98f)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8373a7c6)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8209c6b3)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
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
In lib/iomap.c (ffffffff81876bf2)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread64_lo_hi
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32
```
```
In drivers/pci/pci-sysfs.c (ffffffff81977ccc)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/acpi/osl.c (ffffffff819e2878)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff822260ba)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:io_idle
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a68423)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b255b7)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d7152b)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d89fae)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81e8cac0)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read_slow
  - drivers/clocksource/acpi_pm.c:acpi_pm_read
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81e9489f)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8396f046)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff82173e93)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config
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
