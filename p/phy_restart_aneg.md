# Function: <code>phy_restart_aneg</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168dc90)
Location: drivers/net/phy/phy.c:161
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
```
**Symbols:**

```
ffffffff8168dc90-ffffffff8168dcb9: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f77c0)
Location: drivers/net/phy/phy.c:124
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
```
**Symbols:**

```
ffffffff816f77c0-ffffffff816f77e9: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81734a50)
Location: drivers/net/phy/phy.c:124
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
```
**Symbols:**

```
ffffffff81734a50-ffffffff81734a79: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81757b70)
Location: drivers/net/phy/phy.c:132
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81757b70-ffffffff81757b99: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81794310)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81794310-ffffffff81794339: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b7e40)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff817b7e40-ffffffff817b7e69: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8187f1eb)
Location: drivers/net/phy/phy.c:156
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff8187edf0-ffffffff8187ee19: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188daab)
Location: drivers/net/phy/phy.c:139
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff8188d500-ffffffff8188d529: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff818703eb)
Location: drivers/net/phy/phy.c:139
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff8186fe40-ffffffff8186fe69: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff819009cb)
Location: drivers/net/phy/phy.c:139
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81900420-ffffffff81900449: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a5273b)
Location: drivers/net/phy/phy.c:140
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81a520a0-ffffffff81a520d5: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdbe8b)
Location: drivers/net/phy/phy.c:168
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81bdb500-ffffffff81bdb535: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32d71)
Location: drivers/net/phy/phy.c:181
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
```
**Symbols:**

```
ffffffff81c31fa0-ffffffff81c31fd5: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7a61)
Location: drivers/net/phy/phy.c:181
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
```
**Symbols:**

```
ffffffff81ce6c90-ffffffff81ce6cc5: phy_restart_aneg (STB_GLOBAL)
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
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d05a8)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffff8000109d05a8-ffff8000109d05f8: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab87dc)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
c0ab87dc-c0ab8820: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a8f910)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
c000000000a8f910-c000000000a8f988: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061d142)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffe00061d142-ffffffe00061d18e: phy_restart_aneg (STB_GLOBAL)
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
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177c910)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff8177c910-ffffffff8177c939: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175c6c0)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff8175c6c0-ffffffff8175c6e9: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817accc0)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff817accc0-ffffffff817acce9: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c6c50)
Location: drivers/net/phy/phy.c:148
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff817c6c50-ffffffff817c6c79: phy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
