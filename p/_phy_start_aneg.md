# Function: <code>_phy_start_aneg</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _phy_start_aneg(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81900e10)
Location: drivers/net/phy/phy.c:711
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81900e10-ffffffff81900eb1: _phy_start_aneg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _phy_start_aneg(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a52930)
Location: drivers/net/phy/phy.c:716
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81a52930-ffffffff81a529f0: _phy_start_aneg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _phy_start_aneg(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdc4c0)
Location: drivers/net/phy/phy.c:745
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81bdc4c0-ffffffff81bdc580: _phy_start_aneg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _phy_start_aneg(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c33150)
Location: drivers/net/phy/phy.c:950
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81c33150-ffffffff81c33210: _phy_start_aneg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _phy_start_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7e40)
Location: drivers/net/phy/phy.c:1004
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81ce7e40-ffffffff81ce7f00: _phy_start_aneg (STB_GLOBAL)
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
