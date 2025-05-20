# Function: <code>skb_queue_splice_tail_init</code>

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
In net/core/dev.c (ffffffff8171b96a)
Location: include/linux/skbuff.h:1559
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81784207)
Location: include/linux/skbuff.h:1660
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
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
In net/core/dev.c (ffffffff817b180f)
Location: include/linux/skbuff.h:1675
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
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
In drivers/net/tun.c (ffffffff81694c31)
Location: include/linux/skbuff.h:1668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff817cf28f)
Location: include/linux/skbuff.h:1668
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff81845d03)
Location: include/linux/skbuff.h:1668
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff816ff4c0)
Location: include/linux/skbuff.h:1750
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81848be6)
Location: include/linux/skbuff.h:1750
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff818c5730)
Location: include/linux/skbuff.h:1750
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff8173eeb5)
Location: include/linux/skbuff.h:1761
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81892c54)
Location: include/linux/skbuff.h:1761
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff8191d06e)
Location: include/linux/skbuff.h:1761
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff817630b3)
Location: include/linux/skbuff.h:1839
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff818b6c34)
Location: include/linux/skbuff.h:1839
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff8194b61e)
Location: include/linux/skbuff.h:1839
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff817a0c23)
Location: include/linux/skbuff.h:1929
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81903e4b)
Location: include/linux/skbuff.h:1929
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff819afd35)
Location: include/linux/skbuff.h:1929
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff817c5bf3)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81934fab)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81975c12)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff819e69cb)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff8188e53a)
Location: include/linux/skbuff.h:1966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In net/core/dev.c (ffffffff81a09c4c)
Location: include/linux/skbuff.h:1966
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81a4ac50)
Location: include/linux/skbuff.h:1966
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81ad4154)
Location: include/linux/skbuff.h:1966
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff8189caca)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
```
```
In net/core/dev.c (ffffffff81a0b1f1)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81a50890)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81ae0694)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/mptcp/protocol.c (ffffffff81bc0923)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In drivers/net/tun.c (ffffffff8187f6ea)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff819f379d)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81a35672)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81acc680)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/mptcp/protocol.c (ffffffff81bb06e3)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In drivers/net/tun.c (ffffffff8191085a)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81aa50ed)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81aeb242)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81b8af10)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/mptcp/protocol.c (ffffffff81c7e69a)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In drivers/net/tun.c (ffffffff81a66f1f)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81c1ba12)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81c6daa7)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81d1acf9)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/mptcp/protocol.c (ffffffff81e23a43)
Location: include/linux/skbuff.h:2383
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In drivers/net/tun.c (ffffffff81bf254e)
Location: include/linux/skbuff.h:2241
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81dcc9d3)
Location: include/linux/skbuff.h:2241
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81e25717)
Location: include/linux/skbuff.h:2241
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81ee2299)
Location: include/linux/skbuff.h:2241
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/mptcp/protocol.c (ffffffff81ffb183)
Location: include/linux/skbuff.h:2241
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In drivers/net/tun.c (ffffffff81c4b1db)
Location: include/linux/skbuff.h:2277
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81e3d533)
Location: include/linux/skbuff.h:2277
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81e9ac57)
Location: include/linux/skbuff.h:2277
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81f41d99)
Location: include/linux/skbuff.h:2277
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/mptcp/protocol.c (ffffffff82077503)
Location: include/linux/skbuff.h:2277
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In drivers/net/tun.c (ffffffff81cf8de0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81efbdd3)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81f5d3b0)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff82007c29)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/mptcp/protocol.c (ffffffff8214c533)
Location: include/linux/skbuff.h:2284
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In drivers/net/tun.c (ffff8000109e104c)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffff800010bd326c)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffff800010c1c06c)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffff800010c99e04)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (c0ac4e40)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (c0cedf70)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (c0d33ebc)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (c0daa3fc)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (c000000000aa2194)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (c000000000cb1cf4)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (c000000000d0cdac)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (c000000000dab464)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffe00062aa76)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffe00075d57c)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffe000796134)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffe0007f8fa4)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff8178a6d3)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff818d4f8b)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81915be2)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff8198683b)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff8176a023)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff8188ee09)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff818cf992)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff819402fb)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff817baa73)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81925fab)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81966c12)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff819f100b)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
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
In drivers/net/tun.c (ffffffff817d2ebd)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff8194755c)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81988ea2)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff819f93f9)
Location: include/linux/skbuff.h:1943
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
</details>
</li>
</ul>

## Differences
