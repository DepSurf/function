# Function: <code>phy_resolve_aneg_linkmode</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736730)
Location: drivers/net/phy/phy-core.c:200
Inline: False
```
**Symbols:**

```
ffffffff81736730-ffffffff81736806: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759820)
Location: drivers/net/phy/phy-core.c:353
Inline: False
```
**Symbols:**

```
ffffffff81759820-ffffffff81759980: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796d70)
Location: drivers/net/phy/phy-core.c:289
Inline: True
```
**Symbols:**

```
ffffffff81796d70-ffffffff81796e3c: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba820)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
ffffffff817ba820-ffffffff817ba8ec: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881d00)
Location: drivers/net/phy/phy-core.c:314
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
**Symbols:**

```
ffffffff81881d00-ffffffff81881dd0: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818904d0)
Location: drivers/net/phy/phy-core.c:361
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
**Symbols:**

```
ffffffff818904d0-ffffffff8189059d: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872d90)
Location: drivers/net/phy/phy-core.c:361
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
**Symbols:**

```
ffffffff81872d90-ffffffff81872e5d: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff819034c0)
Location: drivers/net/phy/phy-core.c:362
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
**Symbols:**

```
ffffffff819034c0-ffffffff819035f2: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55f40)
Location: drivers/net/phy/phy-core.c:355
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
**Symbols:**

```
ffffffff81a55f40-ffffffff81a56092: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdfbf0)
Location: drivers/net/phy/phy-core.c:438
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
**Symbols:**

```
ffffffff81bdfbf0-ffffffff81bdfd45: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c374e0)
Location: drivers/net/phy/phy-core.c:441
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
**Symbols:**

```
ffffffff81c374e0-ffffffff81c37635: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cec2c0)
Location: drivers/net/phy/phy-core.c:443
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
**Symbols:**

```
ffffffff81cec2c0-ffffffff81cec415: phy_resolve_aneg_linkmode (STB_GLOBAL)
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
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d3040)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
ffff8000109d3040-ffff8000109d3128: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abafd8)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
c0abafd8-c0abb0c8: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a933c0)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
c000000000a933c0-c000000000a934e0: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f866)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
ffffffe00061f866-ffffffe00061f912: phy_resolve_aneg_linkmode (STB_GLOBAL)
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
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f2f0)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
ffffffff8177f2f0-ffffffff8177f3bc: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f090)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
ffffffff8175f090-ffffffff8175f15c: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af6a0)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
ffffffff817af6a0-ffffffff817af76c: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void phy_resolve_aneg_linkmode(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9630)
Location: drivers/net/phy/phy-core.c:306
Inline: False
```
**Symbols:**

```
ffffffff817c9630-ffffffff817c96fc: phy_resolve_aneg_linkmode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
