# Function: <code>phy_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815e9f00)
Location: drivers/net/phy/phy.c:735
Inline: False
```
**Symbols:**

```
ffffffff815e9f00-ffffffff815e9f78: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81648890)
Location: drivers/net/phy/phy.c:823
Inline: False
```
**Symbols:**

```
ffffffff81648890-ffffffff81648916: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679970)
Location: drivers/net/phy/phy.c:879
Inline: False
```
**Symbols:**

```
ffffffff81679970-ffffffff816799f6: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168dde0)
Location: drivers/net/phy/phy.c:947
Inline: False
```
**Symbols:**

```
ffffffff8168dde0-ffffffff8168de61: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f7910)
Location: drivers/net/phy/phy.c:769
Inline: False
```
**Symbols:**

```
ffffffff816f7910-ffffffff816f7997: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81734bb0)
Location: drivers/net/phy/phy.c:760
Inline: False
```
**Symbols:**

```
ffffffff81734bb0-ffffffff81734c06: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81759110)
Location: drivers/net/phy/phy.c:840
Inline: True
```
**Symbols:**

```
ffffffff81759110-ffffffff8175918f: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81795a80)
Location: drivers/net/phy/phy.c:854
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81795a80-ffffffff81795af5: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b9580)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff817b9580-ffffffff817b95f5: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:947
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81880b2f-ffffffff81880b43: phy_stop.cold (STB_LOCAL)
ffffffff818809c0-ffffffff81880ab7: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1006
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81c1903b-ffffffff81c1904f: phy_stop.cold (STB_LOCAL)
ffffffff8188f180-ffffffff8188f277: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1007
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81c0ae69-ffffffff81c0ae7d: phy_stop.cold (STB_LOCAL)
ffffffff81871ac0-ffffffff81871bb7: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1033
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81d1020e-ffffffff81d10222: phy_stop.cold (STB_LOCAL)
ffffffff819021d0-ffffffff819022c7: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1065
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81edaf4b-ffffffff81edaf5f: phy_stop.cold (STB_LOCAL)
ffffffff81a540f0-ffffffff81a541ff: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdd910)
Location: drivers/net/phy/phy.c:1094
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81bdd910-ffffffff81bdda2c: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c345c0)
Location: drivers/net/phy/phy.c:1328
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81c345c0-ffffffff81c346f1: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce8a20)
Location: drivers/net/phy/phy.c:1488
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81ce8a20-ffffffff81ce8b68: phy_stop (STB_GLOBAL)
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
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d1cf8)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fman/mac.c:stop
```
**Symbols:**

```
ffff8000109d1cf8-ffff8000109d1d7c: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab9ed4)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_stop
```
**Symbols:**

```
c0ab9ed4-c0ab9f64: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a919a0)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
c000000000a919a0-c000000000a91a54: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061e696)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffe00061e696-ffffffe00061e72a: phy_stop (STB_GLOBAL)
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
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177e050)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff8177e050-ffffffff8177e0c5: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175ddf0)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff8175ddf0-ffffffff8175de65: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817ae400)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff817ae400-ffffffff817ae475: phy_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void phy_stop(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c8390)
Location: drivers/net/phy/phy.c:835
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff817c8390-ffffffff817c8405: phy_stop (STB_GLOBAL)
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
