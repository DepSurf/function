# Function: <code>xsk_get_pool_from_qid</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xsk_buff_pool *xsk_get_pool_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb5680)
Location: net/xdp/xsk.c:97
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/xdp/xsk_buff_pool.c:__xp_assign_dev
```
**Symbols:**

```
ffffffff81bb5680-ffffffff81bb56d4: xsk_get_pool_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xsk_buff_pool *xsk_get_pool_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba4670)
Location: net/xdp/xsk.c:97
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81ba4670-ffffffff81ba46c4: xsk_get_pool_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xsk_buff_pool *xsk_get_pool_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c721e0)
Location: net/xdp/xsk.c:97
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81c721e0-ffffffff81c72238: xsk_get_pool_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xsk_buff_pool *xsk_get_pool_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e15d80)
Location: net/xdp/xsk.c:97
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81e15d80-ffffffff81e15deb: xsk_get_pool_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xsk_buff_pool *xsk_get_pool_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fecd80)
Location: net/xdp/xsk.c:97
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff81fecd80-ffffffff81fecdeb: xsk_get_pool_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xsk_buff_pool *xsk_get_pool_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff82069020)
Location: net/xdp/xsk.c:98
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff82069020-ffffffff8206908b: xsk_get_pool_from_qid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xsk_buff_pool *xsk_get_pool_from_qid(struct net_device *dev, u16 queue_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213c2b0)
Location: net/xdp/xsk.c:100
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
**Symbols:**

```
ffffffff8213c2b0-ffffffff8213c315: xsk_get_pool_from_qid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
