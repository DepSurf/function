# Function: <code>genphy_c45_ethtool_get_eee</code>

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
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int genphy_c45_ethtool_get_eee(struct phy_device *phydev, struct ethtool_eee *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-c45.c (0)
Location: drivers/net/phy/phy-c45.c:1397
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
```
**Symbols:**

```
ffffffff8211e395-ffffffff8211e3b0: genphy_c45_ethtool_get_eee.cold (STB_LOCAL)
ffffffff81c36330-ffffffff81c3642a: genphy_c45_ethtool_get_eee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int genphy_c45_ethtool_get_eee(struct phy_device *phydev, struct ethtool_eee *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-c45.c (0)
Location: drivers/net/phy/phy-c45.c:1451
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
```
**Symbols:**

```
ffffffff821ff9be-ffffffff821ff9d9: genphy_c45_ethtool_get_eee.cold (STB_LOCAL)
ffffffff81ceb2b0-ffffffff81ceb3aa: genphy_c45_ethtool_get_eee (STB_GLOBAL)
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
