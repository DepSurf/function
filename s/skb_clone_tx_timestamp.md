# Function: <code>skb_clone_tx_timestamp</code>

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
In drivers/net/virtio_net.c (0)
Location: include/linux/skbuff.h:2983
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3190
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/skbuff.h:3190
Inline: True
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
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3242
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:3316
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3316
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:3500
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3500
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff818c6cf0)
Location: net/core/timestamping.c:35
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff818c6cf0-ffffffff818c6d86: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff818efe40)
Location: net/core/timestamping.c:35
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff818efe40-ffffffff818efed6: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81941720)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff81941720-ffffffff819417b7: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81976630)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff81976630-ffffffff819766c7: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81a4b3a0)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff81a4b3a0-ffffffff81a4b426: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81a50fc0)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81a50fc0-ffffffff81a51046: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81a36840)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81a36840-ffffffff81a368c6: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81aec590)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81aec590-ffffffff81aec616: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81c6f040)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81c6f040-ffffffff81c6f0df: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81e26de0)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81e26de0-ffffffff81e26e7f: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81e9c380)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81e9c380-ffffffff81e9c41f: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81f5eb10)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81f5eb10-ffffffff81f5ebaf: skb_clone_tx_timestamp (STB_GLOBAL)
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
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffff800010c1cc20)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
**Symbols:**

```
ffff800010c1cc20-ffff800010c1ccc4: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (c0d34af4)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
```
**Symbols:**

```
c0d34af4-c0d34b88: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (c000000000d0db80)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
c000000000d0db80-c000000000d0dc7c: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffe0007969c6)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffe0007969c6-ffffffe000796a46: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:3771
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (0)
Location: include/linux/skbuff.h:3771
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/skbuff.h:3771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81967630)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff81967630-ffffffff819676c7: skb_clone_tx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff819898c0)
Location: net/core/timestamping.c:22
Inline: True
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_net_xmit
```
**Symbols:**

```
ffffffff819898c0-ffffffff81989957: skb_clone_tx_timestamp (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
