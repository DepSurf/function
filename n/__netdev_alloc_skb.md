# Function: <code>__netdev_alloc_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8170bea0)
Location: net/core/skbuff.c:415
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8170bea0-ffffffff8170bf9b: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81773890)
Location: net/core/skbuff.c:416
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81773890-ffffffff817739a4: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817a0ac0)
Location: net/core/skbuff.c:416
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff817a0ac0-ffffffff817a0bd4: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bb1e0)
Location: net/core/skbuff.c:415
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff817bb1e0-ffffffff817bb2f7: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833250)
Location: net/core/skbuff.c:386
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81833250-ffffffff81833367: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187d6f0)
Location: net/core/skbuff.c:386
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8187d6f0-ffffffff8187d804: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189e310)
Location: net/core/skbuff.c:393
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8189e310-ffffffff8189e41e: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e8b20)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff818e8b20-ffffffff818e8c71: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191ac80)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8191ac80-ffffffff8191add1: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed260)
Location: net/core/skbuff.c:425
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff819ed260-ffffffff819ed3b1: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ecf20)
Location: net/core/skbuff.c:430
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff819ecf20-ffffffff819ed076: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d33f0)
Location: net/core/skbuff.c:476
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - net/core/selftests.c:net_test_get_skb
```
**Symbols:**

```
ffffffff819d33f0-ffffffff819d354b: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:478
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - net/core/selftests.c:net_test_get_skb
```
**Symbols:**

```
ffffffff81d351d7-ffffffff81d35201: __netdev_alloc_skb.cold (STB_LOCAL)
ffffffff81a83120-ffffffff81a832a1: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:478
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - net/core/selftests.c:net_test_get_skb
```
**Symbols:**

```
ffffffff81f01734-ffffffff81f0175e: __netdev_alloc_skb.cold (STB_LOCAL)
ffffffff81bf7f60-ffffffff81bf80cf: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:614
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - net/core/selftests.c:net_test_get_skb
```
**Symbols:**

```
ffffffff820aaca8-ffffffff820aacd2: __netdev_alloc_skb.cold (STB_LOCAL)
ffffffff81da6d10-ffffffff81da6e86: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:698
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - net/core/selftests.c:net_test_get_skb
```
**Symbols:**

```
ffffffff8212c1ec-ffffffff8212c216: __netdev_alloc_skb.cold (STB_LOCAL)
ffffffff81e15f60-ffffffff81e160d8: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:699
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_decompress_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - net/core/selftests.c:net_test_get_skb
```
**Symbols:**

```
ffffffff8220decc-ffffffff8220def6: __netdev_alloc_skb.cold (STB_LOCAL)
ffffffff81ed3380-ffffffff81ed34f8: __netdev_alloc_skb (STB_GLOBAL)
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
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb4fa8)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffff800010bb4fa8-ffff800010bb512c: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd209c)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
**Symbols:**

```
c0cd209c-c0cd2218: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8bf10)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
**Symbols:**

```
c000000000c8bf10-c000000000c8c0e8: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007450a0)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
**Symbols:**

```
ffffffe0007450a0-ffffffe000745216: __netdev_alloc_skb (STB_GLOBAL)
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
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bac80)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff818bac80-ffffffff818badd1: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81874bd0)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
**Symbols:**

```
ffffffff81874bd0-ffffffff81874d1c: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190bc80)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8190bc80-ffffffff8190bdd1: __netdev_alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__netdev_alloc_skb(struct net_device *dev, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192cda0)
Location: net/core/skbuff.c:424
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8192cda0-ffffffff8192cef1: __netdev_alloc_skb (STB_GLOBAL)
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
