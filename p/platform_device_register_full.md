# Function: <code>platform_device_register_full</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154e4e0)
Location: drivers/base/platform.c:470
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_register
```
**Symbols:**

```
ffffffff8154e4e0-ffffffff8154e613: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815a02e0)
Location: drivers/base/platform.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815a02e0-ffffffff815a0410: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ce920)
Location: drivers/base/platform.c:504
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815ce920-ffffffff815cea50: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e33b0)
Location: drivers/base/platform.c:504
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff815e33b0-ffffffff815e34bb: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a560)
Location: drivers/base/platform.c:504
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff8164a560-ffffffff8164a66b: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685ad0)
Location: drivers/base/platform.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81685ad0-ffffffff81685bd9: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a5730)
Location: drivers/base/platform.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816a5730-ffffffff816a5855: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de6c0)
Location: drivers/base/platform.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816de6c0-ffffffff816de821: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81702970)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81702970-ffffffff81702ab0: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bcc30)
Location: drivers/base/platform.c:682
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_setup_clks
```
**Symbols:**

```
ffffffff817bcc30-ffffffff817bcd70: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1b20)
Location: drivers/base/platform.c:834
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_setup_clks
```
**Symbols:**

```
ffffffff817d1b20-ffffffff817d1c60: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b5550)
Location: drivers/base/platform.c:833
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff817b5550-ffffffff817b568c: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:797
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81d0337e-ffffffff81d03393: platform_device_register_full.cold (STB_LOCAL)
ffffffff8183ea50-ffffffff8183eb9c: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:806
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81ecbac1-ffffffff81ecbad6: platform_device_register_full.cold (STB_LOCAL)
ffffffff81981950-ffffffff81981aa8: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:806
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8209874a-ffffffff8209875f: platform_device_register_full.cold (STB_LOCAL)
ffffffff81aef600-ffffffff81aef758: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:806
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/acpi_processor.c:cpufreq_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff82119736-ffffffff8211974b: platform_device_register_full.cold (STB_LOCAL)
ffffffff81b3d9e0-ffffffff81b3db38: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:806
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/acpi_processor.c:cpufreq_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff821f76f8-ffffffff821f770d: platform_device_register_full.cold (STB_LOCAL)
ffffffff81b95520-ffffffff81b95678: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ee320)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
  - drivers/firmware/arm_sdei.c:sdei_init
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
  - drivers/firmware/efi/arm-init.c:register_gop_device
```
**Symbols:**

```
ffff8000108ee320-ffff8000108ee47c: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dc034)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_late
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_late
  - arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_late
  - arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_late
  - arch/arm/mach-imx/mach-imx7d.c:imx7d_init_late
  - arch/arm/mach-omap2/fb.c:omap_init_vrfb
  - arch/arm/mach-omap2/pm33xx-core.c:amx3_common_pm_init
  - arch/arm/mach-tegra/tegra.c:tegra_dt_init_late
  - arch/arm/mach-vexpress/spc.c:ve_spc_clk_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_register
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_init
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
  - drivers/firmware/efi/arm-init.c:register_gop_device
  - sound/soc/soc-utils.c:snd_soc_util_init
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
**Symbols:**

```
c09dc034-c09dc158: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000986f40)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - arch/powerpc/kernel/time.c:rtc_init
  - arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
c000000000986f40-c0000000009870f8: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000581436)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/edac/sifive_edac.c:sifive_edac_init
```
**Symbols:**

```
ffffffe000581436-ffffffe00058154e: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c80c0)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816c80c0-ffffffff816c8200: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a33c0)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816a33c0-ffffffff816a3500: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f6630)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff816f6630-ffffffff816f6770: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct platform_device *platform_device_register_full(const struct platform_device_info *pdevinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710ed0)
Location: drivers/base/platform.c:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
  - arch/x86/kernel/sysfb.c:sysfb_init
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
```
**Symbols:**

```
ffffffff81710ed0-ffffffff81711010: platform_device_register_full (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
