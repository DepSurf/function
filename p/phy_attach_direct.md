# Function: <code>phy_attach_direct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815ebd70)
Location: drivers/net/phy/phy_device.c:625
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach
```
**Symbols:**

```
ffffffff815ebd70-ffffffff815ebef8: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164ab90)
Location: drivers/net/phy/phy_device.c:856
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach
```
**Symbols:**

```
ffffffff8164ab90-ffffffff8164ad0b: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167c040)
Location: drivers/net/phy/phy_device.c:905
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach
```
**Symbols:**

```
ffffffff8167c040-ffffffff8167c239: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81691040)
Location: drivers/net/phy/phy_device.c:902
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach
```
**Symbols:**

```
ffffffff81691040-ffffffff81691295: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fae40)
Location: drivers/net/phy/phy_device.c:931
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach
```
**Symbols:**

```
ffffffff816fae40-ffffffff816fb099: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81738460)
Location: drivers/net/phy/phy_device.c:957
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach
```
**Symbols:**

```
ffffffff81738460-ffffffff817386c5: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175b230)
Location: drivers/net/phy/phy_device.c:1133
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach
```
**Symbols:**

```
ffffffff8175b230-ffffffff8175b495: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1192
Inline: False
```
**Symbols:**

```
ffffffff81799bd1-ffffffff81799c51: phy_attach_direct.cold (STB_LOCAL)
ffffffff81798790-ffffffff81798a1e: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
```
**Symbols:**

```
ffffffff817bd6cd-ffffffff817bd74d: phy_attach_direct.cold (STB_LOCAL)
ffffffff817bc120-ffffffff817bc3ae: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1267
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81885f44-ffffffff81885fc3: phy_attach_direct.cold (STB_LOCAL)
ffffffff818854b0-ffffffff81885795: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1296
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81c193e7-ffffffff81c19467: phy_attach_direct.cold (STB_LOCAL)
ffffffff81893d60-ffffffff81894033: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1313
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81c0b197-ffffffff81c0b217: phy_attach_direct.cold (STB_LOCAL)
ffffffff81875ae0-ffffffff81875dc3: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1360
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81d10587-ffffffff81d1061c: phy_attach_direct.cold (STB_LOCAL)
ffffffff81906650-ffffffff81906941: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1391
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81edb2f8-ffffffff81edb38c: phy_attach_direct.cold (STB_LOCAL)
ffffffff81a59520-ffffffff81a597d6: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1396
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff8209d521-ffffffff8209d53f: phy_attach_direct.cold (STB_LOCAL)
ffffffff81be3290-ffffffff81be363a: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1427
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff8211e401-ffffffff8211e41f: phy_attach_direct.cold (STB_LOCAL)
ffffffff81c3b190-ffffffff81c3b553: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1431
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff821ffa2a-ffffffff821ffa48: phy_attach_direct.cold (STB_LOCAL)
ffffffff81cf05c0-ffffffff81cf095b: phy_attach_direct (STB_GLOBAL)
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
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d5118)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_attach
```
**Symbols:**

```
ffff8000109d5118-ffff8000109d53cc: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abcc68)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_attach
```
**Symbols:**

```
c0abcc68-c0abcf1c: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a95cf0)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_attach
```
**Symbols:**

```
c000000000a95cf0-c000000000a960a8: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000621390)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
Direct callers:
  - drivers/of/of_mdio.c:of_phy_attach
```
**Symbols:**

```
ffffffe000621390-ffffffe000621602: phy_attach_direct (STB_GLOBAL)
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
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
```
**Symbols:**

```
ffffffff8178219d-ffffffff8178221d: phy_attach_direct.cold (STB_LOCAL)
ffffffff81780bf0-ffffffff81780e7e: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
```
**Symbols:**

```
ffffffff81761f2d-ffffffff81761fad: phy_attach_direct.cold (STB_LOCAL)
ffffffff81760980-ffffffff81760c06: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
```
**Symbols:**

```
ffffffff817b254d-ffffffff817b25cd: phy_attach_direct.cold (STB_LOCAL)
ffffffff817b0fa0-ffffffff817b122e: phy_attach_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int phy_attach_direct(struct net_device *dev, struct phy_device *phydev, u32 flags, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1200
Inline: False
```
**Symbols:**

```
ffffffff817cc4dd-ffffffff817cc55d: phy_attach_direct.cold (STB_LOCAL)
ffffffff817caf30-ffffffff817cb1be: phy_attach_direct (STB_GLOBAL)
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
