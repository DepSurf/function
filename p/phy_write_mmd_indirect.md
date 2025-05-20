# Function: <code>phy_write_mmd_indirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void phy_write_mmd_indirect(struct phy_device *phydev, int prtad, int devad, int addr, u32 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815ea1f0)
Location: drivers/net/phy/phy.c:1079
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff815ea1f0-ffffffff815ea2aa: phy_write_mmd_indirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void phy_write_mmd_indirect(struct phy_device *phydev, int prtad, int devad, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81648920)
Location: drivers/net/phy/phy.c:1174
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81648920-ffffffff816489ea: phy_write_mmd_indirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_write_mmd_indirect(struct phy_device *phydev, int prtad, int devad, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679a00)
Location: drivers/net/phy/phy.c:1256
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff81679a00-ffffffff81679aca: phy_write_mmd_indirect (STB_GLOBAL)
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
<li>
<b>Param reordered. </b>
<code>phydev, prtad, devad, addr, data</code> ➡️ <code>phydev, prtad, devad, data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
