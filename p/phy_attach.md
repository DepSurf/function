# Function: <code>phy_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815ebf00)
Location: drivers/net/phy/phy_device.c:699
Inline: False
```
**Symbols:**

```
ffffffff815ebf00-ffffffff815ebf70: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164ad10)
Location: drivers/net/phy/phy_device.c:937
Inline: False
```
**Symbols:**

```
ffffffff8164ad10-ffffffff8164ad83: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167c240)
Location: drivers/net/phy/phy_device.c:1012
Inline: False
```
**Symbols:**

```
ffffffff8167c240-ffffffff8167c2bf: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816912a0)
Location: drivers/net/phy/phy_device.c:1028
Inline: False
```
**Symbols:**

```
ffffffff816912a0-ffffffff8169131f: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fb0a0)
Location: drivers/net/phy/phy_device.c:1065
Inline: False
```
**Symbols:**

```
ffffffff816fb0a0-ffffffff816fb11f: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1091
Inline: False
```
**Symbols:**

```
ffffffff81739023-ffffffff8173903e: phy_attach.cold.26 (STB_LOCAL)
ffffffff817386d0-ffffffff8173873b: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1267
Inline: False
```
**Symbols:**

```
ffffffff8175c765-ffffffff8175c780: phy_attach.cold.31 (STB_LOCAL)
ffffffff8175b4a0-ffffffff8175b50b: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81798c36)
Location: drivers/net/phy/phy_device.c:1322
Inline: True
```
**Symbols:**

```
ffffffff81799c6c-ffffffff81799c87: phy_attach.cold (STB_LOCAL)
ffffffff81798c10-ffffffff81798c89: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bc6b6)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
ffffffff817bd768-ffffffff817bd783: phy_attach.cold (STB_LOCAL)
ffffffff817bc690-ffffffff817bc710: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81885836)
Location: drivers/net/phy/phy_device.c:1404
Inline: True
```
**Symbols:**

```
ffffffff81885fc3-ffffffff81885fde: phy_attach.cold (STB_LOCAL)
ffffffff81885810-ffffffff81885890: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818940d6)
Location: drivers/net/phy/phy_device.c:1441
Inline: True
```
**Symbols:**

```
ffffffff81c19467-ffffffff81c19482: phy_attach.cold (STB_LOCAL)
ffffffff818940b0-ffffffff81894130: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81875e66)
Location: drivers/net/phy/phy_device.c:1460
Inline: True
```
**Symbols:**

```
ffffffff81c0b217-ffffffff81c0b232: phy_attach.cold (STB_LOCAL)
ffffffff81875e40-ffffffff81875ec0: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff819069e6)
Location: drivers/net/phy/phy_device.c:1507
Inline: True
```
**Symbols:**

```
ffffffff81d1061c-ffffffff81d10637: phy_attach.cold (STB_LOCAL)
ffffffff819069c0-ffffffff81906a40: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a59895)
Location: drivers/net/phy/phy_device.c:1536
Inline: True
```
**Symbols:**

```
ffffffff81edb38c-ffffffff81edb3a7: phy_attach.cold (STB_LOCAL)
ffffffff81a59870-ffffffff81a598fa: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be36f0)
Location: drivers/net/phy/phy_device.c:1551
Inline: True
```
**Symbols:**

```
ffffffff81be36f0-ffffffff81be37a4: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3b610)
Location: drivers/net/phy/phy_device.c:1589
Inline: True
```
**Symbols:**

```
ffffffff81c3b610-ffffffff81c3b6c4: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf0a10)
Location: drivers/net/phy/phy_device.c:1592
Inline: True
```
**Symbols:**

```
ffffffff81cf0a10-ffffffff81cf0ac4: phy_attach (STB_GLOBAL)
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
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d56a8)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
ffff8000109d56a8-ffff8000109d574c: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abd1b4)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
c0abd1b4-c0abd248: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a96550)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
c000000000a96550-c000000000a96664: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000621852)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
ffffffe000621852-ffffffe0006218e6: phy_attach (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81781186)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
ffffffff81782238-ffffffff81782253: phy_attach.cold (STB_LOCAL)
ffffffff81781160-ffffffff817811e0: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760f16)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
ffffffff81761fc8-ffffffff81761fe3: phy_attach.cold (STB_LOCAL)
ffffffff81760ef0-ffffffff81760f70: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b1536)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
ffffffff817b25e8-ffffffff817b2603: phy_attach.cold (STB_LOCAL)
ffffffff817b1510-ffffffff817b1590: phy_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct phy_device *phy_attach(struct net_device *dev, const char *bus_id, phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cb4c6)
Location: drivers/net/phy/phy_device.c:1330
Inline: True
```
**Symbols:**

```
ffffffff817cc578-ffffffff817cc593: phy_attach.cold (STB_LOCAL)
ffffffff817cb4a0-ffffffff817cb520: phy_attach (STB_GLOBAL)
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
