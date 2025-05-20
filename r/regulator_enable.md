# Function: <code>regulator_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814da910)
Location: drivers/regulator/core.c:2135
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff814da910-ffffffff814daa5c: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152c4f0)
Location: drivers/regulator/core.c:2187
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8152c4f0-ffffffff8152c674: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558b50)
Location: drivers/regulator/core.c:2188
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81558b50-ffffffff81558cd4: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156d470)
Location: drivers/regulator/core.c:2200
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8156d470-ffffffff8156d628: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d16f0)
Location: drivers/regulator/core.c:2200
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff815d16f0-ffffffff815d18a8: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2257
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8160ca81-ffffffff8160caf3: regulator_enable.cold.58 (STB_LOCAL)
ffffffff816098f0-ffffffff81609a30: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816271f0)
Location: drivers/regulator/core.c:2581
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff816271f0-ffffffff81627258: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8165a8a0)
Location: drivers/regulator/core.c:2536
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8165a8a0-ffffffff8165a909: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167d4a0)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8167d4a0-ffffffff8167d509: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172ef2c)
Location: drivers/regulator/core.c:2575
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8172e8c0-ffffffff8172e92b: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174bb9c)
Location: drivers/regulator/core.c:2700
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8174b490-ffffffff8174b4fb: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172f2bc)
Location: drivers/regulator/core.c:2701
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8172eba0-ffffffff8172ec0b: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817aef7c)
Location: drivers/regulator/core.c:2801
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff817ae7e0-ffffffff817ae84b: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e99cc)
Location: drivers/regulator/core.c:2848
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff818e9840-ffffffff818e98c8: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3fd71)
Location: drivers/regulator/core.c:2880
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81a3fbe0-ffffffff81a3fc68: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a89941)
Location: drivers/regulator/core.c:2946
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/mmc/core/regulator.c:mmc_regulator_enable_vqmmc
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81a897b0-ffffffff81a89838: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adc091)
Location: drivers/regulator/core.c:2949
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
Direct callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/mmc/core/regulator.c:mmc_regulator_enable_vqmmc
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81adbf00-ffffffff81adbf88: regulator_enable (STB_GLOBAL)
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
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108470d0)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/host/mmci.c:mmci_set_ios
```
**Symbols:**

```
ffff8000108470d0-ffff80001084714c: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0950880)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_on
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_supply
```
**Symbols:**

```
c0950880-c0950900: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e3340)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
c0000000008e3340-c0000000008e33d4: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005274d4)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffe0005274d4-ffffffe000527526: regulator_enable (STB_GLOBAL)
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
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81642d80)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81642d80-ffffffff81642de9: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81623380)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
**Symbols:**

```
ffffffff81623380-ffffffff816233e9: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816712e0)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff816712e0-ffffffff81671349: regulator_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168b940)
Location: drivers/regulator/core.c:2544
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8168b940-ffffffff8168b9a9: regulator_enable (STB_GLOBAL)
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
