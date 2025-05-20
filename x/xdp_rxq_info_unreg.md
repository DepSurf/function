# Function: <code>xdp_rxq_info_unreg</code>

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
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bac10)
Location: net/core/xdp.c:111
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff818bac10-ffffffff818baea1: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1f40)
Location: net/core/xdp.c:125
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff818e1f40-ffffffff818e1f8c: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81930d70)
Location: net/core/xdp.c:188
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81930d70-ffffffff81930dbc: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81963020)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81963020-ffffffff8196306c: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35c60)
Location: net/core/xdp.c:135
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netif_alloc_rx_queues
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81a35c60-ffffffff81a35caf: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37e80)
Location: net/core/xdp.c:135
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_page_pool
  - net/core/dev.c:free_netdev
  - net/core/dev.c:netif_alloc_rx_queues
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81a37e80-ffffffff81a37ecf: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1f020)
Location: net/core/xdp.c:135
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81a1f020-ffffffff81a1f06f: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3a66)
Location: net/core/xdp.c:140
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81ad3ad0-ffffffff81ad3b92: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c5172e)
Location: net/core/xdp.c:146
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81c51620-ffffffff81c51678: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e0688e)
Location: net/core/xdp.c:146
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81e06770-ffffffff81e067c8: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e791f3)
Location: net/core/xdp.c:148
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81e78ff0-ffffffff81e79048: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f390c3)
Location: net/core/xdp.c:148
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81f38ec0-ffffffff81f38f18: xdp_rxq_info_unreg (STB_GLOBAL)
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
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06bb8)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffff800010c06bb8-ffff800010c06c1c: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1fec4)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ethernet/ti/cpsw.c:cpsw_create_xdp_rxqs
  - drivers/net/ethernet/ti/cpsw.c:cpsw_destroy_xdp_rxqs
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
c0d1fec4-c0d1ff34: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1270)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
c000000000cf1270-c000000000cf12f8: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000785034)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/xdp.c:xdp_rxq_info_reg
```
**Symbols:**

```
ffffffe000785034-ffffffe00078508c: xdp_rxq_info_unreg (STB_GLOBAL)
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
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81902ff0)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81902ff0-ffffffff8190303c: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bce20)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff818bce20-ffffffff818bce6c: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81954020)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81954020-ffffffff8195406c: xdp_rxq_info_unreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81975cd0)
Location: net/core/xdp.c:162
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81975cd0-ffffffff81975d1c: xdp_rxq_info_unreg (STB_GLOBAL)
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
