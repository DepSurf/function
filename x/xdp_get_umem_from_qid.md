# Function: <code>xdp_get_umem_from_qid</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a05f64)
Location: net/xdp/xdp_umem.c:60
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffff81a05ec0-ffffffff81a05f0a: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a75688)
Location: net/xdp/xdp_umem.c:63
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffff81a75400-ffffffff81a75451: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81aac4e0)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffff81aac2c0-ffffffff81aac311: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba8797)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81ba8230-ffffffff81ba8284: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffff800010d80df0)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffff800010d80ab0-ffff800010d80b20: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c0e7b2f0)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
c0e7b04c-c0e7b09c: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c000000000ec0a98)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
c000000000ec0770-c000000000ec07c4: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffe0008ad32a)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffe0008ad122-ffffffe0008ad184: xdp_get_umem_from_qid (STB_GLOBAL)
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
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a4b870)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffff81a4b650-ffffffff81a4b6a1: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a08460)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffff81a08240-ffffffff81a08291: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ab7720)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffff81ab7500-ffffffff81ab7551: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct xdp_umem *xdp_get_umem_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ac3b40)
Location: net/xdp/xdp_umem.c:70
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
Direct callers:
  - net/core/ethtool.c:ethtool_set_channels
```
**Symbols:**

```
ffffffff81ac3920-ffffffff81ac3971: xdp_get_umem_from_qid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
