# Function: <code>platform_device_register_simple</code>

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
Location: include/linux/platform_device.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff81f74a35)
Location: include/linux/platform_device.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff8118c0a4)
Location: include/linux/platform_device.h:135
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81487e69)
Location: include/linux/platform_device.h:135
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81fa8583)
Location: include/linux/platform_device.h:135
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81fafeb1)
Location: include/linux/platform_device.h:135
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/usb/phy/phy-generic.c (ffffffff81621286)
Location: include/linux/platform_device.h:135
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_register
```
**Symbols:**

```
ffffffff8118c0a4-ffffffff8118c0f4: platform_device_register_simple.constprop.5 (STB_LOCAL)
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
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff81f9d1bd)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff8119ece0)
Location: include/linux/platform_device.h:136
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6d17)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81fd498b)
Location: include/linux/platform_device.h:136
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81fdca57)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8119ece0-ffffffff8119ed30: platform_device_register_simple.constprop.6 (STB_LOCAL)
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
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff81fd874c)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff811ae748)
Location: include/linux/platform_device.h:136
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f9382)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff817855f8)
Location: include/linux/platform_device.h:136
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff820123b6)
Location: include/linux/platform_device.h:136
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8201a641)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff811ae748-ffffffff811ae798: platform_device_register_simple.constprop.12 (STB_LOCAL)
ffffffff817855f8-ffffffff81785652: platform_device_register_simple.constprop.3 (STB_LOCAL)
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
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff820b9569)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff820c619f)
Location: include/linux/platform_device.h:136
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815086a6)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8150d073)
Location: include/linux/platform_device.h:136
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff820f3fd1)
Location: include/linux/platform_device.h:136
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff820fc6ba)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8150d073-ffffffff8150d0d5: platform_device_register_simple.constprop.3 (STB_LOCAL)
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
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff826bff05)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff826ce840)
Location: include/linux/platform_device.h:136
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8154aa92)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff81550393)
Location: include/linux/platform_device.h:136
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff826fd6be)
Location: include/linux/platform_device.h:136
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82705e2f)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81550393-ffffffff815503f5: platform_device_register_simple.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e15c8)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff826ea13c)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff826f8f53)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580f7e)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82720993)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff827279bb)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8272fc90)
Location: include/linux/platform_device.h:136
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289758a)
Location: include/linux/platform_device.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828a0da8)
Location: include/linux/platform_device.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff828afe2d)
Location: include/linux/platform_device.h:137
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598c04)
Location: include/linux/platform_device.h:137
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff828d8929)
Location: include/linux/platform_device.h:137
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828dfc02)
Location: include/linux/platform_device.h:137
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff828e894d)
Location: include/linux/platform_device.h:137
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
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
Location: include/linux/platform_device.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828b8ff9)
Location: include/linux/platform_device.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/time/alarmtimer.c (ffffffff828c89c7)
Location: include/linux/platform_device.h:140
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c9f3f)
Location: include/linux/platform_device.h:140
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815d054a)
Location: include/linux/platform_device.h:140
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828fa650)
Location: include/linux/platform_device.h:140
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82903288)
Location: include/linux/platform_device.h:140
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815d054a-ffffffff815d05ac: platform_device_register_simple.constprop.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828bf4e7)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815eb15f)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815f17ba)
Location: include/linux/platform_device.h:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff82903543)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8290c485)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815f17ba-ffffffff815f181c: platform_device_register_simple.constprop.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff82ce37da)
Location: include/linux/platform_device.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816964f2)
Location: include/linux/platform_device.h:156
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82d12211)
Location: include/linux/platform_device.h:156
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff82d1a3e4)
Location: include/linux/platform_device.h:156
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82d21084)
Location: include/linux/platform_device.h:156
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff819bb17c)
Location: include/linux/platform_device.h:156
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff819bb17c-ffffffff819bb1cc: platform_device_register_simple.constprop.0.isra.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff82fd0ad3)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b3642)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff82fffce5)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff830080e4)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8300ee6f)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81c2b6cd)
Location: include/linux/platform_device.h:165
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81c2b6cd-ffffffff81c2b71d: platform_device_register_simple.constprop.0.isra.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff831db7a5)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816958c5)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8320adce)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff83212be4)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83219e53)
Location: include/linux/platform_device.h:165
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81c1db66)
Location: include/linux/platform_device.h:165
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81c1db66-ffffffff81c1dbb6: platform_device_register_simple.constprop.0.isra.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff832beb3e)
Location: include/linux/platform_device.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170b5f8)
Location: include/linux/platform_device.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff832f3313)
Location: include/linux/platform_device.h:162
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff832fbea2)
Location: include/linux/platform_device.h:162
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83303928)
Location: include/linux/platform_device.h:162
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81d2efd0)
Location: include/linux/platform_device.h:162
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81d2efd0-ffffffff81d2f020: platform_device_register_simple.constprop.0.isra.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff8347091a)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81839b71)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff834ab427)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff834b4971)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff834bc8f6)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81efb480)
Location: include/linux/platform_device.h:166
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81efb480-ffffffff81efb4da: platform_device_register_simple.constprop.0.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82c59)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff83e97731)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8196f181)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff83ee382b)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff83eefc04)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83efad86)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff83f0702d)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a5f8b)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff836bb2e1)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_processor.c (ffffffff819ab619)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:cpufreq_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819b5701)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8370921f)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff837157c4)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff83720ab6)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff8372d07f)
Location: include/linux/platform_device.h:166
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff838d6047)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff838ebcc1)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f5a49)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:cpufreq_add_device
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819ffa7e)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8393c67f)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff83949224)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff839549b6)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/efi/efi.c (ffffffff839614c8)
Location: include/linux/platform_device.h:194
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
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
In drivers/acpi/acpi_watchdog.c (ffff80001077c674)
Location: include/linux/platform_device.h:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/acpi/arm64/gtdt.c (ffff8000107b2a94)
Location: include/linux/platform_device.h:146
Inline: True
Direct callers:
  - drivers/acpi/arm64/gtdt.c:gtdt_import_sbsa_gwdt
```
```
In drivers/soc/imx/soc-imx8.c (ffff800011490144)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
```
```
In drivers/soc/imx/soc-imx-scu.c (ffff800011490248)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/platform_device.h:146
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffff80001149baa8)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/firmware/arm_sdei.c (ffff8000114a32a4)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_init
```
**Symbols:**

```
ffff80001077c674-ffff80001077c6f0: platform_device_register_simple.constprop.0 (STB_LOCAL)
ffff8000107b2a94-ffff8000107b2b0c: platform_device_register_simple.constprop.0 (STB_LOCAL)
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
In arch/arm/mach-imx/mach-imx6q.c (c150f908)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_late
```
```
In arch/arm/mach-imx/mach-imx6sl.c (c150fab4)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_late
```
```
In arch/arm/mach-imx/mach-imx6sx.c (c150fc58)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_late
```
```
In arch/arm/mach-imx/mach-imx6ul.c (c150fdc0)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_late
```
```
In arch/arm/mach-imx/mach-imx7d.c (c150ff48)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx7d.c:imx7d_init_late
```
```
In arch/arm/mach-tegra/tegra.c (c151aacc)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/arm/mach-tegra/tegra.c:tegra_dt_init_late
```
```
In arch/arm/mach-vexpress/spc.c (c151b100)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_clk_init
```
```
In drivers/soc/imx/soc-imx8.c (c158fc70)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
```
```
In drivers/soc/imx/soc-imx-scu.c (c158fd7c)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/platform_device.h:146
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (c159cd18)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/usb/phy/phy-generic.c (c0b0bc54)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_register
```
```
In drivers/cpufreq/mvebu-cpufreq.c (c15a41d8)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
```
```
In drivers/cpufreq/tegra124-cpufreq.c (c15a42fc)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init
```
```
In drivers/cpufreq/ti-cpufreq.c (c0c01254)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
```
```
In sound/soc/soc-utils.c (c15b2cf8)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - sound/soc/soc-utils.c:snd_soc_util_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/opal-rtc.c (c00000000135c350)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init
```
```
In drivers/char/tpm/tpm_tis.c (c0000000013a96f4)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (c0000000013afedc)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/platform_device.h:146
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffe000034c84)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
```
In drivers/edac/sifive_edac.c (ffffffe000039410)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/edac/sifive_edac.c:sifive_edac_init
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
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828aa4bd)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815e044a)
Location: include/linux/platform_device.h:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828ead2a)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff828f3e42)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815e044a-ffffffff815e04ac: platform_device_register_simple.constprop.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828a2786)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c5b7f)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815cbaca)
Location: include/linux/platform_device.h:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828e21b7)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff828eb2ed)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815cbaca-ffffffff815cbb2c: platform_device_register_simple.constprop.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828bd3bc)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815df43f)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815e5a9a)
Location: include/linux/platform_device.h:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff828fe866)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff82907880)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815e5a9a-ffffffff815e5afc: platform_device_register_simple.constprop.0 (STB_LOCAL)
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
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/pcspeaker.c (ffffffff828c0509)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f92ff)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff815ff94a)
Location: include/linux/platform_device.h:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff829045a5)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:init_tis
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8290d4e7)
Location: include/linux/platform_device.h:146
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815ff94a-ffffffff815ff9ac: platform_device_register_simple.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
