# Function: <code>platform_driver_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154df80)
Location: drivers/base/platform.c:610
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_exit
  - drivers/gpio/gpio-palmas.c:palmas_gpio_exit
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_exit
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_exit
  - drivers/gpio/gpio-zx.c:zx_gpio_driver_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/video/fbdev/efifb.c:efifb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/acpi/apei/ghes.c:ghes_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/syscon.c:syscon_exit
  - drivers/nvdimm/e820.c:e820_pmem_exit
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/power/charger-manager.c:charger_manager_cleanup
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
```
**Symbols:**

```
ffffffff8154df80-ffffffff8154df94: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159fd9c)
Location: drivers/base/platform.c:630
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/syscon.c:syscon_exit
  - drivers/nvdimm/e820.c:e820_pmem_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/power/charger-manager.c:charger_manager_cleanup
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
```
**Symbols:**

```
ffffffff8159fd50-ffffffff8159fd64: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ce3dc)
Location: drivers/base/platform.c:644
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/syscon.c:syscon_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
```
**Symbols:**

```
ffffffff815ce390-ffffffff815ce3a4: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e2d69)
Location: drivers/base/platform.c:644
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/syscon.c:syscon_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
```
**Symbols:**

```
ffffffff815e2d20-ffffffff815e2d34: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81649f19)
Location: drivers/base/platform.c:644
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/pinctrl/intel/pinctrl-cannonlake.c:cnl_pinctrl_driver_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/syscon.c:syscon_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
```
**Symbols:**

```
ffffffff81649ed0-ffffffff81649ee4: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816854ad)
Location: drivers/base/platform.c:642
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/syscon.c:syscon_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/i2c/busses/i2c-amd-platdrv.c:amd_i2c_plat_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
```
**Symbols:**

```
ffffffff81685460-ffffffff81685474: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a511d)
Location: drivers/base/platform.c:644
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/htc-i2cpld.c:htcpld_core_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/syscon.c:syscon_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
```
**Symbols:**

```
ffffffff816a50d0-ffffffff816a50e4: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de0b4)
Location: drivers/base/platform.c:684
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff816de070-ffffffff816de084: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81702274)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff81702230-ffffffff81702244: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bbe14)
Location: drivers/base/platform.c:810
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_driver_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff817bbdd0-ffffffff817bbde4: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d0974)
Location: drivers/base/platform.c:903
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_driver_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff817d0930-ffffffff817d0944: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4394)
Location: drivers/base/platform.c:902
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff817b4350-ffffffff817b4364: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183d581)
Location: drivers/base/platform.c:866
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff8183d540-ffffffff8183d554: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81980221)
Location: drivers/base/platform.c:875
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan_core.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff819801e0-ffffffff819801fa: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aedc31)
Location: drivers/base/platform.c:875
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan_core.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff81aedbe0-ffffffff81aedbfa: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3bff1)
Location: drivers/base/platform.c:875
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan_core.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff81b3bfa0-ffffffff81b3bfba: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b93b41)
Location: drivers/base/platform.c:875
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_driver_exit
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_driver_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/acpi/ac.c:acpi_ac_exit
  - drivers/acpi/fan_core.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/kgdboc.c:exit_kgdboc
  - drivers/tty/serial/kgdboc.c:init_kgdboc
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/gpu/drm/tiny/simpledrm.c:simpledrm_platform_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
```
**Symbols:**

```
ffffffff81b93af0-ffffffff81b93b0a: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ed84c)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_platform_driver_exit
  - drivers/irqchip/irq-renesas-irqc.c:irqc_exit
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_driver_exit
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_driver_exit
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_driver_exit
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_driver_exit
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_driver_init
  - drivers/bus/imx-weim.c:weim_driver_exit
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_driver_exit
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_exit
  - drivers/phy/phy-xgene.c:xgene_phy_driver_exit
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_driver_exit
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-single.c:pcs_driver_exit
  - drivers/pinctrl/actions/pinctrl-s700.c:s700_pinctrl_exit
  - drivers/pinctrl/actions/pinctrl-s900.c:s900_pinctrl_exit
  - drivers/pinctrl/sprd/pinctrl-sprd-sc9860.c:sprd_pinctrl_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/pci/controller/pcie-altera.c:altera_pcie_driver_exit
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_exit
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_driver_exit
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_platform_driver_exit
  - drivers/video/fbdev/mx3fb.c:mx3fb_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_driver_exit
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clk_driver_exit
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clk_driver_exit
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clk_driver_exit
  - drivers/clk/zynqmp/clkc.c:zynqmp_clock_driver_exit
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_driver_exit
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_driver_exit
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_driver_exit
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_driver_exit
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_driver_init
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_driver_exit
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_driver_init
  - drivers/soc/fsl/guts.c:fsl_guts_exit
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_driver_exit
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_platform_driver_exit
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_power_domain_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_dw.c:dw8250_platform_driver_exit
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_platform_driver_exit
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_exit
  - drivers/tty/serial/amba-pl011.c:pl011_exit
  - drivers/tty/serial/imx.c:imx_uart_exit
  - drivers/tty/serial/meson_uart.c:meson_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/msm_serial.c:msm_serial_exit
  - drivers/tty/serial/owl-uart.c:owl_uart_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/iommu/qcom_iommu.c:qcom_iommu_init
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_driver_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/altera-sysmgr.c:altr_sysmgr_exit
  - drivers/ata/ahci_imx.c:imx_ahci_driver_exit
  - drivers/spi/spi-fsl-spi.c:fsl_spi_exit
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_driver_exit
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdiomux_iproc_driver_exit
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_enet_driver_exit
  - drivers/net/ethernet/freescale/fec_main.c:fec_driver_exit
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_driver_exit
  - drivers/net/ethernet/freescale/fman/fman.c:fman_unload
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_unload
  - drivers/net/ethernet/smsc/smc91x.c:smc_driver_exit
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_module_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-orion.c:ehci_orion_cleanup
  - drivers/rtc/rtc-efi.c:efi_rtc_driver_exit
  - drivers/rtc/rtc-mv.c:mv_rtc_driver_exit
  - drivers/rtc/rtc-xgene.c:xgene_rtc_driver_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_exit_driver
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_driver_exit
  - drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_exit
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_exit
  - drivers/power/reset/gpio-restart.c:gpio_restart_driver_exit
  - drivers/power/reset/hisi-reboot.c:hisi_reboot_driver_exit
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/thermal/armada_thermal.c:armada_thermal_driver_exit
  - drivers/edac/altera_edac.c:altr_edac_a10_driver_exit
  - drivers/edac/altera_edac.c:altr_edac_device_driver_exit
  - drivers/edac/altera_edac.c:altr_edac_driver_exit
  - drivers/edac/altera_edac.c:altr_sdram_edac_driver_exit
  - drivers/cpufreq/cpufreq-dt.c:dt_cpufreq_platdrv_exit
  - drivers/firmware/raspberrypi.c:rpi_firmware_driver_exit
  - drivers/firmware/ti_sci.c:ti_sci_driver_exit
  - drivers/firmware/arm_scmi/driver.c:scmi_driver_exit
  - drivers/firmware/meson/meson_sm.c:meson_sm_driver_exit
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_driver_exit
  - drivers/clocksource/sh_cmt.c:sh_cmt_exit
  - drivers/clocksource/sh_tmu.c:sh_tmu_exit
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_driver_exit
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_driver_exit
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_driver_exit
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_exit
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_driver_exit
  - drivers/memory/mtk-smi.c:mtk_smi_init
  - drivers/perf/arm-cci.c:cci_pmu_driver_exit
  - drivers/perf/arm-ccn.c:arm_ccn_exit
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_exit
  - drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_driver_exit
```
**Symbols:**

```
ffff8000108ed7d0-ffff8000108ed7fc: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09db6ec)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - arch/arm/plat-omap/dma.c:omap_system_dma_exit
  - fs/pstore/ram.c:ramoops_exit
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_exit
  - drivers/irqchip/irq-renesas-irqc.c:irqc_exit
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_exit
  - drivers/bus/imx-weim.c:weim_driver_exit
  - drivers/bus/omap_l3_smx.c:omap3_l3_exit
  - drivers/bus/omap_l3_noc.c:omap_l3_exit
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_driver_exit
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_exit
  - drivers/bus/ti-sysc.c:sysc_exit
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_driver_exit
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_driver_exit
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_driver_exit
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_driver_exit
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_driver_exit
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-single.c:pcs_driver_exit
  - drivers/pinctrl/actions/pinctrl-s700.c:s700_pinctrl_exit
  - drivers/pinctrl/actions/pinctrl-s900.c:s900_pinctrl_exit
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_driver_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-omap.c:omap_gpio_exit
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_exit
  - drivers/gpio/gpio-twl6040.c:gpo_twl6040_driver_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/pwm/pwm-tipwmss.c:pwmss_driver_exit
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_driver_exit
  - drivers/pci/controller/pcie-altera.c:altera_pcie_driver_exit
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_exit
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_driver_exit
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_platform_driver_exit
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_driver_exit
  - drivers/video/fbdev/mx3fb.c:mx3fb_exit
  - drivers/amba/tegra-ahb.c:tegra_ahb_driver_exit
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_driver_exit
  - drivers/clk/ti/adpll.c:ti_adpll_exit
  - drivers/dma/tegra20-apb-dma.c:tegra_dmac_driver_exit
  - drivers/dma/ti/edma.c:edma_exit
  - drivers/dma/ti/edma.c:edma_exit
  - drivers/dma/ti/omap-dma.c:omap_dma_exit
  - drivers/soc/fsl/guts.c:fsl_guts_exit
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/regulator/fixed.c:regulator_fixed_voltage_exit
  - drivers/regulator/ti-abb-regulator.c:ti_abb_driver_exit
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_exit
  - drivers/regulator/twl-regulator.c:twlreg_exit
  - drivers/regulator/twl6030-regulator.c:twlreg_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_platform_driver_exit
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_exit
  - drivers/tty/serial/amba-pl011.c:pl011_exit
  - drivers/tty/serial/imx.c:imx_uart_exit
  - drivers/tty/serial/meson_uart.c:meson_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/msm_serial.c:msm_serial_exit
  - drivers/tty/serial/omap-serial.c:serial_omap_exit
  - drivers/tty/serial/owl-uart.c:owl_uart_exit
  - drivers/tty/serial/rda-uart.c:rda_uart_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/iommu/omap-iommu.c:omap_iommu_init
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
  - drivers/iommu/qcom_iommu.c:qcom_iommu_init
  - drivers/mfd/sm501.c:sm501_base_exit
  - drivers/mfd/t7l66xb.c:t7l66xb_platform_driver_exit
  - drivers/mfd/tc6387xb.c:tc6387xb_platform_driver_exit
  - drivers/mfd/tc6393xb.c:tc6393xb_exit
  - drivers/mfd/twl4030-power.c:twl4030_power_driver_exit
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/mfd/omap-usb-host.c:omap_usbhs_drvexit
  - drivers/mfd/omap-usb-tll.c:omap_usbtll_drvexit
  - drivers/ata/ahci_platform.c:ahci_driver_exit
  - drivers/ata/sata_highbank.c:ahci_highbank_driver_exit
  - drivers/ata/ahci_imx.c:imx_ahci_driver_exit
  - drivers/mtd/nand/raw/omap2.c:omap_nand_driver_exit
  - drivers/mtd/nand/raw/omap_elm.c:elm_driver_exit
  - drivers/spi/spi-fsl-spi.c:fsl_spi_exit
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_driver_exit
  - drivers/net/ethernet/freescale/fec_main.c:fec_driver_exit
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_driver_exit
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_exit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_driver_exit
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_exit
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_module_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-orion.c:ehci_orion_cleanup
  - drivers/usb/host/ehci-exynos.c:ehci_exynos_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-exynos.c:ohci_exynos_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/musb/musb_core.c:musb_driver_exit
  - drivers/rtc/rtc-efi.c:efi_rtc_driver_exit
  - drivers/rtc/rtc-mv.c:mv_rtc_driver_exit
  - drivers/rtc/rtc-omap.c:omap_rtc_driver_exit
  - drivers/rtc/rtc-s3c.c:s3c_rtc_driver_exit
  - drivers/rtc/rtc-twl.c:twl4030rtc_driver_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/i2c/busses/i2c-imx.c:i2c_adap_imx_exit
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_exit_driver
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_adap_s3c_exit
  - drivers/power/avs/smartreflex.c:sr_exit
  - drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_exit
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_exit
  - drivers/power/reset/gpio-restart.c:gpio_restart_driver_exit
  - drivers/power/reset/hisi-reboot.c:hisi_reboot_driver_exit
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_driver_exit
  - drivers/thermal/armada_thermal.c:armada_thermal_driver_exit
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_driver_exit
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_exit
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_driver_exit
  - drivers/cpufreq/cpufreq-dt.c:dt_cpufreq_platdrv_exit
  - drivers/cpufreq/omap-cpufreq.c:omap_cpufreq_platdrv_exit
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_driver_exit
  - drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_driver_exit
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_driver_exit
  - drivers/leds/leds-asic3.c:asic3_led_driver_exit
  - drivers/firmware/arm_scmi/driver.c:scmi_driver_exit
  - drivers/clocksource/sh_cmt.c:sh_cmt_exit
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_exit
  - drivers/clocksource/sh_tmu.c:sh_tmu_exit
  - drivers/clocksource/em_sti.c:em_sti_exit
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_driver_exit
  - drivers/staging/emxx_udc/emxx_udc.c:udc_driver_exit
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_driver_exit
  - drivers/devfreq/exynos-bus.c:exynos_bus_platdrv_exit
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_driver_exit
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_driver_exit
  - drivers/memory/mtk-smi.c:mtk_smi_init
  - drivers/perf/arm-cci.c:cci_pmu_driver_exit
  - drivers/perf/arm-ccn.c:arm_ccn_exit
  - sound/soc/soc-core.c:snd_soc_exit
  - sound/soc/soc-utils.c:snd_soc_util_exit
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_driver_exit
  - sound/soc/fsl/imx-audmux.c:imx_audmux_exit
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_driver_exit
```
**Symbols:**

```
c09db690-c09db6b0: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000985aa4)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - arch/powerpc/platforms/powernv/vas.c:vas_init
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_exit
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-single.c:pcs_driver_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/soc/fsl/guts.c:fsl_guts_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/spi/spi-fsl-spi.c:fsl_spi_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-generic.c:generic_rtc_driver_exit
  - drivers/rtc/rtc-opal.c:opal_rtc_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_exit
  - drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_exit
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_exit
  - drivers/power/reset/gpio-restart.c:gpio_restart_driver_exit
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
```
**Symbols:**

```
c000000000985a00-c000000000985a38: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe0005809ba)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
Direct callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_driver_exit
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_driver_exit
  - drivers/pinctrl/pinctrl-single.c:pcs_driver_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/pwm/pwm-sifive.c:pwm_sifive_driver_exit
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_driver_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/tty/serial/sifive.c:sifive_serial_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/spi/spi-fsl-spi.c:fsl_spi_exit
  - drivers/spi/spi-sifive.c:sifive_spi_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/as3722-poweroff.c:as3722_poweroff_driver_exit
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_driver_exit
  - drivers/power/reset/gpio-restart.c:gpio_restart_driver_exit
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_driver_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
```
**Symbols:**

```
ffffffe000580936-ffffffe000580962: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c79c4)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/gpio/gpio-mmio.c:bgpio_driver_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff816c7980-ffffffff816c7994: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a2cc4)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff816a2c80-ffffffff816a2c94: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f5f34)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_plat_driver_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff816f5ef0-ffffffff816f5f04: platform_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void platform_driver_unregister(struct platform_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817107c4)
Location: drivers/base/platform.c:749
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_driver_exit
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_exit
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_exit
  - drivers/gpio/gpio-xilinx.c:xgpio_exit
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_driver_platform_exit
  - drivers/video/fbdev/vesafb.c:vesafb_driver_exit
  - drivers/acpi/fan.c:acpi_fan_driver_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_uart_driver_exit
  - drivers/char/tpm/tpm_tis.c:cleanup_tis
  - drivers/char/tpm/tpm_tis.c:init_tis
  - drivers/mfd/twl4030-audio.c:twl4030_audio_driver_exit
  - drivers/nvdimm/e820.c:e820_pmem_driver_exit
  - drivers/usb/dwc2/platform.c:dwc2_platform_driver_exit
  - drivers/usb/host/ehci-platform.c:ehci_platform_cleanup
  - drivers/usb/host/ohci-platform.c:ohci_platform_cleanup
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/rtc/rtc-cmos.c:cmos_exit
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_exit_driver
  - drivers/power/reset/restart-poweroff.c:restart_poweroff_driver_exit
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_driver_exit
```
**Symbols:**

```
ffffffff81710780-ffffffff81710794: platform_driver_unregister (STB_GLOBAL)
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
