# Function: <code>ethtool_copy_validate_indir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff8171fe90)
Location: net/core/ethtool.c:585
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_set_rxfh
```
**Symbols:**

```
ffffffff8171fe90-ffffffff8171ff00: ethtool_copy_validate_indir.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff81789190)
Location: net/core/ethtool.c:1045
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81789190-ffffffff81789221: ethtool_copy_validate_indir.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff817b6a40)
Location: net/core/ethtool.c:1056
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff817b6a40-ffffffff817b6ad1: ethtool_copy_validate_indir.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff817d5460)
Location: net/core/ethtool.c:1059
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff817d5460-ffffffff817d54f1: ethtool_copy_validate_indir.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff8184fe50)
Location: net/core/ethtool.c:1062
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff8184fe50-ffffffff8184fee1: ethtool_copy_validate_indir.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff8189ac30)
Location: net/core/ethtool.c:1049
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff8189ac30-ffffffff8189acc1: ethtool_copy_validate_indir.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff818bd480)
Location: net/core/ethtool.c:971
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff818bd480-ffffffff818bd511: ethtool_copy_validate_indir.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff81909550)
Location: net/core/ethtool.c:974
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81909550-ffffffff819095d3: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff8193bae0)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff8193bae0-ffffffff8193bb75: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a82e20)
Location: net/ethtool/ioctl.c:910
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81a82e20-ffffffff81a82eb6: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8c8f0)
Location: net/ethtool/ioctl.c:914
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81a8c8f0-ffffffff81a8c986: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a759f0)
Location: net/ethtool/ioctl.c:914
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81a759f0-ffffffff81a75a86: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2ebb0)
Location: net/ethtool/ioctl.c:1019
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81b2ebb0-ffffffff81b2ec46: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cb96c0)
Location: net/ethtool/ioctl.c:1041
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81cb96c0-ffffffff81cb9767: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e77e90)
Location: net/ethtool/ioctl.c:1029
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81e77e90-ffffffff81e77f37: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed4010)
Location: net/ethtool/ioctl.c:1030
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81ed4010-ffffffff81ed40b7: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f97a20)
Location: net/ethtool/ioctl.c:1054
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff81f97a20-ffffffff81f97ac7: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffff800010bdbc48)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffff800010bdbc48-ffff800010bdbd14: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ethtool_copy_validate_indir(u32 *indir, void *useraddr, struct ethtool_rxnfc *rx_rings, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c0cf4d84)
Location: net/core/ethtool.c:975
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
c0cf4d84-c0cf4eb8: ethtool_copy_validate_indir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (c000000000cbac20)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
c000000000cbac20-c000000000cbad44: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffe00076368a)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffe00076368a-ffffffe000763726: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff818dbab0)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff818dbab0-ffffffff818dbb45: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff818958f0)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff818958f0-ffffffff81895985: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff8192cae0)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff8192cae0-ffffffff8192cb75: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff8194e1b0)
Location: net/core/ethtool.c:975
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
```
**Symbols:**

```
ffffffff8194e1b0-ffffffff8194e245: ethtool_copy_validate_indir.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
