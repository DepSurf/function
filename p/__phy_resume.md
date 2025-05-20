# Function: <code>__phy_resume</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa3e0)
Location: drivers/net/phy/phy_device.c:1162
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff816fa3e0-ffffffff816fa435: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81736f30)
Location: drivers/net/phy/phy_device.c:1191
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff81736f30-ffffffff81736f85: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175a0e0)
Location: drivers/net/phy/phy_device.c:1368
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff8175a0e0-ffffffff8175a135: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1466
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff81799a4b-ffffffff81799a5e: __phy_resume.cold (STB_LOCAL)
ffffffff81797de0-ffffffff81797e37: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bbc20)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff817bbc20-ffffffff817bbc78: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818833e0)
Location: drivers/net/phy/phy_device.c:1689
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff818833e0-ffffffff8188343b: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81891b00)
Location: drivers/net/phy/phy_device.c:1726
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81891b00-ffffffff81891b5b: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81873750)
Location: drivers/net/phy/phy_device.c:1745
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81873750-ffffffff8187378e: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81904060)
Location: drivers/net/phy/phy_device.c:1792
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81904060-ffffffff8190409e: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a59ff1)
Location: drivers/net/phy/phy_device.c:1821
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81a56c30-ffffffff81a56c7c: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be43c1)
Location: drivers/net/phy/phy_device.c:1839
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81be09c0-ffffffff81be0a0c: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3c046)
Location: drivers/net/phy/phy_device.c:1878
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81c382d0-ffffffff81c3831a: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf1446)
Location: drivers/net/phy/phy_device.c:1885
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81ced660-ffffffff81ced6aa: __phy_resume (STB_GLOBAL)
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
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4a80)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffff8000109d4a80-ffff8000109d4aec: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc690)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
c0abc690-c0abc710: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a953f0)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
c000000000a953f0-c000000000a95490: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000620d7a)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffe000620d7a-ffffffe000620dd4: __phy_resume (STB_GLOBAL)
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
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817806f0)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff817806f0-ffffffff81780748: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760480)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff81760480-ffffffff817604d8: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b0aa0)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff817b0aa0-ffffffff817b0af8: __phy_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __phy_resume(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817caa30)
Location: drivers/net/phy/phy_device.c:1474
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy_device.c:phy_resume
```
**Symbols:**

```
ffffffff817caa30-ffffffff817caa88: __phy_resume (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
