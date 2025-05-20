# Function: <code>devm_kcalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814235c7)
Location: include/linux/device.h:664
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/device.h:664
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/device.h:664
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c6fe)
Location: include/linux/device.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/device.h:668
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/device.h:668
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:668
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/device.h:668
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148ce2d)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148ea0f)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81713fd9)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/device.h:673
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493aca)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81496727)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8149843f)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154bafd)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff8172c480)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/device.h:673
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8179ef6d)
Location: include/linux/device.h:673
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cfd5a)
Location: include/linux/device.h:670
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d2a29)
Location: include/linux/device.h:670
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d467b)
Location: include/linux/device.h:670
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d6007)
Location: include/linux/device.h:670
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:670
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af08d)
Location: include/linux/device.h:670
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/device.h:670
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/device.h:670
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff8179dc4d)
Location: include/linux/device.h:670
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/devfreq/devfreq.c (ffffffff81813bfc)
Location: include/linux/device.h:670
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818160cd)
Location: include/linux/device.h:670
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500f44)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81503a64)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815056a9)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:688
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff815c6c61)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:688
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e729b)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b1df)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:688
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b56bb)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816c216b)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8173a56b)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e4172)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff817e51dd)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8185d8c9)
Location: include/linux/device.h:688
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8185ffaa)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515a14)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815184a3)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8151a1f9)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:692
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff815e0221)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:692
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816016cb)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81679199)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:692
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d691b)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816e35ab)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8175dcab)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff817f7093)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:692
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180fa20)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81810c6d)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8187d20f)
Location: include/linux/device.h:692
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8187f931)
Location: include/linux/device.h:692
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543b94)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81546601)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154866f)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8154ad32)
Location: include/linux/device.h:695
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:695
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff81611cc5)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:695
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81634012)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af7b6)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:695
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81712068)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff8171d137)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff8178fe43)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8179b2ba)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff81837dbb)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:695
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851716)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff818530a3)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/soundwire/mipi_disco.c (ffffffff818c305b)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
```
```
In drivers/devfreq/devfreq.c (ffffffff818c7493)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff818c9f30)
Location: include/linux/device.h:695
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564aa4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815673c4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8156932d)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8156bfc2)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81574b22)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff81633175)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655d42)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d24a6)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81736368)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff81741407)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff817b385b)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff817bed6a)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff8186972b)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff818831f6)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff818f994f)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff818fc380)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606ec4)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81608662)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_soc_data
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160ad02)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/device.h:224
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:224
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff816dfc73)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81705cc7)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81785a49)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:224
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3b60)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff817ff095)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff81878052)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81887b4a)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff8193d38b)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:224
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81951be7)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff819d04d7)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:set_freq_table
```
```
In drivers/extcon/extcon.c (ffffffff819d2f68)
Location: include/linux/device.h:224
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b794)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162cdf2)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_soc_data
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162f40c)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81631510)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167ce0e)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/fan.c (ffffffff816fdc03)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81722f67)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179cc49)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef429)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:229
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff818077c0)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff818104c5)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff81886962)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81895dfd)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff8194338e)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:229
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81957166)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff819cff42)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:set_freq_table
```
```
In drivers/extcon/extcon.c (ffffffff819d2b45)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f464)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81610b25)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816130ac)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81614de3)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fc8d)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/fan.c (ffffffff816df873)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817041c7)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8170977e)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177f71f)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3cc9)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:229
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec280)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff817f4b05)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff8186930f)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8187866d)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff81926bae)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:229
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193b098)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff819b509e)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff819b7df5)
Location: include/linux/device.h:229
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e399)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8167fc55)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816821ec)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8168407b)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d28ad)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/fan.c (ffffffff817576f3)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177f7c7)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81785134)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81805aaf)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/base/regmap/regmap.c (ffffffff8185f360)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:220
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81878e60)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff8187db65)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff818f8c1f)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8190957d)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff819c9aee)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:220
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff819df888)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81a63c0e)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff81a66cf5)
Location: include/linux/device.h:220
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799fb6)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179baa9)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179e29b)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a04fd)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbd36)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/fan_core.c (ffffffff8188ac62)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b5f17)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbd0e)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81945566)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/base/regmap/regmap.c (ffffffff819a777b)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:221
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c13a4)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff819c6050)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff81a4a01b)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81a5cbd8)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff81b2af3c)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:221
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b440aa)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81bca9e8)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd49a0)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b0571)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2389)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b4fab)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b765d)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81929020)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/fan_core.c (ffffffff819d17cc)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a033c7)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07aab)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a8f8)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff81a450d4)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa8596)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/base/regmap/regmap.c (ffffffff81b197c9)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:221
Inline: True
```
```
In drivers/mfd/twl-core.c (ffffffff81b3c9d5)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff81bd07db)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81be7788)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff81cbecac)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:221
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cdad20)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81d740d8)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81d80a9d)
Location: include/linux/device.h:221
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f3555)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f53e5)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f804b)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fa723)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196d260)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/fan_core.c (ffffffff81a18dbf)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c225)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a5093c)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a5377f)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff81a8f284)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af3dc6)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/base/regmap/regmap.c (ffffffff81b69aab)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:326
Inline: True
```
```
In drivers/mfd/twl-core.c (ffffffff81b8fe3c)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff81c28531)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81c3fb54)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff81d265f4)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:326
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d42fdf)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81de20f8)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81deee49)
Location: include/linux/device.h:326
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193ad85)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193ca55)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193f048)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941aa3)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b624c)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/fan_core.c (ffffffff81a6408f)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a97e75)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c60c)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f52f)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff81ae1af4)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b47386)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbd76b)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:325
Inline: True
```
```
In drivers/mfd/twl-core.c (ffffffff81be3d5f)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff81cdac81)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81cf5154)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff81ddc364)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:325
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df99a5)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81e980ca)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea53fc)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81eafe9d)
Location: include/linux/device.h:325
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_populate_sysfs_cells
  - drivers/nvmem/core.c:nvmem_populate_sysfs_cells
```
</details>
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
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678c58)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b324)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f320)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff800010680fec)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
```
```
In drivers/bus/fsl-mc/fsl-mc-allocator.c (ffff800010684024)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_allocate_irqs
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_populate_irq_pool
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692b30)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699624)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069cc5c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff8000106a0044)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a2020)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3b44)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a4b94)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a664c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
```
```
In drivers/pinctrl/berlin/berlin.c (ffff8000106a7e88)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a8728)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106ab45c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff800011477484)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ad324)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106af748)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b19fc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b39ec)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b652c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_build_state
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_build_state
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7db8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b9758)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/gpio/gpiolib.c (ffff8000106bf33c)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ce86c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3270)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_probe
```
```
In drivers/pci/controller/pcie-cadence.c (ffff80001071d4f0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e2bc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff800010726110)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff800010729688)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff8000107301f0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761530)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffff8000107a1784)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (ffff8000107c7900)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cd1bc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_debug_init
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_debug_init
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff800011487780)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
```
```
In drivers/clk/socfpga/clk-s10.c (ffff8000107f040c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/socfpga/clk-s10.c:s10_clkmgr_init
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3444)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
```
```
In drivers/clk/sunxi/clk-sun6i-apb0-gates.c (ffff8000107f4570)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
```
```
In drivers/dma/amba-pl08x.c (ffff800010802d48)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff800010809178)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080e120)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
```
```
In drivers/soc/bcm/raspberrypi-power.c (ffff80001080efa4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff800010818cd4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (ffff80001081a860)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b480)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
```
```
In drivers/soc/qcom/rpmhpd.c (ffff80001081db98)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmhpd.c:rpmhpd_probe
```
```
In drivers/soc/rockchip/pm_domains.c (ffff80001081edfc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
```
```
In drivers/soc/xilinx/zynqmp_pm_domains.c (ffff800010820630)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcf44)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d227c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7dbc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/misc/sram.c (ffff80001092b658)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092dd20)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffff80001093cc30)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/ata/libahci_platform.c (ffff8000109bd4e8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/spi/spi.c (ffff8000109c78a8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd790)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffff8000109d84f8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffff800010aac008)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acb43c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/charger-manager.c (ffff800010ad0548)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/firmware/ti_sci.c (ffff800010b51160)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_of_resource
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b563f0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/firmware/arm_scmi/base.c (ffff800010b57370)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57954)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b586b0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
```
```
In drivers/firmware/arm_scmi/power.c (ffff800010b58ff4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
```
```
In drivers/firmware/arm_scmi/reset.c (ffff800010b592c0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/firmware/arm_scmi/sensors.c (ffff800010b59978)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
```
In drivers/firmware/imx/scu-pd.c (ffff800010b62c1c)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b35c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7c8a4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
```
```
In drivers/devfreq/devfreq.c (ffff800010b85fe8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffff800010b88fe4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/perf/arm-cci.c (ffff800010b907c0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In drivers/perf/arm-ccn.c (ffff800010b9382c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
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
In arch/arm/plat-omap/dma.c (c034ee68)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - arch/arm/plat-omap/dma.c:omap_system_dma_probe
```
```
In drivers/bus/ti-sysc.c (c0827be8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/bus/ti-sysc.c:sysc_get_clocks
```
```
In drivers/phy/ti/phy-gmii-sel.c (c082cfdc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c083549c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083ac88)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-rza1.c (c083bc60)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083cc34)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-single.c (c0840360)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c0842e9c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0844bec)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0846434)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/berlin/berlin.c (c0847f00)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c0848db0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084b2c0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-dove.c (c084bca4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084f590)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c08514a0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_create_functions
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852674)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
```
```
In drivers/pinctrl/sh-pfc/core.c (c08530cc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (c0854e60)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
```
```
In drivers/pinctrl/sh-pfc/gpio.c (c08551fc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_setup
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_setup
```
```
In drivers/pinctrl/ti/pinctrl-ti-iodelay.c (c0856a5c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858d00)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c085a3a8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/gpio/gpiolib.c (c085fae0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-ftgpio010.c (c08689fc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-htc-egpio.c (c15508f0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/gpio/gpio-pl061.c (c086f34c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_probe
```
```
In drivers/gpio/gpio-tegra.c (c0871858)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
```
```
In drivers/gpio/gpio-vf610.c (c0873a40)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
```
```
In drivers/pci/controller/pcie-cadence.c (c08a654c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a74b4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-mvebu.c (c08a98e4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ab084)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b44a4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b93d4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c155218c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/video/fbdev/omap2/omapfb/vrfb.c (c1553428)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_probe
```
```
In drivers/video/fbdev/simplefb.c (c08e3d48)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/clk/clk-gpio.c (c08f287c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (c157fbb4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
```
```
In drivers/clk/tegra/clk-bpmp.c (c09153a8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
```
```
In drivers/clk/ti/adpll.c (c091b890)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_probe
```
```
In drivers/dma/amba-pl08x.c (c0921be4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/ti/edma.c (c092ee24)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
  - drivers/dma/ti/edma.c:edma_xbar_event_map
```
```
In drivers/dma/ti/omap-dma.c (c0931588)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
```
In drivers/dma/ti/dma-crossbar.c (c09332e8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c0935f84)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (c0937574)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/soc/qcom/spm.c (c1590570)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/qcom/spm.c:qcom_cpuidle_init
```
```
In drivers/soc/rockchip/pm_domains.c (c09393e4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
```
```
In drivers/regulator/ti-abb-regulator.c (c0955ae0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
```
```
In drivers/regulator/tps65217-regulator.c (c0956d80)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (c09b6344)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/iommu/rockchip-iommu.c (c09c5854)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/misc/sram.c (c0a09be8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/htc-i2cpld.c (c0a0f72c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (c0a256ac)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/ata/libahci_platform.c (c0a88308)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/spi/spi.c (c0ab0830)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7c44)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/phy/phy_led_triggers.c (c0abfc38)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad5558)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
```
```
In drivers/rtc/sysfs.c (c0b8a5c8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (c0bac2dc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/charger-manager.c (c0bb0d80)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/mmc/host/cqhci.c (c0c2f8ec)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_init
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37bb0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/firmware/arm_scmi/base.c (c0c3865c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38de0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39c30)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
```
```
In drivers/firmware/arm_scmi/power.c (c0c3a2a8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
```
```
In drivers/firmware/arm_scmi/reset.c (c0c3a580)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/firmware/arm_scmi/sensors.c (c0c3ab9c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
```
In drivers/firmware/imx/scu-pd.c (c0c41324)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/firmware/tegra/bpmp.c (c0c423ac)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c607fc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/tegra-hsp.c (c0c614dc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
```
```
In drivers/devfreq/devfreq.c (c0c69070)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6c43c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
```
```
In drivers/extcon/extcon.c (c0c6dc08)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/memory/of_memory.c (c0c6ec68)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/memory/of_memory.c:of_get_ddr_timings
```
```
In drivers/memory/tegra/mc.c (c0c74140)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74b94)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
```
```
In drivers/memory/tegra/tegra124-emc.c (c0c759e8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
```
```
In drivers/perf/arm-cci.c (c0c7aa44)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In drivers/perf/arm-ccn.c (c0c7c978)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In sound/soc/soc-core.c (c0ca1554)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - sound/soc/soc-core.c:snd_soc_of_parse_audio_routing
  - sound/soc/soc-core.c:snd_soc_of_parse_audio_simple_widgets
```
```
In sound/soc/soc-dapm.c (c0cabe34)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_dai
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
In drivers/pinctrl/pinctrl-amd.c (c00000000082f39c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c0000000008352ac)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0000000008389e0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (c00000000083cd1c)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-ftgpio010.c (c0000000008499a8)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/pci/controller/pcie-cadence.c (c00000000088e2d0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f6bc)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/video/fbdev/simplefb.c (c0000000008c50f0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (c00000000095ed9c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (c0000000009ca960)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cd5d0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (c0000000009e4904)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (c000000000a882e0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy_led_triggers.c (c000000000a9a784)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (c000000000b8e234)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (c000000000bad600)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/charger-manager.c (c000000000bb43ac)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/devfreq/devfreq.c (c000000000c64c7c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (c000000000c68e9c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0df4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3c04)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a68e2)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004aea74)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e4298)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e54b4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea186)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffe000508230)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/clk/clk-gpio.c (ffffffe0005146ac)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f1b0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (ffffffe0005a2f86)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4b4e)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffe0005b0f0e)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffe00061802c)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffe000624188)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffe0006b68b4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c8c40)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006ccd92)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/devfreq/devfreq.c (ffffffe00072f4c4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffe000731d70)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155d094)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155e894)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81561782)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bda2)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697ef6)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8177833b)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8178383a)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff8181c3db)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff8189ac7f)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff8189d6b0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154d9d4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f93d)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff815525d2)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155b132)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/acpi/nfit/core.c (ffffffff815f65be)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:__nfit_mem_init
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816102d2)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816758e6)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817580eb)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/rtc/sysfs.c (ffffffff817e3acb)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff8185814f)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558dd4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155b6f4)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155d65d)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff815602f2)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568e52)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff81627455)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649b82)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c6166)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81729828)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff817348c7)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff817a86db)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff817b3bea)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff8185d8bb)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff818786a6)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff818ea36f)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff818ecda0)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572c64)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81575714)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8157757d)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8157a162)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582d72)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff81641305)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81664112)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e0666)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/misc/sram.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81744c68)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/twl-core.c (ffffffff8174fd07)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/spi/spi.c (ffffffff817c256b)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff817cdbba)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/rtc/sysfs.c (ffffffff81878b2b)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_add_groups
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/device.h:931
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81894046)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff8190b3ef)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff8190de20)
Location: include/linux/device.h:931
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
</ul>

## Differences
