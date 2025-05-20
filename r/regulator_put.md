# Function: <code>regulator_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dbbe0)
Location: drivers/regulator/core.c:1743
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/charger-manager.c:charger_manager_remove
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff814dbbe0-ffffffff814dbc1e: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152cdd0)
Location: drivers/regulator/core.c:1795
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/charger-manager.c:charger_manager_remove
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8152cdd0-ffffffff8152ce0e: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559430)
Location: drivers/regulator/core.c:1796
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81559430-ffffffff8155946e: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156cea0)
Location: drivers/regulator/core.c:1806
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8156cea0-ffffffff8156cede: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1110)
Location: drivers/regulator/core.c:1806
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff815d1110-ffffffff815d114e: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816093d0)
Location: drivers/regulator/core.c:1857
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff816093d0-ffffffff8160940e: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816257b0)
Location: drivers/regulator/core.c:2097
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff816257b0-ffffffff816257ee: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81657c80)
Location: drivers/regulator/core.c:2071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81657c80-ffffffff81657cc0: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167bba0)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff8167bba0-ffffffff8167bbe0: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172e403)
Location: drivers/regulator/core.c:2099
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff8172a020-ffffffff8172a062: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81746b1b)
Location: drivers/regulator/core.c:2163
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_free
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81746b90-ffffffff81746bfc: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172e6e3)
Location: drivers/regulator/core.c:2174
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff8172a560-ffffffff8172a5a2: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817ae2c3)
Location: drivers/regulator/core.c:2274
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff817aa840-ffffffff817aa882: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e92b7)
Location: drivers/regulator/core.c:2321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff818e5280-ffffffff818e52b9: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3f5f7)
Location: drivers/regulator/core.c:2348
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:_regulator_bulk_get
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
```
**Symbols:**

```
ffffffff81a39ea0-ffffffff81a39ed9: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a891c7)
Location: drivers/regulator/core.c:2414
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:_regulator_bulk_get
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
```
**Symbols:**

```
ffffffff81a83a80-ffffffff81a83ab9: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adb8a7)
Location: drivers/regulator/core.c:2416
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:_regulator_bulk_get
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
```
**Symbols:**

```
ffffffff81ad6230-ffffffff81ad6269: regulator_put (STB_GLOBAL)
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
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010844868)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_free
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffff800010844868-ffff8000108448b8: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094eb10)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
**Symbols:**

```
c094eb10-c094eb58: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e0c00)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
c0000000008e0c00-c0000000008e0c7c: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000525e8e)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffe000525e8e-ffffffe000525ee0: regulator_put (STB_GLOBAL)
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
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816415e0)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff816415e0-ffffffff81641620: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81621a80)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff81621a80-ffffffff81621ac0: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166f9e0)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff8166f9e0-ffffffff8166fa20: regulator_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void regulator_put(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168a040)
Location: drivers/regulator/core.c:2079
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_release
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_release
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
```
**Symbols:**

```
ffffffff8168a040-ffffffff8168a080: regulator_put (STB_GLOBAL)
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
