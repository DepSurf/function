# Function: <code>phy_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815eaf60)
Location: drivers/net/phy/phy_device.c:787
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/mdio_bus.c:mdio_bus_resume
```
**Symbols:**

```
ffffffff815eaf60-ffffffff815eaf95: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164aca0)
Location: drivers/net/phy/phy_device.c:1026
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81649920-ffffffff81649955: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167c1d5)
Location: drivers/net/phy/phy_device.c:1109
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff8167ac00-ffffffff8167ac35: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8169123c)
Location: drivers/net/phy/phy_device.c:1124
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff8168fc10-ffffffff8168fc4c: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa440)
Location: drivers/net/phy/phy_device.c:1181
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff816fa440-ffffffff816fa479: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81737020)
Location: drivers/net/phy/phy_device.c:1210
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81737020-ffffffff81737059: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175a280)
Location: drivers/net/phy/phy_device.c:1387
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff8175a280-ffffffff8175a2b9: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81797e40)
Location: drivers/net/phy/phy_device.c:1485
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81797e40-ffffffff81797e7b: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bbc80)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff817bbc80-ffffffff817bbcbb: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81885627)
Location: drivers/net/phy/phy_device.c:1707
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81883440-ffffffff8188347b: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81893eea)
Location: drivers/net/phy/phy_device.c:1744
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81891b60-ffffffff81891b9b: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81875a70)
Location: drivers/net/phy/phy_device.c:1763
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81875a70-ffffffff81875ad5: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff819065e0)
Location: drivers/net/phy/phy_device.c:1810
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff819065e0-ffffffff81906645: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a59fe2)
Location: drivers/net/phy/phy_device.c:1839
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81a594b0-ffffffff81a59519: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be43b2)
Location: drivers/net/phy/phy_device.c:1857
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81be3210-ffffffff81be3279: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3c037)
Location: drivers/net/phy/phy_device.c:1896
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81c3b110-ffffffff81c3b17b: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf1437)
Location: drivers/net/phy/phy_device.c:1903
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81cf0540-ffffffff81cf05ab: phy_resume (STB_GLOBAL)
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
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4af0)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffff8000109d4af0-ffff8000109d4b38: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc710)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
c0abc710-c0abc750: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a95490)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
c000000000a95490-c000000000a954fc: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000620dd4)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffe000620dd4-ffffffe000620e1e: phy_resume (STB_GLOBAL)
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
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81780750)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81780750-ffffffff8178078b: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817604e0)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff817604e0-ffffffff8176051b: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b0b00)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff817b0b00-ffffffff817b0b3b: phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817caa90)
Location: drivers/net/phy/phy_device.c:1493
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff817caa90-ffffffff817caacb: phy_resume (STB_GLOBAL)
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
