# Function: <code>platform_device_register_resndata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81f6cc40)
Location: include/linux/platform_device.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff81f74a35)
Location: include/linux/platform_device.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff81f74df7)
Location: include/linux/platform_device.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff8118c0a5)
Location: include/linux/platform_device.h:94
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81487e69)
Location: include/linux/platform_device.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c0e80)
Location: include/linux/platform_device.h:94
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81fa8583)
Location: include/linux/platform_device.h:94
Inline: True
```
```
In drivers/mfd/adp5520.c (ffffffff81593305)
Location: include/linux/platform_device.h:94
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81fafeb1)
Location: include/linux/platform_device.h:94
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/usb/phy/phy-generic.c (ffffffff81621286)
Location: include/linux/platform_device.h:94
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_register
```
**Symbols:**

```
ffffffff814c0e80-ffffffff814c0ee2: platform_device_register_resndata.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81f95031)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff81f9d1bd)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff81f9d57f)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff8119ece1)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6d17)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81511460)
Location: include/linux/platform_device.h:95
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81fd498b)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/mfd/adp5520.c (ffffffff815e8145)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81fdca57)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81511460-ffffffff815114c2: platform_device_register_resndata.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81fd068d)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff81fd874c)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff81fd8b0b)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff811ae749)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f9382)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff817855fc)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d420)
Location: include/linux/platform_device.h:95
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff820123b6)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/mfd/adp5520.c (ffffffff81614f55)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8201a641)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8153d420-ffffffff8153d482: platform_device_register_resndata.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff820b10a4)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff820b9569)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff820b995f)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff820c619f)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815086a6)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8150d077)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815510c0)
Location: include/linux/platform_device.h:95
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff820f3fd1)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/mfd/adp5520.c (ffffffff81628f45)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff820fc6ba)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff82106a1d)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815510c0-ffffffff81551122: platform_device_register_resndata.constprop.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826b78b6)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff826bff05)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff826c030e)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff826ce840)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8154aa92)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81550397)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b48e0)
Location: include/linux/platform_device.h:95
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff826fd6be)
Location: include/linux/platform_device.h:95
Inline: True
```
```
In drivers/mfd/adp5520.c (ffffffff8169185b)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82705e2f)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8271037a)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815b48e0-ffffffff815b4942: platform_device_register_resndata.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e15c8)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff826ea13c)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff826ea52c)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff826f8f53)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580f7e)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815810dc)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82720993)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ed336)
Location: include/linux/platform_device.h:95
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff827279bb)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff816cd991)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8272fc90)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8273a618)
Location: include/linux/platform_device.h:95
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815ed336-ffffffff815ed397: platform_device_register_resndata.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289758a)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828a0da8)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828a11d5)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff828afe2d)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598c04)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8159927c)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828d8929)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607c1c)
Location: include/linux/platform_device.h:96
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828dfc02)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff816eef51)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff828e894d)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff828f45f9)
Location: include/linux/platform_device.h:96
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81607c1c-ffffffff81607c7d: platform_device_register_resndata.constprop.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828af135)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828b8ff9)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828b9425)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff828c89c7)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c9f3f)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff815ca63f)
Location: include/linux/platform_device.h:99
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815d0569)
Location: include/linux/platform_device.h:99
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163ba3a)
Location: include/linux/platform_device.h:99
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828fa650)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff817285e5)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82903288)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8290fec1)
Location: include/linux/platform_device.h:99
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8163ba3a-ffffffff8163ba9d: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b246e)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828bf4e7)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828bf913)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff8113f844)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815eb15f)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff815eb84f)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815f17d9)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165dee4)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff82903543)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff8174c835)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8290c485)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff82919bd5)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8165dee4-ffffffff8165df47: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82cd75b4)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff82ce37da)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff82ce3c06)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff8114e372)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816964f2)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff81697280)
Location: include/linux/platform_device.h:115
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8169d7a7)
Location: include/linux/platform_device.h:115
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170cff6)
Location: include/linux/platform_device.h:115
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff82d1a3e4)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff8180a886)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82d21084)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff819bb19b)
Location: include/linux/platform_device.h:115
Inline: True
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff819c5c6b)
Location: include/linux/platform_device.h:115
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_setup_clks
```
**Symbols:**

```
ffffffff81697280-ffffffff816972e4: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff8169d7a7-ffffffff8169d809: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff8170cff6-ffffffff8170d059: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82fc35ed)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff82fd0ad3)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff82fd0eff)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff8114a602)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b3642)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff816b42d0)
Location: include/linux/platform_device.h:124
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81c0271f)
Location: include/linux/platform_device.h:124
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81c046b7)
Location: include/linux/platform_device.h:124
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff830080e4)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff8181a1b6)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8300ee6f)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81c2b6ec)
Location: include/linux/platform_device.h:124
Inline: True
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c2d632)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_setup_clks
```
**Symbols:**

```
ffffffff816b42d0-ffffffff816b4334: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81c0271f-ffffffff81c02781: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81c046b7-ffffffff81c0471a: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cdbcf)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff831db7a5)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff831dbbcb)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff8114babf)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816958c5)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff81696500)
Location: include/linux/platform_device.h:124
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81bf411e)
Location: include/linux/platform_device.h:124
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81bf63a0)
Location: include/linux/platform_device.h:124
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff83212be4)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff817fd8d6)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83219e53)
Location: include/linux/platform_device.h:124
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81c1db85)
Location: include/linux/platform_device.h:124
Inline: True
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81c1f9ca)
Location: include/linux/platform_device.h:124
Inline: True
```
**Symbols:**

```
ffffffff81696500-ffffffff81696564: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81bf411e-ffffffff81bf4180: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81bf63a0-ffffffff81bf6403: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff832afd31)
Location: include/linux/platform_device.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff832beb3e)
Location: include/linux/platform_device.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff8116f7cf)
Location: include/linux/platform_device.h:121
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170b5f8)
Location: include/linux/platform_device.h:121
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff8170c2a0)
Location: include/linux/platform_device.h:121
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81cf0f42)
Location: include/linux/platform_device.h:121
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81cf4ecc)
Location: include/linux/platform_device.h:121
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff832fbea2)
Location: include/linux/platform_device.h:121
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff81887676)
Location: include/linux/platform_device.h:121
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83303928)
Location: include/linux/platform_device.h:121
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81d2efef)
Location: include/linux/platform_device.h:121
Inline: True
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d31246)
Location: include/linux/platform_device.h:121
Inline: True
```
**Symbols:**

```
ffffffff8170c2a0-ffffffff8170c304: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81cf0f42-ffffffff81cf0fa4: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81cf4ecc-ffffffff81cf4f2f: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83460dc9)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff8347091a)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff811a3d12)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81839b71)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff8183a900)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81eb8ded)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81ebd037)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff834b4971)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff819d0631)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff834bc8f6)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81efb49f)
Location: include/linux/platform_device.h:125
Inline: True
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81efd697)
Location: include/linux/platform_device.h:125
Inline: True
```
**Symbols:**

```
ffffffff8183a900-ffffffff8183a970: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81eb8ded-ffffffff81eb8e59: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81ebd037-ffffffff81ebd0a4: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82c59)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff83e97731)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff811e3586)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8196f181)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff8196ff60)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81979c20)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a12490)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff83eefc04)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff81b49868)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83efad86)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff83f0702d)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81d713a9)
Location: include/linux/platform_device.h:125
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76b00)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff8196ff60-ffffffff8196ffd0: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81979c20-ffffffff81979c8f: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81a12490-ffffffff81a124fe: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81d76b00-ffffffff81d76b70: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a5f8b)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff836bb2e1)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff811f7bd6)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_processor.c (ffffffff819ab619)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:cpufreq_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819b5701)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff819b6520)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff819c06b0)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b4c0)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff837157c4)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff81b9ccb5)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83720ab6)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff8372d07f)
Location: include/linux/platform_device.h:125
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81ddf05c)
Location: include/linux/platform_device.h:125
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4a40)
Location: include/linux/platform_device.h:125
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff819b6520-ffffffff819b6590: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff819c06b0-ffffffff819c071f: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81a5b4c0-ffffffff81a5b52e: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81de4a40-ffffffff81de4ab0: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff838d6047)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff838ebcc1)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff8120dd76)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f5a49)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:cpufreq_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819ffa7e)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff81a00aa0)
Location: include/linux/platform_device.h:153
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81a0b130)
Location: include/linux/platform_device.h:153
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aac930)
Location: include/linux/platform_device.h:153
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff83949224)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff81bf0ca5)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff839549b6)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff839614c8)
Location: include/linux/platform_device.h:153
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81e94f9c)
Location: include/linux/platform_device.h:153
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ab30)
Location: include/linux/platform_device.h:153
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81a00aa0-ffffffff81a00b10: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81a0b130-ffffffff81a0b19f: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81aac930-ffffffff81aac99e: platform_device_register_resndata.constprop.0 (STB_LOCAL)
ffffffff81e9ab30-ffffffff81e9aba0: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a9fd0)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_watchdog.c (ffff80001077c6a0)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/acpi/arm64/gtdt.c (ffff8000107b2abc)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/soc/imx/soc-imx8.c (ffff800011490144)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
```
```
In drivers/soc/imx/soc-imx-scu.c (ffff800011490248)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826cfc)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/mfd/adp5520.c (ffff80001094ad0c)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffff80001149baa8)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (ffff8000114a1f60)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/firmware/arm_sdei.c (ffff8000114a32a4)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_init
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e9d4)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
```
```
In drivers/firmware/efi/arm-init.c (ffff8000114a7210)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:register_gop_device
```
**Symbols:**

```
ffff800010826cfc-ffff800010826d80: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/mach-imx/mach-imx6q.c (c150f908)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_late
```
```
In arch/arm/mach-imx/mach-imx6sl.c (c150fab4)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_late
```
```
In arch/arm/mach-imx/mach-imx6sx.c (c150fc58)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_late
```
```
In arch/arm/mach-imx/mach-imx6ul.c (c150fdc0)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_late
```
```
In arch/arm/mach-imx/mach-imx7d.c (c150ff48)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx7d.c:imx7d_init_late
```
```
In arch/arm/mach-imx/devices/platform-gpio-mxc.c (c033497c)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - arch/arm/mach-imx/devices/platform-gpio-mxc.c:mxc_register_gpio
```
```
In arch/arm/mach-imx/devices/platform-imx-dma.c (c0334a08)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - arch/arm/mach-imx/devices/platform-imx-dma.c:imx_add_imx_sdma
  - arch/arm/mach-imx/devices/platform-imx-dma.c:imx_add_imx_dma
```
```
In arch/arm/mach-omap2/fb.c (c1512708)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-omap2/fb.c:omap_init_vrfb
```
```
In arch/arm/mach-tegra/tegra.c (c151aacc)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-tegra/tegra.c:tegra_dt_init_late
```
```
In arch/arm/mach-vexpress/spc.c (c151b100)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_clk_init
```
```
In kernel/time/alarmtimer.c (c03f4d54)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In fs/pstore/ram.c (c06d7170)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/soc/imx/soc-imx8.c (c158fc70)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
```
```
In drivers/soc/imx/soc-imx-scu.c (c158fd7c)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
```
```
In drivers/virtio/virtio_mmio.c (c0944d00)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/mfd/adp5520.c (c0a339a4)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (c159cd18)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/usb/phy/phy-generic.c (c0b0bc54)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_register
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (c15a3f84)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/cpufreq/mvebu-cpufreq.c (c15a41d8)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
```
```
In drivers/cpufreq/tegra124-cpufreq.c (c15a42fc)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init
```
```
In drivers/cpufreq/ti-cpufreq.c (c0c01084)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_init
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
```
```
In drivers/firmware/efi/arm-init.c (c15a9cc4)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:register_gop_device
```
```
In sound/soc/soc-utils.c (c15b2cf8)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - sound/soc/soc-utils.c:snd_soc_util_init
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0a94)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
**Symbols:**

```
c033497c-c0334a08: platform_device_register_resndata.constprop.0 (STB_LOCAL)
c0334a08-c0334aa4: platform_device_register_resndata.constprop.0 (STB_LOCAL)
c0944d00-c0944d90: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/time.c (c000000001348b88)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:rtc_init
```
```
In arch/powerpc/platforms/powernv/opal-rtc.c (c00000000135c350)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init
```
```
In kernel/time/alarmtimer.c (c00000000020ce90)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d2954)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (c0000000013a96f4)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (c0000000009f6664)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (c0000000013afedc)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
c0000000008d2954-c0000000008d2a00: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000135230)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d2ee)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/mfd/adp5520.c (ffffffe0005bc59c)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffe000034c84)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/edac/sifive_edac.c (ffffffe000039410)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/edac/sifive_edac.c:sifive_edac_init
```
**Symbols:**

```
ffffffe00051d2ee-ffffffe00051d34e: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828a048d)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828aa4bd)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828aa8e9)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff81137ff4)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815e0469)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81623d84)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828ead2a)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff828f3e42)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff828fecde)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81623d84-ffffffff81623de7: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289869a)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828a2786)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828a2bb5)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff8112aa44)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c5b7f)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff815c626f)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815cbae9)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816183d4)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828e21b7)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff828eb2ed)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff828f6841)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816183d4-ffffffff81618437: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3450)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828bd3bc)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828bd7e8)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff81135d14)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815df43f)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff815dfb2f)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815e5ab9)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651d24)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828fe866)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff8173fcf5)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82907880)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff82913f70)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81651d24-ffffffff81651d87: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b347e)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828c0509)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828c0935)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/time/alarmtimer.c (ffffffff81142764)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f92ff)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_apd.c (ffffffff815f99ef)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815ff969)
Location: include/linux/platform_device.h:105
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166c3b4)
Location: include/linux/platform_device.h:105
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff829045a5)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/mfd/adp5520.c (ffffffff8175b135)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8290d4e7)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff8291ac37)
Location: include/linux/platform_device.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8166c3b4-ffffffff8166c417: platform_device_register_resndata.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
