# Function: <code>ncsi_vlan_rx_kill_vid</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819708b0)
Location: net/ncsi/ncsi-manage.c:1506
Inline: True
```
**Symbols:**

```
ffffffff819708b0-ffffffff81970a15: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819ca060)
Location: net/ncsi/ncsi-manage.c:1397
Inline: True
```
**Symbols:**

```
ffffffff819ca060-ffffffff819ca1db: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a027f0)
Location: net/ncsi/ncsi-manage.c:1655
Inline: True
```
**Symbols:**

```
ffffffff81a027f0-ffffffff81a0296b: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a717bb)
Location: net/ncsi/ncsi-manage.c:1651
Inline: True
```
**Symbols:**

```
ffffffff81a72131-ffffffff81a7214d: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81a71790-ffffffff81a718f0: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81aa7fab)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
ffffffff81aa88f5-ffffffff81aa8911: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81aa7f80-ffffffff81aa80e0: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba43a0)
Location: net/ncsi/ncsi-manage.c:1641
Inline: True
```
**Symbols:**

```
ffffffff81ba4240-ffffffff81ba4391: ncsi_vlan_rx_kill_vid.part.0 (STB_LOCAL)
ffffffff81ba481c-ffffffff81ba4839: ncsi_vlan_rx_kill_vid.part.0.cold (STB_LOCAL)
ffffffff81ba43a0-ffffffff81ba43bb: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81bb3c10)
Location: net/ncsi/ncsi-manage.c:1641
Inline: True
```
**Symbols:**

```
ffffffff81bb3ab0-ffffffff81bb3c01: ncsi_vlan_rx_kill_vid.part.0 (STB_LOCAL)
ffffffff81c33c7e-ffffffff81c33c9b: ncsi_vlan_rx_kill_vid.part.0.cold (STB_LOCAL)
ffffffff81bb3c10-ffffffff81bb3c2b: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba2adb)
Location: net/ncsi/ncsi-manage.c:1647
Inline: True
```
**Symbols:**

```
ffffffff81c25ff2-ffffffff81c2600e: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81ba2ab0-ffffffff81ba2c10: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81c7062b)
Location: net/ncsi/ncsi-manage.c:1715
Inline: True
```
**Symbols:**

```
ffffffff81d42cc1-ffffffff81d42cdd: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81c70600-ffffffff81c7075d: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1715
Inline: False
```
**Symbols:**

```
ffffffff81f0f650-ffffffff81f0f674: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81e141e0-ffffffff81e1433c: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81feaf60)
Location: net/ncsi/ncsi-manage.c:1715
Inline: False
```
**Symbols:**

```
ffffffff81feaf60-ffffffff81feb0f1: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82067210)
Location: net/ncsi/ncsi-manage.c:1715
Inline: False
```
**Symbols:**

```
ffffffff82067210-ffffffff820673a1: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8213a490)
Location: net/ncsi/ncsi-manage.c:1706
Inline: False
```
**Symbols:**

```
ffffffff8213a490-ffffffff8213a621: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
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
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d7b820)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
ffff800010d7b820-ffff800010d7b9b4: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e76b14)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
c0e76b14-c0e76c9c: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000ebb070)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
c000000000ebb070-c000000000ebb2e4: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a9bf4)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
ffffffe0008a9bf4-ffffffe0008a9d4e: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
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
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a4733b)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
ffffffff81a47c85-ffffffff81a47ca1: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81a47310-ffffffff81a47470: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a03f2b)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
ffffffff81a04875-ffffffff81a04891: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81a03f00-ffffffff81a04060: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ab31eb)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
ffffffff81ab3b35-ffffffff81ab3b51: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81ab31c0-ffffffff81ab3320: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_kill_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81abf58b)
Location: net/ncsi/ncsi-manage.c:1584
Inline: True
```
**Symbols:**

```
ffffffff81abfed1-ffffffff81abfeed: ncsi_vlan_rx_kill_vid.cold (STB_LOCAL)
ffffffff81abf560-ffffffff81abf6c0: ncsi_vlan_rx_kill_vid (STB_GLOBAL)
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
