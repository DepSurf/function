# Function: <code>genphy_loopback</code>

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
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816907f0)
Location: drivers/net/phy/phy_device.c:1622
Inline: False
```
**Symbols:**

```
ffffffff816907f0-ffffffff81690844: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa600)
Location: drivers/net/phy/phy_device.c:1670
Inline: False
```
**Symbols:**

```
ffffffff816fa600-ffffffff816fa654: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81737ba0)
Location: drivers/net/phy/phy_device.c:1718
Inline: False
```
**Symbols:**

```
ffffffff81737ba0-ffffffff81737bc2: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175ad90)
Location: drivers/net/phy/phy_device.c:1915
Inline: False
```
**Symbols:**

```
ffffffff8175ad90-ffffffff8175adb2: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817982d0)
Location: drivers/net/phy/phy_device.c:2040
Inline: False
```
**Symbols:**

```
ffffffff817982d0-ffffffff817982f2: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bbdb0)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
ffffffff817bbdb0-ffffffff817bbdd2: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81883570)
Location: drivers/net/phy/phy_device.c:2494
Inline: False
```
**Symbols:**

```
ffffffff81883570-ffffffff81883592: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81891c90)
Location: drivers/net/phy/phy_device.c:2544
Inline: False
```
**Symbols:**

```
ffffffff81891c90-ffffffff81891cb2: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81874c78)
Location: drivers/net/phy/phy_device.c:2566
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_loopback
```
**Symbols:**

```
ffffffff81c0b172-ffffffff81c0b197: genphy_loopback.cold (STB_LOCAL)
ffffffff81874c60-ffffffff81874d51: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff819056c8)
Location: drivers/net/phy/phy_device.c:2612
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_loopback
```
**Symbols:**

```
ffffffff81d10562-ffffffff81d10587: genphy_loopback.cold (STB_LOCAL)
ffffffff819056b0-ffffffff819057a6: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2640
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_loopback
```
**Symbols:**

```
ffffffff81edb274-ffffffff81edb299: genphy_loopback.cold (STB_LOCAL)
ffffffff81a57fc0-ffffffff81a580b5: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be1d50)
Location: drivers/net/phy/phy_device.c:2652
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_loopback
```
**Symbols:**

```
ffffffff81be1d50-ffffffff81be1e71: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c39640)
Location: drivers/net/phy/phy_device.c:2699
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_loopback
```
**Symbols:**

```
ffffffff81c39640-ffffffff81c397a8: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cee9d0)
Location: drivers/net/phy/phy_device.c:2706
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_loopback
```
**Symbols:**

```
ffffffff81cee9d0-ffffffff81ceeb38: genphy_loopback (STB_GLOBAL)
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
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4c98)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
ffff8000109d4c98-ffff8000109d4cdc: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc868)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
c0abc868-c0abc898: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a956c0)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
c000000000a956c0-c000000000a9570c: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000620f62)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
ffffffe000620f62-ffffffe000620f9c: genphy_loopback (STB_GLOBAL)
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
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81780880)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
ffffffff81780880-ffffffff817808a2: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760610)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
ffffffff81760610-ffffffff81760632: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b0c30)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
ffffffff817b0c30-ffffffff817b0c52: genphy_loopback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int genphy_loopback(struct phy_device *phydev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cabc0)
Location: drivers/net/phy/phy_device.c:2009
Inline: False
```
**Symbols:**

```
ffffffff817cabc0-ffffffff817cabe2: genphy_loopback (STB_GLOBAL)
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
