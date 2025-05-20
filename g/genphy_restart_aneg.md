# Function: <code>genphy_restart_aneg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815eb670)
Location: drivers/net/phy/phy_device.c:908
Inline: False
```
**Symbols:**

```
ffffffff815eb670-ffffffff815eb6b0: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164a3a0)
Location: drivers/net/phy/phy_device.c:1148
Inline: False
```
**Symbols:**

```
ffffffff8164a3a0-ffffffff8164a3e6: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167b800)
Location: drivers/net/phy/phy_device.c:1268
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff8167b800-ffffffff8167b846: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816906e0)
Location: drivers/net/phy/phy_device.c:1316
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff816906e0-ffffffff81690726: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa500)
Location: drivers/net/phy/phy_device.c:1368
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff816fa500-ffffffff816fa546: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81737b40)
Location: drivers/net/phy/phy_device.c:1421
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff81737b40-ffffffff81737b5c: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175ad30)
Location: drivers/net/phy/phy_device.c:1604
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff8175ad30-ffffffff8175ad4c: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81798270)
Location: drivers/net/phy/phy_device.c:1675
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff81798270-ffffffff8179828c: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bbd50)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817bbd50-ffffffff817bbd6c: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81883510)
Location: drivers/net/phy/phy_device.c:2005
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81883510-ffffffff8188352c: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81891c30)
Location: drivers/net/phy/phy_device.c:2042
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81891c30-ffffffff81891c4c: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818743c0)
Location: drivers/net/phy/phy_device.c:2064
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff818743c0-ffffffff818743dc: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81904da0)
Location: drivers/net/phy/phy_device.c:2110
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81904da0-ffffffff81904dbc: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a57dd0)
Location: drivers/net/phy/phy_device.c:2134
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81a57dd0-ffffffff81a57df8: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be1c60)
Location: drivers/net/phy/phy_device.c:2146
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81be1c60-ffffffff81be1c88: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c39550)
Location: drivers/net/phy/phy_device.c:2185
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
```
**Symbols:**

```
ffffffff81c39550-ffffffff81c39578: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cee8e0)
Location: drivers/net/phy/phy_device.c:2192
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
```
**Symbols:**

```
ffffffff81cee8e0-ffffffff81cee908: genphy_restart_aneg (STB_GLOBAL)
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
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4bf0)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffff8000109d4bf0-ffff8000109d4c28: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc7f0)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_nway_reset
```
**Symbols:**

```
c0abc7f0-c0abc818: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a95600)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
c000000000a95600-c000000000a95640: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000620ec4)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffe000620ec4-ffffffe000620efa: genphy_restart_aneg (STB_GLOBAL)
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
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81780820)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff81780820-ffffffff8178083c: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817605b0)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817605b0-ffffffff817605cc: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b0bd0)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817b0bd0-ffffffff817b0bec: genphy_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int genphy_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cab60)
Location: drivers/net/phy/phy_device.c:1673
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817cab60-ffffffff817cab7c: genphy_restart_aneg (STB_GLOBAL)
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
