# Function: <code>skb_can_coalesce</code>

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
In drivers/net/virtio_net.c (ffffffff815f338b)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In net/core/skbuff.c (ffffffff8170a977)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff8175d571)
Location: include/linux/skbuff.h:2652
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817691ea)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c5c22)
Location: include/linux/skbuff.h:2652
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
In drivers/net/virtio_net.c (ffffffff816532a0)
Location: include/linux/skbuff.h:2795
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In net/core/skbuff.c (ffffffff81772213)
Location: include/linux/skbuff.h:2795
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff817c8a1e)
Location: include/linux/skbuff.h:2795
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6200)
Location: include/linux/skbuff.h:2795
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81832d23)
Location: include/linux/skbuff.h:2795
Inline: True
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
In net/core/skbuff.c (ffffffff8179f313)
Location: include/linux/skbuff.h:2833
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff817f8609)
Location: include/linux/skbuff.h:2833
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806225)
Location: include/linux/skbuff.h:2833
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff818647b7)
Location: include/linux/skbuff.h:2833
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
In net/core/skbuff.c (ffffffff817b918c)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81818bb8)
Location: include/linux/skbuff.h:2899
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818266dc)
Location: include/linux/skbuff.h:2899
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81887fe4)
Location: include/linux/skbuff.h:2899
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
In net/core/skbuff.c (ffffffff81831fe2)
Location: include/linux/skbuff.h:2996
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81898bd5)
Location: include/linux/skbuff.h:2996
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a480d)
Location: include/linux/skbuff.h:2996
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8190a3ec)
Location: include/linux/skbuff.h:2996
Inline: True
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
In net/core/skbuff.c (ffffffff8187c17a)
Location: include/linux/skbuff.h:3008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff818eccdd)
Location: include/linux/skbuff.h:3008
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fa601)
Location: include/linux/skbuff.h:3008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819617eb)
Location: include/linux/skbuff.h:3008
Inline: True
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
In net/core/skbuff.c (ffffffff8189cc1a)
Location: include/linux/skbuff.h:3084
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff8191a53d)
Location: include/linux/skbuff.h:3084
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8192853b)
Location: include/linux/skbuff.h:3084
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81996148)
Location: include/linux/skbuff.h:3084
Inline: True
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
In net/core/skbuff.c (ffffffff818e77de)
Location: include/linux/skbuff.h:3171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff8197c757)
Location: include/linux/skbuff.h:3171
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198b49e)
Location: include/linux/skbuff.h:3171
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a025c3)
Location: include/linux/skbuff.h:3171
Inline: True
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
In net/core/skbuff.c (ffffffff81919bbe)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff819b30f7)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c1cf2)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a3919b)
Location: include/linux/skbuff.h:3236
Inline: True
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
In net/core/skbuff.c (ffffffff819ec651)
Location: include/linux/skbuff.h:3260
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81a9d0f0)
Location: include/linux/skbuff.h:3260
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aad697)
Location: include/linux/skbuff.h:3260
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e8d0)
Location: include/linux/skbuff.h:3260
Inline: True
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
In net/core/skbuff.c (ffffffff819ec101)
Location: include/linux/skbuff.h:3286
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81aa6fb0)
Location: include/linux/skbuff.h:3286
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4a0e)
Location: include/linux/skbuff.h:3286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d320)
Location: include/linux/skbuff.h:3286
Inline: True
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
In net/core/skbuff.c (ffffffff819d25f7)
Location: include/linux/skbuff.h:3350
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81a9212f)
Location: include/linux/skbuff.h:3350
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9fbbe)
Location: include/linux/skbuff.h:3350
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a7a3)
Location: include/linux/skbuff.h:3350
Inline: True
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
In net/core/skbuff.c (ffffffff81a824c7)
Location: include/linux/skbuff.h:3387
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81b4d53f)
Location: include/linux/skbuff.h:3387
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5b977)
Location: include/linux/skbuff.h:3387
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81bf08a5)
Location: include/linux/skbuff.h:3387
Inline: True
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
In net/core/skbuff.c (ffffffff81bf6e40)
Location: include/linux/skbuff.h:3756
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81cdad0d)
Location: include/linux/skbuff.h:3756
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81cea8eb)
Location: include/linux/skbuff.h:3756
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81d88f69)
Location: include/linux/skbuff.h:3756
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1f763)
Location: include/linux/skbuff.h:3756
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skbuff.c (ffffffff81da5bcb)
Location: include/linux/skbuff.h:3652
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81e9b52f)
Location: include/linux/skbuff.h:3652
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eae8d4)
Location: include/linux/skbuff.h:3652
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81f56d90)
Location: include/linux/skbuff.h:3652
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff62ad)
Location: include/linux/skbuff.h:3652
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/virtio_net.c (ffffffff81c559d1)
Location: include/linux/skbuff.h:3686
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable
```
```
In net/core/skbuff.c (ffffffff81e14846)
Location: include/linux/skbuff.h:3686
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81efa0eb)
Location: include/linux/skbuff.h:3686
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0cb5d)
Location: include/linux/skbuff.h:3686
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81fb67e4)
Location: include/linux/skbuff.h:3686
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff820723a7)
Location: include/linux/skbuff.h:3686
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/virtio_net.c (ffffffff81d0c081)
Location: include/linux/skbuff.h:3714
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable
```
```
In net/core/skbuff.c (ffffffff81ed1e46)
Location: include/linux/skbuff.h:3714
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81fbe019)
Location: include/linux/skbuff.h:3714
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd0c4d)
Location: include/linux/skbuff.h:3714
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff820840cf)
Location: include/linux/skbuff.h:3714
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff821464fb)
Location: include/linux/skbuff.h:3714
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skbuff.c (ffff800010bb41e0)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffff800010c62ac8)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c74bc8)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffff800010cf9124)
Location: include/linux/skbuff.h:3236
Inline: True
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
In net/core/skbuff.c (c0cd1b6c)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (c0d7348c)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d83344)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c0e00910)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
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
In net/core/skbuff.c (c000000000c8a7a0)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (c000000000d676f0)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7bf64)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c000000000e20d10)
Location: include/linux/skbuff.h:3236
Inline: True
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
In net/core/skbuff.c (ffffffe000744892)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffe0007cb4d8)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d7eec)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffe000844f5c)
Location: include/linux/skbuff.h:3236
Inline: True
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
In net/core/skbuff.c (ffffffff818b9bbe)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff81952f67)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81961b62)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819d882b)
Location: include/linux/skbuff.h:3236
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
In net/core/skbuff.c (ffffffff81873b0e)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff8190ca57)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191b652)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff819955eb)
Location: include/linux/skbuff.h:3236
Inline: True
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
In net/core/skbuff.c (ffffffff8190abbe)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff819bd737)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819cc332)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a432ab)
Location: include/linux/skbuff.h:3236
Inline: True
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
In net/core/skbuff.c (ffffffff8192bcbe)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff819c7047)
Location: include/linux/skbuff.h:3236
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d5ec2)
Location: include/linux/skbuff.h:3236
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81a4ef4b)
Location: include/linux/skbuff.h:3236
Inline: True
```
</details>
</li>
</ul>

## Differences
