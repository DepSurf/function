# Function: <code>skb_linearize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fafd0)
Location: include/linux/skbuff.h:2676
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff817098a3)
Location: include/linux/skbuff.h:2676
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pad
```
```
In net/ipv6/ndisc.c (ffffffff817e117e)
Location: include/linux/skbuff.h:2676
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff8165aeb0)
Location: include/linux/skbuff.h:2819
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81771353)
Location: include/linux/skbuff.h:2819
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pad
```
```
In net/ipv6/ndisc.c (ffffffff8184fac7)
Location: include/linux/skbuff.h:2819
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81688c28)
Location: include/linux/skbuff.h:2857
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8179e473)
Location: include/linux/skbuff.h:2857
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pad
```
```
In net/ipv6/ndisc.c (ffffffff818819e7)
Location: include/linux/skbuff.h:2857
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff8169e3eb)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff817bc930)
Location: include/linux/skbuff.h:2923
Inline: True
```
```
In net/core/dev.c (ffffffff817d0a14)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
```
```
In net/ipv6/ndisc.c (ffffffff818a7b03)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff8170958e)
Location: include/linux/skbuff.h:3022
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818364b0)
Location: include/linux/skbuff.h:3022
Inline: True
```
```
In net/core/dev.c (ffffffff8184a669)
Location: include/linux/skbuff.h:3022
Inline: True
Inline callers:
  - net/core/dev.c:do_xdp_generic
```
```
In net/ipv6/ndisc.c (ffffffff8192a5ad)
Location: include/linux/skbuff.h:3022
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff8174811a)
Location: include/linux/skbuff.h:3034
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818805a5)
Location: include/linux/skbuff.h:3034
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81894ab9)
Location: include/linux/skbuff.h:3034
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81982815)
Location: include/linux/skbuff.h:3034
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff8176c1e6)
Location: include/linux/skbuff.h:3110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818a147c)
Location: include/linux/skbuff.h:3110
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff818b53b0)
Location: include/linux/skbuff.h:3110
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff819b8eb5)
Location: include/linux/skbuff.h:3110
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff817a9ffb)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818ebe57)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff818faaff)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffff81a27926)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff817cda63)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8191df87)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff8192cc23)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffff81a5e386)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff818995ad)
Location: include/linux/skbuff.h:3286
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f1627)
Location: include/linux/skbuff.h:3286
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81a06649)
Location: include/linux/skbuff.h:3286
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffff81b57176)
Location: include/linux/skbuff.h:3286
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff818a7adf)
Location: include/linux/skbuff.h:3312
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f0e77)
Location: include/linux/skbuff.h:3312
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81a07bfe)
Location: include/linux/skbuff.h:3312
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/skmsg.c (ffffffff81a3e435)
Location: include/linux/skbuff.h:3312
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81b657e6)
Location: include/linux/skbuff.h:3312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff8188b373)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d6e97)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff819ea57f)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/selftests.c (ffffffff81a364c8)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81a4cc0a)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81b53a96)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff8191de6c)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a874e7)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81aa20ed)
Location: include/linux/skbuff.h:3413
Inline: True
```
```
In net/core/selftests.c (ffffffff81aec198)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81b06b0b)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81c1afd6)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff81a75688)
Location: include/linux/skbuff.h:3782
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81bfbec0)
Location: include/linux/skbuff.h:3782
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81c1a197)
Location: include/linux/skbuff.h:3782
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/selftests.c (ffffffff81c6eb49)
Location: include/linux/skbuff.h:3782
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81c8b6a4)
Location: include/linux/skbuff.h:3782
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81db75f5)
Location: include/linux/skbuff.h:3782
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff81c070ea)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81dabc10)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81dcb227)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/selftests.c (ffffffff81e26889)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81e46e14)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81f872e5)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff81c6c7c0)
Location: include/linux/skbuff.h:3712
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1b710)
Location: include/linux/skbuff.h:3712
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81e3bdb7)
Location: include/linux/skbuff.h:3712
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/selftests.c (ffffffff81e9be29)
Location: include/linux/skbuff.h:3712
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81ea1d74)
Location: include/linux/skbuff.h:3712
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81fe761b)
Location: include/linux/skbuff.h:3712
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff81d21163)
Location: include/linux/skbuff.h:3740
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81ed8cd0)
Location: include/linux/skbuff.h:3740
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81efa2f7)
Location: include/linux/skbuff.h:3740
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/selftests.c (ffffffff81f5e589)
Location: include/linux/skbuff.h:3740
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81f64344)
Location: include/linux/skbuff.h:3740
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff820b547b)
Location: include/linux/skbuff.h:3740
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffff800010a097a4)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffff800010bb86b4)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffff800010bcf548)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffff800010d233c4)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In net/core/skbuff.c (c0cd51c8)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (c0ce5908)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (c0e27a0c)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In net/core/skbuff.c (c000000000c907ac)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (c000000000ca6344)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (c000000000e53354)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In net/core/skbuff.c (ffffffe000747e82)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffe000755a5c)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffe000864d56)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff81792683)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818bdf87)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff818ccc23)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffff819fda16)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In net/core/skbuff.c (ffffffff81877ec7)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81886cb3)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffff819ba7d6)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff817c28e3)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8190ef87)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff8191dc23)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffff81a68496)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
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
In drivers/net/xen-netfront.c (ffffffff817dcba3)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819300b7)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff8193f293)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ipv6/ndisc.c (ffffffff81a74a86)
Location: include/linux/skbuff.h:3262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
</details>
</li>
</ul>

## Differences
