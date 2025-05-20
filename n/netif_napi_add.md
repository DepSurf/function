# Function: <code>netif_napi_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81715d90)
Location: net/core/dev.c:4734
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81715d90-ffffffff81715e5f: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177ec50)
Location: net/core/dev.c:5073
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8177ec50-ffffffff8177ed27: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ab6d0)
Location: net/core/dev.c:5222
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff817ab6d0-ffffffff817ab85f: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9d20)
Location: net/core/dev.c:5426
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817c9d20-ffffffff817c9ec4: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81843640)
Location: net/core/dev.c:5567
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81843640-ffffffff818437e4: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5697
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81899035-ffffffff81899053: netif_napi_add.cold.160 (STB_LOCAL)
ffffffff81891770-ffffffff818918e8: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b22d0)
Location: net/core/dev.c:6261
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff818b22d0-ffffffff818b2492: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6271
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff8190738a-ffffffff819073b6: netif_napi_add.cold (STB_LOCAL)
ffffffff818fece0-ffffffff818fee69: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff819399c4-ffffffff819399f0: netif_napi_add.cold (STB_LOCAL)
ffffffff81931030-ffffffff819311d8: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6597
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81a0ef40-ffffffff81a0ef6c: netif_napi_add.cold (STB_LOCAL)
ffffffff81a053d0-ffffffff81a054e4: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6724
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81c31250-ffffffff81c3127c: netif_napi_add.cold (STB_LOCAL)
ffffffff81a068e0-ffffffff81a06abc: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6889
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81c23562-ffffffff81c2358e: netif_napi_add.cold (STB_LOCAL)
ffffffff819edba0-ffffffff819eddc6: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6875
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81d362ec-ffffffff81d3632c: netif_napi_add.cold (STB_LOCAL)
ffffffff81a9edd0-ffffffff81a9f06b: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a72013)
Location: include/linux/netdevice.h:2560
Inline: True
```
```
In net/core/gro_cells.c (ffffffff81c8a25d)
Location: include/linux/netdevice.h:2560
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c047df)
Location: include/linux/netdevice.h:2586
Inline: True
```
```
In net/core/gro_cells.c (ffffffff81e44fe9)
Location: include/linux/netdevice.h:2586
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c69ed7)
Location: include/linux/netdevice.h:2639
Inline: True
```
```
In net/core/gro_cells.c (ffffffff81e9fde9)
Location: include/linux/netdevice.h:2639
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d1e887)
Location: include/linux/netdevice.h:2707
Inline: True
```
```
In net/core/gro_cells.c (ffffffff81f62579)
Location: include/linux/netdevice.h:2707
Inline: True
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
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bce7b0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffff800010bce7b0-ffff800010bcea24: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce54c0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
**Symbols:**

```
c0ce54c0-c0ce56b8: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca5d70)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
c000000000ca5d70-c000000000ca6010: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000758b5c)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffe000758b5c-ffffffe000758d3a: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff818d9994-ffffffff818d99c0: netif_napi_add.cold (STB_LOCAL)
ffffffff818d1030-ffffffff818d11d8: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff818937d4-ffffffff81893800: netif_napi_add.cold (STB_LOCAL)
ffffffff8188aee0-ffffffff8188b088: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff8192a9c4-ffffffff8192a9f0: netif_napi_add.cold (STB_LOCAL)
ffffffff81922030-ffffffff819221d8: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void netif_napi_add(struct net_device *dev, struct napi_struct *napi, int (*poll)(struct napi_struct *, int), int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff8194bc12-ffffffff8194bc3e: netif_napi_add.cold (STB_LOCAL)
ffffffff8193ff50-ffffffff819400f6: netif_napi_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
