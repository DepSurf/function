# Function: <code>gpiod_set_value_cansleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426490)
Location: drivers/gpio/gpiolib.c:1727
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
```
**Symbols:**

```
ffffffff81426490-ffffffff814264c2: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146fc70)
Location: drivers/gpio/gpiolib.c:2734
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
```
**Symbols:**

```
ffffffff8146fc70-ffffffff8146fd03: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491fe0)
Location: drivers/gpio/gpiolib.c:2943
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
**Symbols:**

```
ffffffff81491fe0-ffffffff81492073: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149bc00)
Location: drivers/gpio/gpiolib.c:2950
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
**Symbols:**

```
ffffffff8149bc00-ffffffff8149bc91: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9eb0)
Location: drivers/gpio/gpiolib.c:3268
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
**Symbols:**

```
ffffffff814d9eb0-ffffffff814d9f25: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508c40)
Location: drivers/gpio/gpiolib.c:3459
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff81508c40-ffffffff81508c72: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d550)
Location: drivers/gpio/gpiolib.c:3707
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff8151d550-ffffffff8151d582: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154b5a0)
Location: drivers/gpio/gpiolib.c:3796
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff8154b5a0-ffffffff8154b5d4: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c820)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff8156c820-ffffffff8156c854: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4563
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff816147ea-ffffffff8161483f: gpiod_set_value_cansleep.cold (STB_LOCAL)
ffffffff81610750-ffffffff816107a1: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3387
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
```
**Symbols:**

```
ffffffff81bf5f8c-ffffffff81bf5fe1: gpiod_set_value_cansleep.cold (STB_LOCAL)
ffffffff81636aa0-ffffffff81636af1: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3364
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
```
**Symbols:**

```
ffffffff81be7e91-ffffffff81be7ee6: gpiod_set_value_cansleep.cold (STB_LOCAL)
ffffffff8161a410-ffffffff8161a461: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3423
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
```
**Symbols:**

```
ffffffff81ce19bc-ffffffff81ce1a11: gpiod_set_value_cansleep.cold (STB_LOCAL)
ffffffff816897b0-ffffffff81689801: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3544
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
```
**Symbols:**

```
ffffffff81ea828c-ffffffff81ea82e0: gpiod_set_value_cansleep.cold (STB_LOCAL)
ffffffff817a6720-ffffffff817a6787: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818be6b0)
Location: drivers/gpio/gpiolib.c:3614
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
```
**Symbols:**

```
ffffffff818be6b0-ffffffff818be74e: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901790)
Location: drivers/gpio/gpiolib.c:3655
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
```
**Symbols:**

```
ffffffff81901790-ffffffff8190183f: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949300)
Location: drivers/gpio/gpiolib.c:3848
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
  - drivers/nvmem/core.c:nvmem_access_with_keepouts
```
**Symbols:**

```
ffffffff81949300-ffffffff81949392: gpiod_set_value_cansleep (STB_GLOBAL)
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
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c2468)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
```
**Symbols:**

```
ffff8000106c2468-ffff8000106c24b8: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860394)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
```
**Symbols:**

```
c0860394-c08603d4: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083db80)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
```
**Symbols:**

```
c00000000083db80-c00000000083dbf8: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a70da)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
```
**Symbols:**

```
ffffffe0004a70da-ffffffe0004a7122: gpiod_set_value_cansleep (STB_GLOBAL)
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
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561fe0)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
**Symbols:**

```
ffffffff81561fe0-ffffffff81562014: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552e30)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
**Symbols:**

```
ffffffff81552e30-ffffffff81552e64: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560b50)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff81560b50-ffffffff81560b84: gpiod_set_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157a9f0)
Location: drivers/gpio/gpiolib.c:4150
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare
  - drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/regulator/core.c:regulator_ena_gpio_ctrl
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/i2c-core-base.c:set_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff8157a9f0-ffffffff8157aa24: gpiod_set_value_cansleep (STB_GLOBAL)
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
