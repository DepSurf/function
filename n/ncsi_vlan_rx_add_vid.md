# Function: <code>ncsi_vlan_rx_add_vid</code>

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
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81970700)
Location: net/ncsi/ncsi-manage.c:1455
Inline: True
```
**Symbols:**

```
ffffffff81970700-ffffffff819708b0: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c9e90)
Location: net/ncsi/ncsi-manage.c:1346
Inline: True
```
**Symbols:**

```
ffffffff819c9e90-ffffffff819ca059: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a02620)
Location: net/ncsi/ncsi-manage.c:1604
Inline: True
```
**Symbols:**

```
ffffffff81a02620-ffffffff81a027e9: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a7160d)
Location: net/ncsi/ncsi-manage.c:1600
Inline: True
```
**Symbols:**

```
ffffffff81a72110-ffffffff81a72131: ncsi_vlan_rx_add_vid.cold (STB_LOCAL)
ffffffff81a715f0-ffffffff81a71789: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81aa7dfd)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
ffffffff81aa88d4-ffffffff81aa88f5: ncsi_vlan_rx_add_vid.cold (STB_LOCAL)
ffffffff81aa7de0-ffffffff81aa7f79: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba4220)
Location: net/ncsi/ncsi-manage.c:1590
Inline: True
```
**Symbols:**

```
ffffffff81ba40a0-ffffffff81ba4214: ncsi_vlan_rx_add_vid.part.0 (STB_LOCAL)
ffffffff81ba47fa-ffffffff81ba481c: ncsi_vlan_rx_add_vid.part.0.cold (STB_LOCAL)
ffffffff81ba4220-ffffffff81ba423e: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81bb3a90)
Location: net/ncsi/ncsi-manage.c:1590
Inline: True
```
**Symbols:**

```
ffffffff81bb3910-ffffffff81bb3a84: ncsi_vlan_rx_add_vid.part.0 (STB_LOCAL)
ffffffff81c33c5c-ffffffff81c33c7e: ncsi_vlan_rx_add_vid.part.0.cold (STB_LOCAL)
ffffffff81bb3a90-ffffffff81bb3aae: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba2a90)
Location: net/ncsi/ncsi-manage.c:1596
Inline: True
```
**Symbols:**

```
ffffffff81ba2910-ffffffff81ba2a84: ncsi_vlan_rx_add_vid.part.0 (STB_LOCAL)
ffffffff81c25fd0-ffffffff81c25ff2: ncsi_vlan_rx_add_vid.part.0.cold (STB_LOCAL)
ffffffff81ba2a90-ffffffff81ba2aae: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81c705e0)
Location: net/ncsi/ncsi-manage.c:1664
Inline: True
```
**Symbols:**

```
ffffffff81c70460-ffffffff81c705d1: ncsi_vlan_rx_add_vid.part.0 (STB_LOCAL)
ffffffff81d42c9f-ffffffff81d42cc1: ncsi_vlan_rx_add_vid.part.0.cold (STB_LOCAL)
ffffffff81c705e0-ffffffff81c705fe: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1664
Inline: False
```
**Symbols:**

```
ffffffff81f0f62e-ffffffff81f0f650: ncsi_vlan_rx_add_vid.cold (STB_LOCAL)
ffffffff81e14060-ffffffff81e141d6: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81feada0)
Location: net/ncsi/ncsi-manage.c:1664
Inline: False
```
**Symbols:**

```
ffffffff81feada0-ffffffff81feaf4b: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82067050)
Location: net/ncsi/ncsi-manage.c:1664
Inline: False
```
**Symbols:**

```
ffffffff82067050-ffffffff820671fb: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8213a290)
Location: net/ncsi/ncsi-manage.c:1655
Inline: False
```
**Symbols:**

```
ffffffff8213a290-ffffffff8213a471: ncsi_vlan_rx_add_vid (STB_GLOBAL)
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
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d7b638)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
ffff800010d7b638-ffff800010d7b820: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e7695c)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
c0e7695c-c0e76b14: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000ebada0)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
c000000000ebada0-c000000000ebb064: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a9a72)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
ffffffe0008a9a72-ffffffe0008a9bf4: ncsi_vlan_rx_add_vid (STB_GLOBAL)
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
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a4718d)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
ffffffff81a47c64-ffffffff81a47c85: ncsi_vlan_rx_add_vid.cold (STB_LOCAL)
ffffffff81a47170-ffffffff81a47309: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a03d7d)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
ffffffff81a04854-ffffffff81a04875: ncsi_vlan_rx_add_vid.cold (STB_LOCAL)
ffffffff81a03d60-ffffffff81a03ef9: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ab303d)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
ffffffff81ab3b14-ffffffff81ab3b35: ncsi_vlan_rx_add_vid.cold (STB_LOCAL)
ffffffff81ab3020-ffffffff81ab31b9: ncsi_vlan_rx_add_vid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ncsi_vlan_rx_add_vid(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81abf3dd)
Location: net/ncsi/ncsi-manage.c:1533
Inline: True
```
**Symbols:**

```
ffffffff81abfeb0-ffffffff81abfed1: ncsi_vlan_rx_add_vid.cold (STB_LOCAL)
ffffffff81abf3c0-ffffffff81abf559: ncsi_vlan_rx_add_vid (STB_GLOBAL)
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
