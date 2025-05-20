# Function: <code>phy_connect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815ebfd0)
Location: drivers/net/phy/phy_device.c:503
Inline: False
```
**Symbols:**

```
ffffffff815ebfd0-ffffffff815ec044: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164ae40)
Location: drivers/net/phy/phy_device.c:707
Inline: False
```
**Symbols:**

```
ffffffff8164ae40-ffffffff8164aeb7: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167c370)
Location: drivers/net/phy/phy_device.c:755
Inline: False
```
**Symbols:**

```
ffffffff8167c370-ffffffff8167c3f3: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816913d0)
Location: drivers/net/phy/phy_device.c:750
Inline: False
```
**Symbols:**

```
ffffffff816913d0-ffffffff81691453: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fb1d0)
Location: drivers/net/phy/phy_device.c:763
Inline: False
```
**Symbols:**

```
ffffffff816fb1d0-ffffffff816fb253: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:786
Inline: False
```
**Symbols:**

```
ffffffff8173903e-ffffffff81739059: phy_connect.cold.27 (STB_LOCAL)
ffffffff817387f0-ffffffff8173885f: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:964
Inline: False
```
**Symbols:**

```
ffffffff8175c780-ffffffff8175c79b: phy_connect.cold.32 (STB_LOCAL)
ffffffff8175b5c0-ffffffff8175b62f: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:981
Inline: False
```
**Symbols:**

```
ffffffff81799c51-ffffffff81799c6c: phy_connect.cold (STB_LOCAL)
ffffffff81798ba0-ffffffff81798c0b: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:989
Inline: False
```
**Symbols:**

```
ffffffff817bd74d-ffffffff817bd768: phy_connect.cold (STB_LOCAL)
ffffffff817bc610-ffffffff817bc682: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:991
Inline: False
```
**Symbols:**

```
ffffffff81885fde-ffffffff81885ff9: phy_connect.cold (STB_LOCAL)
ffffffff81885890-ffffffff81885960: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1013
Inline: False
```
**Symbols:**

```
ffffffff81c19482-ffffffff81c1949d: phy_connect.cold (STB_LOCAL)
ffffffff81894130-ffffffff81894200: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1030
Inline: False
```
**Symbols:**

```
ffffffff81c0b232-ffffffff81c0b24d: phy_connect.cold (STB_LOCAL)
ffffffff81875ec0-ffffffff81875f90: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1077
Inline: False
```
**Symbols:**

```
ffffffff81d10637-ffffffff81d10652: phy_connect.cold (STB_LOCAL)
ffffffff81906a40-ffffffff81906b10: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1108
Inline: False
```
**Symbols:**

```
ffffffff81edb3a7-ffffffff81edb3c2: phy_connect.cold (STB_LOCAL)
ffffffff81a59900-ffffffff81a599f5: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be3c70)
Location: drivers/net/phy/phy_device.c:1113
Inline: False
```
**Symbols:**

```
ffffffff81be3c70-ffffffff81be3d7b: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3b740)
Location: drivers/net/phy/phy_device.c:1144
Inline: False
```
**Symbols:**

```
ffffffff81c3b740-ffffffff81c3b84b: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf0b40)
Location: drivers/net/phy/phy_device.c:1147
Inline: False
```
**Symbols:**

```
ffffffff81cf0b40-ffffffff81cf0c4b: phy_connect (STB_GLOBAL)
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
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d5600)
Location: drivers/net/phy/phy_device.c:989
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
```
**Symbols:**

```
ffff8000109d5600-ffff8000109d56a8: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abd124)
Location: drivers/net/phy/phy_device.c:989
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
```
**Symbols:**

```
c0abd124-c0abd1b4: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a96470)
Location: drivers/net/phy/phy_device.c:989
Inline: False
```
**Symbols:**

```
c000000000a96470-c000000000a9654c: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe0006217c2)
Location: drivers/net/phy/phy_device.c:989
Inline: False
```
**Symbols:**

```
ffffffe0006217c2-ffffffe000621852: phy_connect (STB_GLOBAL)
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
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:989
Inline: False
```
**Symbols:**

```
ffffffff8178221d-ffffffff81782238: phy_connect.cold (STB_LOCAL)
ffffffff817810e0-ffffffff81781152: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:989
Inline: False
```
**Symbols:**

```
ffffffff81761fad-ffffffff81761fc8: phy_connect.cold (STB_LOCAL)
ffffffff81760e70-ffffffff81760ee2: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:989
Inline: False
```
**Symbols:**

```
ffffffff817b25cd-ffffffff817b25e8: phy_connect.cold (STB_LOCAL)
ffffffff817b1490-ffffffff817b1502: phy_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct phy_device *phy_connect(struct net_device *dev, const char *bus_id, void (*handler)(struct net_device *), phy_interface_t interface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:989
Inline: False
```
**Symbols:**

```
ffffffff817cc55d-ffffffff817cc578: phy_connect.cold (STB_LOCAL)
ffffffff817cb420-ffffffff817cb492: phy_connect (STB_GLOBAL)
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
