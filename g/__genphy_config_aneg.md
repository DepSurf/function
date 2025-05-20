# Function: <code>__genphy_config_aneg</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bc710)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
ffffffff817bc710-ffffffff817bc8be: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2052
Inline: False
```
**Symbols:**

```
ffffffff81885ff9-ffffffff81886012: __genphy_config_aneg.cold (STB_LOCAL)
ffffffff818859f0-ffffffff81885b29: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2089
Inline: False
```
**Symbols:**

```
ffffffff81c1949d-ffffffff81c194b6: __genphy_config_aneg.cold (STB_LOCAL)
ffffffff81894290-ffffffff818943c9: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2111
Inline: False
```
**Symbols:**

```
ffffffff81c0b2f0-ffffffff81c0b309: __genphy_config_aneg.cold (STB_LOCAL)
ffffffff81876ac0-ffffffff81876bfb: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2157
Inline: False
```
**Symbols:**

```
ffffffff81d106f5-ffffffff81d1070e: __genphy_config_aneg.cold (STB_LOCAL)
ffffffff819076d0-ffffffff8190780b: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2181
Inline: False
```
**Symbols:**

```
ffffffff81edb485-ffffffff81edb49f: __genphy_config_aneg.cold (STB_LOCAL)
ffffffff81a5a600-ffffffff81a5a886: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be4750)
Location: drivers/net/phy/phy_device.c:2193
Inline: False
```
**Symbols:**

```
ffffffff81be4750-ffffffff81be487e: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3c3c0)
Location: drivers/net/phy/phy_device.c:2232
Inline: False
```
**Symbols:**

```
ffffffff81c3c3c0-ffffffff81c3c4ab: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf17c0)
Location: drivers/net/phy/phy_device.c:2239
Inline: False
```
**Symbols:**

```
ffffffff81cf17c0-ffffffff81cf18ab: __genphy_config_aneg (STB_GLOBAL)
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
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d5750)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
ffff8000109d5750-ffff8000109d58f4: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abd248)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
c0abd248-c0abd3c8: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a96670)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
c000000000a96670-c000000000a9689c: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe0006218e6)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
ffffffe0006218e6-ffffffe000621a76: __genphy_config_aneg (STB_GLOBAL)
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
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817811e0)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
ffffffff817811e0-ffffffff8178138e: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760f70)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
ffffffff81760f70-ffffffff8176111e: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b1590)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
ffffffff817b1590-ffffffff817b173e: __genphy_config_aneg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __genphy_config_aneg(struct phy_device *phydev, bool changed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cb520)
Location: drivers/net/phy/phy_device.c:1690
Inline: True
```
**Symbols:**

```
ffffffff817cb520-ffffffff817cb6ce: __genphy_config_aneg (STB_GLOBAL)
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
