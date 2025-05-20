# Function: <code>genphy_read_lpa</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bcdd5)
Location: drivers/net/phy/phy_device.c:1794
Inline: True
```
**Symbols:**

```
ffffffff817bd783-ffffffff817bd7ba: genphy_read_lpa.cold (STB_LOCAL)
ffffffff817bcdb0-ffffffff817bd029: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818841e0)
Location: drivers/net/phy/phy_device.c:2195
Inline: True
```
**Symbols:**

```
ffffffff81883b30-ffffffff81883cfe: genphy_read_lpa.part.0 (STB_LOCAL)
ffffffff81885e6a-ffffffff81885ea1: genphy_read_lpa.part.0.cold (STB_LOCAL)
ffffffff818841e0-ffffffff8188426c: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81892910)
Location: drivers/net/phy/phy_device.c:2232
Inline: True
```
**Symbols:**

```
ffffffff81892260-ffffffff8189240a: genphy_read_lpa.part.0 (STB_LOCAL)
ffffffff81c1930d-ffffffff81c19344: genphy_read_lpa.part.0.cold (STB_LOCAL)
ffffffff81892910-ffffffff8189299c: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81875000)
Location: drivers/net/phy/phy_device.c:2254
Inline: True
```
**Symbols:**

```
ffffffff818748a0-ffffffff81874a20: genphy_read_lpa.part.0 (STB_LOCAL)
ffffffff81c0b13b-ffffffff81c0b172: genphy_read_lpa.part.0.cold (STB_LOCAL)
ffffffff81875000-ffffffff8187506f: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81905ad0)
Location: drivers/net/phy/phy_device.c:2300
Inline: True
```
**Symbols:**

```
ffffffff819052f0-ffffffff81905470: genphy_read_lpa.part.0 (STB_LOCAL)
ffffffff81d1052b-ffffffff81d10562: genphy_read_lpa.part.0.cold (STB_LOCAL)
ffffffff81905ad0-ffffffff81905b3f: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2324
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_read_status
```
**Symbols:**

```
ffffffff81edb2c9-ffffffff81edb2f8: genphy_read_lpa.cold (STB_LOCAL)
ffffffff81a58720-ffffffff81a58928: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be4b10)
Location: drivers/net/phy/phy_device.c:2336
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_read_status
```
**Symbols:**

```
ffffffff81be4b10-ffffffff81be4d21: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3c9f0)
Location: drivers/net/phy/phy_device.c:2378
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_read_status
```
**Symbols:**

```
ffffffff81c3c9f0-ffffffff81c3cbfe: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf1df0)
Location: drivers/net/phy/phy_device.c:2385
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_read_status
```
**Symbols:**

```
ffffffff81cf1df0-ffffffff81cf1ffe: genphy_read_lpa (STB_GLOBAL)
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
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d5d58)
Location: drivers/net/phy/phy_device.c:1794
Inline: True
```
**Symbols:**

```
ffff8000109d5d58-ffff8000109d5ef8: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abd74c)
Location: drivers/net/phy/phy_device.c:1794
Inline: True
```
**Symbols:**

```
c0abd74c-c0abd8b0: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a96ab0)
Location: drivers/net/phy/phy_device.c:1794
Inline: False
```
**Symbols:**

```
c000000000a96ab0-c000000000a96d58: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe00062216c)
Location: drivers/net/phy/phy_device.c:1794
Inline: False
```
**Symbols:**

```
ffffffe00062216c-ffffffe000622322: genphy_read_lpa (STB_GLOBAL)
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
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817818a5)
Location: drivers/net/phy/phy_device.c:1794
Inline: True
```
**Symbols:**

```
ffffffff81782253-ffffffff8178228a: genphy_read_lpa.cold (STB_LOCAL)
ffffffff81781880-ffffffff81781af9: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81761635)
Location: drivers/net/phy/phy_device.c:1794
Inline: True
```
**Symbols:**

```
ffffffff81761fe3-ffffffff8176201a: genphy_read_lpa.cold (STB_LOCAL)
ffffffff81761610-ffffffff81761889: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b1c55)
Location: drivers/net/phy/phy_device.c:1794
Inline: True
```
**Symbols:**

```
ffffffff817b2603-ffffffff817b263a: genphy_read_lpa.cold (STB_LOCAL)
ffffffff817b1c30-ffffffff817b1ea9: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genphy_read_lpa(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cbbe5)
Location: drivers/net/phy/phy_device.c:1794
Inline: True
```
**Symbols:**

```
ffffffff817cc593-ffffffff817cc5ca: genphy_read_lpa.cold (STB_LOCAL)
ffffffff817cbbc0-ffffffff817cbe39: genphy_read_lpa (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
