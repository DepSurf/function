# Function: <code>phy_read_mmd_indirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int phy_read_mmd_indirect(struct phy_device *phydev, int prtad, int devad, int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815ea400)
Location: drivers/net/phy/phy.c:1041
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
```
**Symbols:**

```
ffffffff815ea400-ffffffff815ea4b4: phy_read_mmd_indirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int phy_read_mmd_indirect(struct phy_device *phydev, int prtad, int devad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81648d80)
Location: drivers/net/phy/phy.c:1137
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
```
**Symbols:**

```
ffffffff81648d80-ffffffff81648e42: phy_read_mmd_indirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int phy_read_mmd_indirect(struct phy_device *phydev, int prtad, int devad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679f20)
Location: drivers/net/phy/phy.c:1219
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff81679f20-ffffffff81679fe2: phy_read_mmd_indirect (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
