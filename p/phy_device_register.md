# Function: <code>phy_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815eb3d0)
Location: drivers/net/phy/phy_device.c:380
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/phy/fixed_phy.c:fixed_phy_register
```
**Symbols:**

```
ffffffff815eb3d0-ffffffff815eb46a: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81649f80)
Location: drivers/net/phy/phy_device.c:584
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff81649f80-ffffffff81649ffd: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167b2f0)
Location: drivers/net/phy/phy_device.c:632
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff8167b2f0-ffffffff8167b36d: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816901b0)
Location: drivers/net/phy/phy_device.c:627
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff816901b0-ffffffff8169022d: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816f9e80)
Location: drivers/net/phy/phy_device.c:627
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff816f9e80-ffffffff816f9efd: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:642
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff81738fdf-ffffffff81739023: phy_device_register.cold.25 (STB_LOCAL)
ffffffff81737540-ffffffff81737596: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:820
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff8175c707-ffffffff8175c74b: phy_device_register.cold.29 (STB_LOCAL)
ffffffff8175a830-ffffffff8175a886: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:835
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff81799a11-ffffffff81799a4b: phy_device_register.cold (STB_LOCAL)
ffffffff81797d10-ffffffff81797d6e: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff817bd530-ffffffff817bd56a: phy_device_register.cold (STB_LOCAL)
ffffffff817bb830-ffffffff817bb88e: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:842
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
**Symbols:**

```
ffffffff81885df9-ffffffff81885e33: phy_device_register.cold (STB_LOCAL)
ffffffff81883060-ffffffff818830be: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:864
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff81c1929c-ffffffff81c192d6: phy_device_register.cold (STB_LOCAL)
ffffffff81891770-ffffffff818917ce: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:881
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff81c0b0ca-ffffffff81c0b104: phy_device_register.cold (STB_LOCAL)
ffffffff81873fa0-ffffffff81873ffe: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:915
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81d104ba-ffffffff81d104f4: phy_device_register.cold (STB_LOCAL)
ffffffff81904940-ffffffff8190499e: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:946
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81edb23a-ffffffff81edb274: phy_device_register.cold (STB_LOCAL)
ffffffff81a57700-ffffffff81a57766: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be14f0)
Location: drivers/net/phy/phy_device.c:950
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81be14f0-ffffffff81be1583: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c38d80)
Location: drivers/net/phy/phy_device.c:981
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81c38d80-ffffffff81c38e13: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cee110)
Location: drivers/net/phy/phy_device.c:984
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81cee110-ffffffff81cee1a3: phy_device_register (STB_GLOBAL)
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
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4590)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
ffff8000109d4590-ffff8000109d4630: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc224)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
c0abc224-c0abc2b8: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a94d50)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
c000000000a94d50-c000000000a94e30: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000620928)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
  - drivers/of/of_mdio.c:of_mdiobus_register_phy
```
**Symbols:**

```
ffffffe000620928-ffffffe0006209c2: phy_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff81782000-ffffffff8178203a: phy_device_register.cold (STB_LOCAL)
ffffffff81780300-ffffffff8178035e: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff81761d90-ffffffff81761dca: phy_device_register.cold (STB_LOCAL)
ffffffff817600a0-ffffffff817600fe: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff817b23b0-ffffffff817b23ea: phy_device_register.cold (STB_LOCAL)
ffffffff817b06b0-ffffffff817b070e: phy_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int phy_device_register(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:843
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_scan
```
**Symbols:**

```
ffffffff817cc340-ffffffff817cc37a: phy_device_register.cold (STB_LOCAL)
ffffffff817ca640-ffffffff817ca69e: phy_device_register (STB_GLOBAL)
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
