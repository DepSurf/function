# Function: <code>ethtool_get_max_rxfh_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8171fcb9)
Location: net/core/ethtool.c:612
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81789c54)
Location: net/core/ethtool.c:1072
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817b7532)
Location: net/core/ethtool.c:1083
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817d4974)
Location: net/core/ethtool.c:1086
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8184eed0)
Location: net/core/ethtool.c:1089
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8189ab50)
Location: net/core/ethtool.c:1076
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818bd399)
Location: net/core/ethtool.c:998
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8190a578)
Location: net/core/ethtool.c:1001
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193cb78)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a85660)
Location: net/ethtool/common.c:315
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81a85660-ffffffff81a85726: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a8eff0)
Location: net/ethtool/common.c:342
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81a8eff0-ffffffff81a8f0b6: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a786f0)
Location: net/ethtool/common.c:495
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81a786f0-ffffffff81a787b6: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81b327e0)
Location: net/ethtool/common.c:497
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81b327e0-ffffffff81b328a6: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81cbdd50)
Location: net/ethtool/common.c:501
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81cbdd50-ffffffff81cbde24: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81e7c770)
Location: net/ethtool/common.c:582
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81e7c770-ffffffff81e7c844: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81ed8b30)
Location: net/ethtool/common.c:590
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81ed8b30-ffffffff81ed8c04: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_get_max_rxfh_channel(struct net_device *dev, u32 *max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81f9c950)
Location: net/ethtool/common.c:590
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
```
**Symbols:**

```
ffffffff81f9c950-ffffffff81f9ca79: ethtool_get_max_rxfh_channel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bdb2e0)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c0cf69f4)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cbc310)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe00076345a)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818dcb48)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81896988)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192db78)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194f248)
Location: net/core/ethtool.c:1002
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
