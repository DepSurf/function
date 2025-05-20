# Function: <code>regulator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dc8e0)
Location: drivers/regulator/core.c:1645
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff814dc8e0-ffffffff814dc8f7: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152e4a0)
Location: drivers/regulator/core.c:1697
Inline: False
Direct callers:
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8152e4a0-ffffffff8152e4b7: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8155a226)
Location: drivers/regulator/core.c:1698
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8155a1b0-ffffffff8155a1c7: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8157012c)
Location: drivers/regulator/core.c:1708
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815700b0-ffffffff815700c2: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d43bc)
Location: drivers/regulator/core.c:1708
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815d4340-ffffffff815d4352: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8160c260)
Location: drivers/regulator/core.c:1759
Inline: True
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8160c260-ffffffff8160c272: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81628900)
Location: drivers/regulator/core.c:1984
Inline: True
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81628900-ffffffff81628912: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8165accf)
Location: drivers/regulator/core.c:1966
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8165ac50-ffffffff8165ac62: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167f19f)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8167f120-ffffffff8167f132: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172ecbf)
Location: drivers/regulator/core.c:1993
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff8172ec40-ffffffff8172ec52: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174b95c)
Location: drivers/regulator/core.c:2050
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff8174b8e0-ffffffff8174b8f2: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172f06c)
Location: drivers/regulator/core.c:2061
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff8172eff0-ffffffff8172f002: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817aed2c)
Location: drivers/regulator/core.c:2161
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff817aecb0-ffffffff817aecc2: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818ea6da)
Location: drivers/regulator/core.c:2208
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff818ea660-ffffffff818ea67c: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a40640)
Location: drivers/regulator/core.c:2235
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81a40640-ffffffff81a40680: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8a740)
Location: drivers/regulator/core.c:2301
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81a8a740-ffffffff81a8a780: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adce90)
Location: drivers/regulator/core.c:2303
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81adce90-ffffffff81adced0: regulator_get (STB_GLOBAL)
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
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010849168)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffff8000108490c0-ffff8000108490f8: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0952924)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
c09528a4-c09528c4: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e62ec)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
c0000000008e6230-c0000000008e6248: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005291e6)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffe000529154-ffffffe000529188: regulator_get (STB_GLOBAL)
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
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81644bff)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffffffff81644b80-ffffffff81644b92: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8162507f)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffffffff81625000-ffffffff81625012: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81672fdf)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81672f60-ffffffff81672f72: regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct regulator *regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168d63f)
Location: drivers/regulator/core.c:1974
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_get
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8168d5c0-ffffffff8168d5d2: regulator_get (STB_GLOBAL)
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
