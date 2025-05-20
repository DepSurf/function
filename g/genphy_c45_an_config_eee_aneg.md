# Function: <code>genphy_c45_an_config_eee_aneg</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_c45_an_config_eee_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81c364ab)
Location: drivers/net/phy/phy-c45.c:864
Inline: True
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff8211e3b0-ffffffff8211e3c5: genphy_c45_an_config_eee_aneg.cold (STB_LOCAL)
ffffffff81c36440-ffffffff81c364ce: genphy_c45_an_config_eee_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_c45_an_config_eee_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81ceb42b)
Location: drivers/net/phy/phy-c45.c:873
Inline: True
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff821ff9d9-ffffffff821ff9ee: genphy_c45_an_config_eee_aneg.cold (STB_LOCAL)
ffffffff81ceb3c0-ffffffff81ceb44e: genphy_c45_an_config_eee_aneg (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
