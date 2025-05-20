# Function: <code>genphy_config_eee_advert</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167b922)
Location: drivers/net/phy/phy_device.c:1207
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81690863)
Location: drivers/net/phy/phy_device.c:1255
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa673)
Location: drivers/net/phy/phy_device.c:1307
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81738165)
Location: drivers/net/phy/phy_device.c:1360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175b65d)
Location: drivers/net/phy/phy_device.c:1543
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817981e0)
Location: drivers/net/phy/phy_device.c:1628
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff817981e0-ffffffff8179821a: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bbcc0)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff817bbcc0-ffffffff817bbcfa: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818859f5)
Location: drivers/net/phy/phy_device.c:1874
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81883480-ffffffff818834bc: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81894295)
Location: drivers/net/phy/phy_device.c:1911
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81891ba0-ffffffff81891bdc: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81876ac5)
Location: drivers/net/phy/phy_device.c:1933
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81874330-ffffffff81874364: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff819076d5)
Location: drivers/net/phy/phy_device.c:1979
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81904d10-ffffffff81904d44: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a5a605)
Location: drivers/net/phy/phy_device.c:2008
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81a57d10-ffffffff81a57d62: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be4755)
Location: drivers/net/phy/phy_device.c:2026
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81be1bf0-ffffffff81be1c42: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c394e0)
Location: drivers/net/phy/phy_device.c:2065
Inline: False
```
**Symbols:**

```
ffffffff81c394e0-ffffffff81c39532: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cee870)
Location: drivers/net/phy/phy_device.c:2072
Inline: False
```
**Symbols:**

```
ffffffff81cee870-ffffffff81cee8c2: genphy_config_eee_advert (STB_GLOBAL)
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
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4b38)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffff8000109d4b38-ffff8000109d4b84: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc750)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
c0abc750-c0abc79c: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a95500)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
c000000000a95500-c000000000a95574: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000620e1e)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffe000620e1e-ffffffe000620e66: genphy_config_eee_advert (STB_GLOBAL)
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
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81780790)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81780790-ffffffff817807ca: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760520)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff81760520-ffffffff8176055a: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b0b40)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff817b0b40-ffffffff817b0b7a: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817caad0)
Location: drivers/net/phy/phy_device.c:1626
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
**Symbols:**

```
ffffffff817caad0-ffffffff817cab0a: genphy_config_eee_advert (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
