# Function: <code>__skb_linearize</code>

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
In drivers/net/xen-netfront.c (ffffffff815fafd8)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8170991c)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_pad
```
```
In net/core/dev.c (ffffffff81718dd2)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv4/gre_offload.c (ffffffff817a53f0)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ndisc.c (ffffffff817e123b)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/packet/af_packet.c (ffffffff8180379b)
Location: include/linux/skbuff.h:2664
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/xen-netfront.c (ffffffff8165aedf)
Location: include/linux/skbuff.h:2807
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81772d76)
Location: include/linux/skbuff.h:2807
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_pad
```
```
In net/core/dev.c (ffffffff817850a7)
Location: include/linux/skbuff.h:2807
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff8184fb56)
Location: include/linux/skbuff.h:2807
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/packet/af_packet.c (ffffffff818749db)
Location: include/linux/skbuff.h:2807
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/xen-netfront.c (ffffffff81688cd2)
Location: include/linux/skbuff.h:2845
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8179ff1a)
Location: include/linux/skbuff.h:2845
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_pad
```
```
In net/core/dev.c (ffffffff817b26b7)
Location: include/linux/skbuff.h:2845
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff81881a76)
Location: include/linux/skbuff.h:2845
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
In drivers/net/xen-netfront.c (ffffffff8169e483)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff817bec85)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817d0c9a)
Location: include/linux/skbuff.h:2911
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff818a7b4d)
Location: include/linux/skbuff.h:2911
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
In drivers/net/xen-netfront.c (ffffffff81709623)
Location: include/linux/skbuff.h:3010
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81838777)
Location: include/linux/skbuff.h:3010
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8184a78d)
Location: include/linux/skbuff.h:3010
Inline: True
Inline callers:
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff8192a5fd)
Location: include/linux/skbuff.h:3010
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
In drivers/net/xen-netfront.c (ffffffff81748138)
Location: include/linux/skbuff.h:3022
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81882b1c)
Location: include/linux/skbuff.h:3022
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff8189388b)
Location: include/linux/skbuff.h:3022
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff8198289a)
Location: include/linux/skbuff.h:3022
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
In drivers/net/xen-netfront.c (ffffffff8176c202)
Location: include/linux/skbuff.h:3098
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818a358a)
Location: include/linux/skbuff.h:3098
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff818b42a7)
Location: include/linux/skbuff.h:3098
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff819b8f1b)
Location: include/linux/skbuff.h:3098
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
In drivers/net/xen-netfront.c (ffffffff817aa028)
Location: include/linux/skbuff.h:3185
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818ee2bb)
Location: include/linux/skbuff.h:3185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff818fadc9)
Location: include/linux/skbuff.h:3185
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff81a27998)
Location: include/linux/skbuff.h:3185
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
In drivers/net/xen-netfront.c (ffffffff817cda90)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819203af)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff8192cf24)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff81a5e3f8)
Location: include/linux/skbuff.h:3250
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
In drivers/net/xen-netfront.c (ffffffff81899669)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f39c5)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81a0692b)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff81b571ec)
Location: include/linux/skbuff.h:3274
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
In drivers/net/xen-netfront.c (ffffffff818a7b9b)
Location: include/linux/skbuff.h:3300
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819f39ec)
Location: include/linux/skbuff.h:3300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81a07f12)
Location: include/linux/skbuff.h:3300
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/skmsg.c (ffffffff81a3e516)
Location: include/linux/skbuff.h:3300
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81b6585c)
Location: include/linux/skbuff.h:3300
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
In drivers/net/xen-netfront.c (ffffffff8188b42e)
Location: include/linux/skbuff.h:3364
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d9be0)
Location: include/linux/skbuff.h:3364
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff819ea888)
Location: include/linux/skbuff.h:3364
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/selftests.c (ffffffff81a364d5)
Location: include/linux/skbuff.h:3364
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81a4ccb3)
Location: include/linux/skbuff.h:3364
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81b53b0c)
Location: include/linux/skbuff.h:3364
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
In drivers/net/xen-netfront.c (ffffffff8191df9d)
Location: include/linux/skbuff.h:3401
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a8a075)
Location: include/linux/skbuff.h:3401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81aa11d9)
Location: include/linux/skbuff.h:3401
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/selftests.c (ffffffff81aec1a5)
Location: include/linux/skbuff.h:3401
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81b06bd4)
Location: include/linux/skbuff.h:3401
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81c1b04c)
Location: include/linux/skbuff.h:3401
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
In drivers/net/xen-netfront.c (ffffffff81a7575c)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81bff646)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81c1a265)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/selftests.c (ffffffff81c6ec79)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81c8b790)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81db766c)
Location: include/linux/skbuff.h:3770
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
In drivers/net/xen-netfront.c (ffffffff81c071fb)
Location: include/linux/skbuff.h:3666
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81dae027)
Location: include/linux/skbuff.h:3666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81dcb2f5)
Location: include/linux/skbuff.h:3666
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/selftests.c (ffffffff81e269b9)
Location: include/linux/skbuff.h:3666
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81e46f00)
Location: include/linux/skbuff.h:3666
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81f8735c)
Location: include/linux/skbuff.h:3666
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
In drivers/net/xen-netfront.c (ffffffff81c6c89f)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e1d9af)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81e3be7f)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/selftests.c (ffffffff81e9bf59)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81ea1e60)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff81fe76d6)
Location: include/linux/skbuff.h:3700
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
In drivers/net/xen-netfront.c (ffffffff81d21241)
Location: include/linux/skbuff.h:3728
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81edb0bc)
Location: include/linux/skbuff.h:3728
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81efa3bf)
Location: include/linux/skbuff.h:3728
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/selftests.c (ffffffff81f5e6b9)
Location: include/linux/skbuff.h:3728
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/skmsg.c (ffffffff81f64430)
Location: include/linux/skbuff.h:3728
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv6/ndisc.c (ffffffff820b5536)
Location: include/linux/skbuff.h:3728
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
In drivers/net/xen-netfront.c (ffff800010a0985c)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffff800010bbad9c)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffff800010bcf884)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffff800010d23448)
Location: include/linux/skbuff.h:3250
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
In net/core/skbuff.c (c0cd75c0)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (c0ce5be0)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (c0e27aa8)
Location: include/linux/skbuff.h:3250
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
In net/core/skbuff.c (c000000000c93b48)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (c000000000ca6780)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (c000000000e53430)
Location: include/linux/skbuff.h:3250
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
In net/core/skbuff.c (ffffffe000749f30)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffe000755ca0)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffe000864dce)
Location: include/linux/skbuff.h:3250
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
In drivers/net/xen-netfront.c (ffffffff817926b0)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff818c03af)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff818ccf24)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff819fda88)
Location: include/linux/skbuff.h:3250
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
In net/core/skbuff.c (ffffffff8187a2ef)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff81886fb4)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff819ba848)
Location: include/linux/skbuff.h:3250
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
In drivers/net/xen-netfront.c (ffffffff817c2910)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819113af)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff8191df24)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff81a68508)
Location: include/linux/skbuff.h:3250
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
In drivers/net/xen-netfront.c (ffffffff817dcbd0)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff8193250f)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__skb_pad
```
```
In net/core/dev.c (ffffffff8193f5ad)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv6/ndisc.c (ffffffff81a74af8)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
</details>
</li>
</ul>

## Differences
