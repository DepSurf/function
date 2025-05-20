# Function: <code>skb_tx_timestamp</code>

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
In drivers/net/virtio_net.c (ffffffff815f236a)
Location: include/linux/skbuff.h:3046
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
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
In drivers/net/tun.c (ffffffff8164d4c0)
Location: include/linux/skbuff.h:3253
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81651caa)
Location: include/linux/skbuff.h:3253
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
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
In drivers/net/tun.c (ffffffff8167f1e0)
Location: include/linux/skbuff.h:3305
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/loopback.c (ffffffff8168d85e)
Location: include/linux/skbuff.h:3372
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff816943fe)
Location: include/linux/skbuff.h:3372
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/loopback.c (ffffffff816f73de)
Location: include/linux/skbuff.h:3556
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff816fe51e)
Location: include/linux/skbuff.h:3556
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff81734565)
Location: include/linux/skbuff.h:3566
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8173d6c9)
Location: include/linux/skbuff.h:3566
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff817576b5)
Location: include/linux/skbuff.h:3651
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81761087)
Location: include/linux/skbuff.h:3651
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff81793e65)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8179ed05)
Location: include/linux/skbuff.h:3760
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff817b7995)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817c34f1)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8187ead5)
Location: include/linux/skbuff.h:3853
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8188e79c)
Location: include/linux/skbuff.h:3853
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8188d060)
Location: include/linux/skbuff.h:3882
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8189d106)
Location: include/linux/skbuff.h:3882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff818a7932)
Location: include/linux/skbuff.h:3882
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff8186f9a0)
Location: include/linux/skbuff.h:3946
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8187f935)
Location: include/linux/skbuff.h:3946
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8188b1db)
Location: include/linux/skbuff.h:3946
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff818fff40)
Location: include/linux/skbuff.h:3983
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81910abe)
Location: include/linux/skbuff.h:3983
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8191dd6e)
Location: include/linux/skbuff.h:3983
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/net/loopback.c (ffffffff81a519b4)
Location: include/linux/skbuff.h:4402
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81a60897)
Location: include/linux/skbuff.h:4402
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81a754c5)
Location: include/linux/skbuff.h:4402
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/net/loopback.c (ffffffff81bdabf4)
Location: include/linux/skbuff.h:4298
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81bece58)
Location: include/linux/skbuff.h:4298
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81c06f20)
Location: include/linux/skbuff.h:4298
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/net/loopback.c (ffffffff81c31694)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81c45359)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81c50eb2)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c605)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/net/loopback.c (ffffffff81ce4514)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81cfac88)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/virtio_net.c (ffffffff81d06eef)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81d20fb1)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffff8000109d01c0)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffff8000109deeb0)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb994)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (c0ab8424)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c0ac2ab4)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acdc54)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad29d8)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (c000000000a8f108)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c000000000aa07fc)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffe00061cc60)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffe000628110)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/loopback.c (ffffffff8177c475)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81787f9d)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
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
In drivers/net/loopback.c (ffffffff8175c225)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817678ed)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff817ac815)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817b8371)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/loopback.c (ffffffff817c67a5)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff817d0676)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
</details>
</li>
</ul>

## Differences
