# Function: <code>phy_request_interrupt</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81795b79)
Location: drivers/net/phy/phy.c:815
Inline: True
```
**Symbols:**

```
ffffffff81795b79-ffffffff81795bd3: phy_request_interrupt.cold (STB_LOCAL)
ffffffff81794850-ffffffff817948dd: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b960d)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
ffffffff817b960d-ffffffff817b9667: phy_request_interrupt.cold (STB_LOCAL)
ffffffff817b83f0-ffffffff817b847d: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:908
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81880acf-ffffffff81880b1b: phy_request_interrupt.cold (STB_LOCAL)
ffffffff818806a0-ffffffff81880730: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:967
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81c18fdb-ffffffff81c19027: phy_request_interrupt.cold (STB_LOCAL)
ffffffff8188d960-ffffffff8188d9cd: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:968
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81c0ae09-ffffffff81c0ae55: phy_request_interrupt.cold (STB_LOCAL)
ffffffff818702a0-ffffffff8187030d: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:994
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81d10193-ffffffff81d101df: phy_request_interrupt.cold (STB_LOCAL)
ffffffff81900880-ffffffff819008ed: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1026
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81edaed0-ffffffff81edaf1c: phy_request_interrupt.cold (STB_LOCAL)
ffffffff81a52540-ffffffff81a525c1: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdbd40)
Location: drivers/net/phy/phy.c:1055
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81bdbd40-ffffffff81bdbe57: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32e50)
Location: drivers/net/phy/phy.c:1289
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81c32e50-ffffffff81c32f67: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7b40)
Location: drivers/net/phy/phy.c:1342
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81ce7b40-ffffffff81ce7c57: phy_request_interrupt (STB_GLOBAL)
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
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d0de0)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
ffff8000109d0de0-ffff8000109d0ec0: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab8df0)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
c0ab8df0-c0ab8ee4: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a904d0)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
c000000000a904d0-c000000000a90600: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061d89a)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
ffffffe00061d89a-ffffffe00061d960: phy_request_interrupt (STB_GLOBAL)
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
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177e0dd)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
ffffffff8177e0dd-ffffffff8177e137: phy_request_interrupt.cold (STB_LOCAL)
ffffffff8177cec0-ffffffff8177cf4d: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175de7d)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
ffffffff8175de7d-ffffffff8175ded7: phy_request_interrupt.cold (STB_LOCAL)
ffffffff8175cc70-ffffffff8175ccfd: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817ae48d)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
ffffffff817ae48d-ffffffff817ae4e7: phy_request_interrupt.cold (STB_LOCAL)
ffffffff817ad270-ffffffff817ad2fd: phy_request_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void phy_request_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c841d)
Location: drivers/net/phy/phy.c:796
Inline: True
```
**Symbols:**

```
ffffffff817c841d-ffffffff817c8477: phy_request_interrupt.cold (STB_LOCAL)
ffffffff817c7200-ffffffff817c728d: phy_request_interrupt (STB_GLOBAL)
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
