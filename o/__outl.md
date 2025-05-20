# Function: <code>__outl</code>

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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102cb2e)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff816f2b70)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cc512)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81822fad)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188e157)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192966c)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81acabd2)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae4989)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81efd49f)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff834d01d0)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81e41bc6)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033cae)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff817e49d0)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff818ea732)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8195407d)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d57cb)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a86088)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c55212)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70549)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d70cd0)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff83f1404f)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8201c2b6)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033c3e)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81824a10)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192dca5)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8199a48d)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1d11b)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad1758)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc792)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd7b3a)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81dde990)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8373a7cf)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8209c956)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81039f3e)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81876420)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite64_lo_hi
  - lib/iomap.c:iowrite32be
  - lib/iomap.c:iowrite32
```
```
In drivers/pci/pci-sysfs.c (ffffffff81976625)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff819e290d)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a6842b)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b255b8)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d71502)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8cb4a)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81e948a0)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_power_off
```
```
In arch/x86/pci/direct.c (ffffffff8396f04f)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_check_type1
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff82174136)
Location: arch/x86/include/asm/shared/io.h:24
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:write_pci_config_16
  - arch/x86/pci/early.c:write_pci_config_byte
  - arch/x86/pci/early.c:write_pci_config
  - arch/x86/pci/early.c:write_pci_config
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
