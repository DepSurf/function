# Function: <code>dev_err_probe</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_err_probe(const struct device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4401
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
**Symbols:**

```
ffffffff81c0e0ca-ffffffff81c0e0e1: dev_err_probe.cold (STB_LOCAL)
ffffffff817c8420-ffffffff817c84dc: dev_err_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_err_probe(const struct device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4628
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff81c00468-ffffffff81c0047f: dev_err_probe.cold (STB_LOCAL)
ffffffff817ab9b0-ffffffff817aba6c: dev_err_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_err_probe(const struct device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4693
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff81d029d9-ffffffff81d029f0: dev_err_probe.cold (STB_LOCAL)
ffffffff81834b40-ffffffff81834bf9: dev_err_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_err_probe(const struct device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4732
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ecb09c-ffffffff81ecb0b3: dev_err_probe.cold (STB_LOCAL)
ffffffff819766c0-ffffffff81976790: dev_err_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_err_probe(const struct device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2ff0)
Location: drivers/base/core.c:4951
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ae2ff0-ffffffff81ae30d0: dev_err_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_err_probe(const struct device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30f10)
Location: drivers/base/core.c:4956
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_of_phy_optional_get
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b30f10-ffffffff81b30ff0: dev_err_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_err_probe(const struct device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88510)
Location: drivers/base/core.c:4970
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_of_phy_optional_get
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/core.c:device_links_check_suppliers
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b88510-ffffffff81b885f0: dev_err_probe (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
