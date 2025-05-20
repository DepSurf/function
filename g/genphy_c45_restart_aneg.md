# Function: <code>genphy_c45_restart_aneg</code>

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
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff8168f920)
Location: drivers/net/phy/phy-c45.c:98
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff8168f920-ffffffff8168f955: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff816f93b0)
Location: drivers/net/phy/phy-c45.c:98
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff816f93b0-ffffffff816f93e5: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81736550)
Location: drivers/net/phy/phy-c45.c:98
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff81736550-ffffffff81736585: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff817594b0)
Location: drivers/net/phy/phy-c45.c:98
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817594b0-ffffffff817594e5: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81796580)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff81796580-ffffffff8179659f: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff817b9f40)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817b9f40-ffffffff817b9f5f: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff818814c2)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81881190-ffffffff818811af: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff8188fbf2)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff8188f8c0-ffffffff8188f8df: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff818724e2)
Location: drivers/net/phy/phy-c45.c:195
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81872150-ffffffff8187216f: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81902bf2)
Location: drivers/net/phy/phy-c45.c:195
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81902750-ffffffff8190276f: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81a54e7a)
Location: drivers/net/phy/phy-c45.c:323
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81a54b90-ffffffff81a54bfa: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81bde1da)
Location: drivers/net/phy/phy-c45.c:323
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
```
**Symbols:**

```
ffffffff81bde080-ffffffff81bde0ea: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81c3537a)
Location: drivers/net/phy/phy-c45.c:329
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
```
**Symbols:**

```
ffffffff81c35220-ffffffff81c3528a: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81cea34a)
Location: drivers/net/phy/phy-c45.c:338
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_nway_reset
```
**Symbols:**

```
ffffffff81cea110-ffffffff81cea17a: genphy_c45_restart_aneg (STB_GLOBAL)
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
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffff8000109d20e0)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffff8000109d20e0-ffff8000109d211c: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (c0aba270)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
c0aba270-c0aba2a8: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (c000000000a91f60)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
c000000000a91f60-c000000000a91fa4: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffe00061eada)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffe00061eada-ffffffe00061eb10: genphy_c45_restart_aneg (STB_GLOBAL)
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
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff8177ea10)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff8177ea10-ffffffff8177ea2f: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff8175e7b0)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff8175e7b0-ffffffff8175e7cf: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff817aedc0)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817aedc0-ffffffff817aeddf: genphy_c45_restart_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int genphy_c45_restart_aneg(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff817c8d50)
Location: drivers/net/phy/phy-c45.c:152
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_restart_aneg
```
**Symbols:**

```
ffffffff817c8d50-ffffffff817c8d6f: genphy_c45_restart_aneg (STB_GLOBAL)
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
