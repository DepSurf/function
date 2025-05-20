# Function: <code>vlan_kill_rx_filter_info</code>

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
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff819b4d90)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff819b4d90-ffffffff819b4de8: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff819ebde0)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff819ebde0-ffffffff819ebe38: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a5af70)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81a5af70-ffffffff81a5afc8: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a91b90)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81a91b90-ffffffff81a91be8: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81b8d180)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81b8d180-ffffffff81b8d1d8: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81b9cdf0)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81b9cdf0-ffffffff81b9ce48: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81b8bf00)
Location: net/8021q/vlan_core.c:216
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81b8bf00-ffffffff81b8bf58: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81c58480)
Location: net/8021q/vlan_core.c:216
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81c58480-ffffffff81c584d8: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81df98e0)
Location: net/8021q/vlan_core.c:216
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81df98e0-ffffffff81df9960: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81fce200)
Location: net/8021q/vlan_core.c:216
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81fce200-ffffffff81fce280: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff82049b50)
Location: net/8021q/vlan_core.c:216
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff82049b50-ffffffff82049bd0: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff8211c180)
Location: net/8021q/vlan_core.c:216
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff8211c180-ffffffff8211c200: vlan_kill_rx_filter_info (STB_LOCAL)
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
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffff800010d5f7d0)
Location: net/8021q/vlan_core.c:215
Inline: True
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffff800010d5f7d0-ffff800010d5f87c: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (c0e5f378)
Location: net/8021q/vlan_core.c:215
Inline: True
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
c0e5f378-c0e5f404: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (c000000000e9a410)
Location: net/8021q/vlan_core.c:215
Inline: True
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
c000000000e9a410-c000000000e9a4ac: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffe000894e08)
Location: net/8021q/vlan_core.c:215
Inline: True
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffe000894e08-ffffffe000894e9c: vlan_kill_rx_filter_info (STB_LOCAL)
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
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a31220)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81a31220-ffffffff81a31278: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff819ee410)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff819ee410-ffffffff819ee468: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a9cdd0)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81a9cdd0-ffffffff81a9ce28: vlan_kill_rx_filter_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vlan_kill_rx_filter_info(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81aa8fc0)
Location: net/8021q/vlan_core.c:215
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/8021q/vlan_core.c:vlan_filter_drop_vids
  - net/8021q/vlan_core.c:vlan_filter_push_vids
```
**Symbols:**

```
ffffffff81aa8fc0-ffffffff81aa9018: vlan_kill_rx_filter_info (STB_LOCAL)
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
