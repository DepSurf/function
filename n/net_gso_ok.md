# Function: <code>net_gso_ok</code>

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
In drivers/net/xen-netfront.c (ffffffff815facba)
Location: include/linux/netdevice.h:3803
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff817008e7)
Location: include/linux/netdevice.h:3803
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/dev.c (ffffffff8171c668)
Location: include/linux/netdevice.h:3803
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81765e74)
Location: include/linux/netdevice.h:3803
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_send_mss
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176ef21)
Location: include/linux/netdevice.h:3803
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_offload.c (ffffffff817832a0)
Location: include/linux/netdevice.h:3803
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8178b33c)
Location: include/linux/netdevice.h:3803
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff8180168e)
Location: include/linux/netdevice.h:3803
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff8165ab9c)
Location: include/linux/netdevice.h:4082
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff817672a5)
Location: include/linux/netdevice.h:4082
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/dev.c (ffffffff8178501c)
Location: include/linux/netdevice.h:4082
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp.c (ffffffff817d6688)
Location: include/linux/netdevice.h:4082
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff817d8cb6)
Location: include/linux/netdevice.h:4082
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0824)
Location: include/linux/netdevice.h:4082
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff817f8bee)
Location: include/linux/netdevice.h:4082
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818669fe)
Location: include/linux/netdevice.h:4082
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff81688929)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81794325)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff8179f8b2)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817b262c)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp.c (ffffffff818065da)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff818094c5)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_offload.c (ffffffff8182159b)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81829abe)
Location: include/linux/netdevice.h:4036
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818990fe)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff8169e0da)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff817b26fc)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff817be90e)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817cfe31)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp.c (ffffffff81826882)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff818299ce)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_offload.c (ffffffff8184227b)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8184ad0f)
Location: include/linux/netdevice.h:4088
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818bf31e)
Location: include/linux/netdevice.h:4088
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff8170927a)
Location: include/linux/netdevice.h:4122
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff8182a8bf)
Location: include/linux/netdevice.h:4122
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff8183820e)
Location: include/linux/netdevice.h:4122
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81849781)
Location: include/linux/netdevice.h:4122
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp.c (ffffffff818a48f8)
Location: include/linux/netdevice.h:4122
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff818a8c59)
Location: include/linux/netdevice.h:4122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1b58)
Location: include/linux/netdevice.h:4122
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81747fef)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81874a37)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81882a35)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81893773)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff8191782d)
Location: include/linux/netdevice.h:4228
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff8176c0bc)
Location: include/linux/netdevice.h:4465
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81895249)
Location: include/linux/netdevice.h:4465
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff818a34bb)
Location: include/linux/netdevice.h:4465
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818b4192)
Location: include/linux/netdevice.h:4465
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81945f64)
Location: include/linux/netdevice.h:4465
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817a9ecc)
Location: include/linux/netdevice.h:4491
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff818df779)
Location: include/linux/netdevice.h:4491
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff818edf33)
Location: include/linux/netdevice.h:4491
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81900a86)
Location: include/linux/netdevice.h:4491
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa592)
Location: include/linux/netdevice.h:4491
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817cd934)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81911949)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81920025)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81932db6)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1262)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff818994cf)
Location: include/linux/netdevice.h:4696
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff819e3789)
Location: include/linux/netdevice.h:4696
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff819f3624)
Location: include/linux/netdevice.h:4696
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a07cbb)
Location: include/linux/netdevice.h:4696
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace8a2)
Location: include/linux/netdevice.h:4696
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff818a79f2)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff819e32de)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff819f364e)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a0938b)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada8c2)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff8188b287)
Location: include/linux/netdevice.h:5023
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff819c932b)
Location: include/linux/netdevice.h:5023
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff819d989f)
Location: include/linux/netdevice.h:5023
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819efd0b)
Location: include/linux/netdevice.h:5023
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac58f4)
Location: include/linux/netdevice.h:5023
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff8191db02)
Location: include/linux/netdevice.h:5071
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81a786cb)
Location: include/linux/netdevice.h:5071
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81a89854)
Location: include/linux/netdevice.h:5071
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81aa1140)
Location: include/linux/netdevice.h:5071
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84104)
Location: include/linux/netdevice.h:5071
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81a751cc)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81bebfe4)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81bfee5d)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81c18fe6)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81d148dc)
Location: include/linux/netdevice.h:4892
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81c06b5b)
Location: include/linux/netdevice.h:4936
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81d989b4)
Location: include/linux/netdevice.h:4936
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81dad89e)
Location: include/linux/netdevice.h:4936
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81dc9fbc)
Location: include/linux/netdevice.h:4936
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81edaa1c)
Location: include/linux/netdevice.h:4936
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7611)
Location: include/linux/netdevice.h:4936
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6576)
Location: include/linux/netdevice.h:4936
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
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
In drivers/net/xen-netfront.c (ffffffff81c6c25e)
Location: include/linux/netdevice.h:4984
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81e0817e)
Location: include/linux/netdevice.h:4984
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81e1d7ab)
Location: include/linux/netdevice.h:4984
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81e3ab38)
Location: include/linux/netdevice.h:4984
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gso.c (ffffffff81e7d714)
Location: include/linux/netdevice.h:4984
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39b03)
Location: include/linux/netdevice.h:4984
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81f462b7)
Location: include/linux/netdevice.h:4984
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81d20c0e)
Location: include/linux/netdevice.h:5060
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81ec4bd4)
Location: include/linux/netdevice.h:5060
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81edaeaf)
Location: include/linux/netdevice.h:5060
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81ef8edc)
Location: include/linux/netdevice.h:5060
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/gso.c (ffffffff81f3e691)
Location: include/linux/netdevice.h:5060
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffbf3)
Location: include/linux/netdevice.h:5060
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8200c3f7)
Location: include/linux/netdevice.h:5060
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In drivers/net/xen-netfront.c (ffff800010a09474)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffff800010ba95d4)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffff800010bbacc0)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffff800010bd0d94)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffff800010c9529c)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/sock.c (c0cca5f0)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (c0cd7204)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c0ceb9d0)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (c0da39b4)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/sock.c (c000000000c7e5f0)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (c000000000c93a2c)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c000000000caee44)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (c000000000da6250)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/sock.c (ffffffe00073c956)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffe000749e86)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffe00075b3f2)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f44bc)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff81792554)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff818b1949)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff818c0025)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818d2db6)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819810d2)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/sock.c (ffffffff8186b899)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81879f65)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8188cc46)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff8193ab92)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817c27b4)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff81902949)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81911025)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81923db6)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb8a2)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In drivers/net/xen-netfront.c (ffffffff817dca74)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/sock.c (ffffffff819238e9)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/core/skbuff.c (ffffffff81932185)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81945226)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__skb_gso_segment
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5752)
Location: include/linux/netdevice.h:4504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
</details>
</li>
</ul>

## Differences
