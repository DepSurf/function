# Function: <code>regulator_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d9e10)
Location: drivers/regulator/core.c:2252
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff814d9e10-ffffffff814d9e71: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152c480)
Location: drivers/regulator/core.c:2301
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8152c480-ffffffff8152c4e1: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558ae0)
Location: drivers/regulator/core.c:2302
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81558ae0-ffffffff81558b41: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156d410)
Location: drivers/regulator/core.c:2314
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8156d410-ffffffff8156d46a: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1690)
Location: drivers/regulator/core.c:2314
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff815d1690-ffffffff815d16ea: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81609880)
Location: drivers/regulator/core.c:2371
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81609880-ffffffff816098e4: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81626c20)
Location: drivers/regulator/core.c:2691
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81626c20-ffffffff81626c88: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8165a280)
Location: drivers/regulator/core.c:2646
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8165a280-ffffffff8165a2e9: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167cfc0)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8167cfc0-ffffffff8167d029: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172e3ca)
Location: drivers/regulator/core.c:2685
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8172e310-ffffffff8172e37b: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174afd6)
Location: drivers/regulator/core.c:2810
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8174af20-ffffffff8174af8b: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172e6aa)
Location: drivers/regulator/core.c:2808
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8172e5f0-ffffffff8172e65b: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817ae28a)
Location: drivers/regulator/core.c:2908
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff817ae1d0-ffffffff817ae23b: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e9266)
Location: drivers/regulator/core.c:2955
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff818e9190-ffffffff818e9218: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3f5a6)
Location: drivers/regulator/core.c:2987
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_disable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81a3f4c0-ffffffff81a3f548: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a89176)
Location: drivers/regulator/core.c:3053
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_disable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_disable_vqmmc
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81a89090-ffffffff81a89118: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adb856)
Location: drivers/regulator/core.c:3059
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
Direct callers:
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_disable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:_set_opp
  - drivers/mmc/core/regulator.c:mmc_regulator_disable_vqmmc
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81adb770-ffffffff81adb7f8: regulator_disable (STB_GLOBAL)
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
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010846b70)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_free
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/ata/libahci_platform.c:ahci_platform_disable_regulators
  - drivers/ata/libahci_platform.c:ahci_platform_disable_regulators
  - drivers/ata/libahci_platform.c:ahci_platform_disable_regulators
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/host/mmci.c:mmci_set_ios
```
**Symbols:**

```
ffff800010846b70-ffff800010846bec: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c095031c)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_off
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/ata/libahci_platform.c:ahci_platform_disable_regulators
  - drivers/ata/libahci_platform.c:ahci_platform_disable_regulators
  - drivers/ata/libahci_platform.c:ahci_platform_disable_regulators
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_remove
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:sdhci_cleanup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_supply
```
**Symbols:**

```
c095031c-c095039c: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e2c40)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
c0000000008e2c40-c0000000008e2cd4: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000527060)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/stmpe.c:stmpe_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffe000527060-ffffffe0005270b2: regulator_disable (STB_GLOBAL)
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
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816428a0)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff816428a0-ffffffff81642909: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81622ea0)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
**Symbols:**

```
ffffffff81622ea0-ffffffff81622f09: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81670e00)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81670e00-ffffffff81670e69: regulator_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168b460)
Location: drivers/regulator/core.c:2654
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8168b460-ffffffff8168b4c9: regulator_disable (STB_GLOBAL)
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
