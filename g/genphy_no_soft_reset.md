# Function: <code>genphy_no_soft_reset</code>

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
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8168fb80)
Location: include/linux/phy.h:856
Inline: False
```
**Symbols:**

```
ffffffff8168fb80-ffffffff8168fb88: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816f9880)
Location: include/linux/phy.h:879
Inline: False
```
**Symbols:**

```
ffffffff816f9880-ffffffff816f9888: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81736ea0)
Location: include/linux/phy.h:982
Inline: False
```
**Symbols:**

```
ffffffff81736ea0-ffffffff81736ea3: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175a040)
Location: include/linux/phy.h:991
Inline: False
```
**Symbols:**

```
ffffffff8175a040-ffffffff8175a043: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81795c00)
Location: include/linux/phy.h:1080
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffffffff81797280)
Location: include/linux/phy.h:1080
Inline: False
```
**Symbols:**

```
ffffffff81795c00-ffffffff81795c03: genphy_no_soft_reset (STB_LOCAL)
ffffffff81797280-ffffffff81797283: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff817b9670)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffffffff817bae40)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
ffffffff817b9670-ffffffff817b9673: genphy_no_soft_reset (STB_LOCAL)
ffffffff817bae40-ffffffff817bae43: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffff8000109d1d80)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffff8000109d3998)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
ffff8000109d1d80-ffff8000109d1d88: genphy_no_soft_reset (STB_LOCAL)
ffff8000109d3998-ffff8000109d39a0: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (c0ab9f64)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (c0abb7f0)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
c0ab9f64-c0ab9f78: genphy_no_soft_reset (STB_LOCAL)
c0abb7f0-c0abb804: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (c000000000a91a60)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (c000000000a93ec0)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
c000000000a91a60-c000000000a91a68: genphy_no_soft_reset (STB_LOCAL)
c000000000a93ec0-c000000000a93ec8: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffe00061e72a)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffffffe000620018)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
ffffffe000620018-ffffffe000620026: genphy_no_soft_reset (STB_LOCAL)
ffffffe00061e72a-ffffffe00061e738: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff8177e140)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffffffff8177f910)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
ffffffff8177e140-ffffffff8177e143: genphy_no_soft_reset (STB_LOCAL)
ffffffff8177f910-ffffffff8177f913: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff8175dee0)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffffffff8175f6b0)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
ffffffff8175dee0-ffffffff8175dee3: genphy_no_soft_reset (STB_LOCAL)
ffffffff8175f6b0-ffffffff8175f6b3: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff817ae4f0)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffffffff817afcc0)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
ffffffff817ae4f0-ffffffff817ae4f3: genphy_no_soft_reset (STB_LOCAL)
ffffffff817afcc0-ffffffff817afcc3: genphy_no_soft_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
int genphy_no_soft_reset(struct phy_device *phydev);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff817c8480)
Location: include/linux/phy.h:1095
Inline: False
```
```
In drivers/net/phy/phy_device.c (ffffffff817c9c50)
Location: include/linux/phy.h:1095
Inline: False
```
**Symbols:**

```
ffffffff817c8480-ffffffff817c8483: genphy_no_soft_reset (STB_LOCAL)
ffffffff817c9c50-ffffffff817c9c53: genphy_no_soft_reset (STB_LOCAL)
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
