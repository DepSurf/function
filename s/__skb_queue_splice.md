# Function: <code>__skb_queue_splice</code>

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
In net/core/dev.c (ffffffff8171b975)
Location: include/linux/skbuff.h:1492
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b39f8)
Location: include/linux/skbuff.h:1492
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
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
In net/core/dev.c (ffffffff81784212)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822f55)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In net/core/dev.c (ffffffff817b181a)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854898)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff81694c5a)
Location: include/linux/skbuff.h:1601
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/dev.c (ffffffff817cf296)
Location: include/linux/skbuff.h:1601
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff81845d20)
Location: include/linux/skbuff.h:1601
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187835c)
Location: include/linux/skbuff.h:1601
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
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
In drivers/net/tun.c (ffffffff816ff4ef)
Location: include/linux/skbuff.h:1683
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81848bf1)
Location: include/linux/skbuff.h:1683
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff818c574a)
Location: include/linux/skbuff.h:1683
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8c60)
Location: include/linux/skbuff.h:1683
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff818feb51)
Location: include/linux/skbuff.h:1683
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
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
In drivers/net/tun.c (ffffffff8173eec1)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81892c58)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff8191d081)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f681)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819556b1)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819584b2)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff817630bf)
Location: include/linux/skbuff.h:1772
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff818b6c38)
Location: include/linux/skbuff.h:1772
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff8194b631)
Location: include/linux/skbuff.h:1772
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982cbb)
Location: include/linux/skbuff.h:1772
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a2c1)
Location: include/linux/skbuff.h:1772
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d0b2)
Location: include/linux/skbuff.h:1772
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff817a0c2f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81903e4f)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/ipv4/udp.c (ffffffff819afd4a)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec9a8)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4531)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8922)
Location: include/linux/skbuff.h:1862
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff817c5bff)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81934faf)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81975c1f)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff819e69e0)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a239b8)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b1d1)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f582)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff8188e551)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
```
```
In net/core/dev.c (ffffffff81a09c57)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81a4ac5e)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81ad4171)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b158dc)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d84d)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22196)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b23201)
Location: include/linux/skbuff.h:1899
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
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
In drivers/net/tun.c (ffffffff8189cae1)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
```
```
In net/core/dev.c (ffffffff81a0b1fc)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81a5089e)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81ae06b1)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23d37)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c11d)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30b96)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b31bf1)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/mptcp/protocol.c (ffffffff81bc0930)
Location: include/linux/skbuff.h:1920
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In drivers/net/tun.c (ffffffff8187f701)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff819f37a8)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81a35680)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81acc69d)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11937)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19d7d)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e8c6)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b1f923)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/mptcp/protocol.c (ffffffff81bb06f0)
Location: include/linux/skbuff.h:1936
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In drivers/net/tun.c (ffffffff81910871)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81aa50f8)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81aeb250)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81b8af2d)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5427)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde31d)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3406)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81be45c3)
Location: include/linux/skbuff.h:1965
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/mptcp/protocol.c (ffffffff81c7e6a7)
Location: include/linux/skbuff.h:1965
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
In drivers/net/tun.c (ffffffff81a66f24)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81c1ba1f)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81c6dab5)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81d1ad13)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bc35)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75118)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a636)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81d7ba2a)
Location: include/linux/skbuff.h:2316
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/mptcp/protocol.c (ffffffff81e23a56)
Location: include/linux/skbuff.h:2316
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
In drivers/net/tun.c (ffffffff81bf2553)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81dcc9e0)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81e25725)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81ee22b3)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f36f75)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81f412e2)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47546)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81f48ada)
Location: include/linux/skbuff.h:2174
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/mptcp/protocol.c (ffffffff81ffb196)
Location: include/linux/skbuff.h:2174
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
In drivers/net/tun.c (ffffffff81c4b1eb)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81e3d540)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81e9ac65)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81f41db3)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f968fb)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0b72)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa7016)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81fa894a)
Location: include/linux/skbuff.h:2210
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/mptcp/protocol.c (ffffffff82077516)
Location: include/linux/skbuff.h:2210
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
In drivers/net/tun.c (ffffffff81cf8de5)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/skbuff.c (ffffffff81ed9428)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_purge_reason
```
```
In net/core/dev.c (ffffffff81efbde0)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81f5d3bd)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff82007c43)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063cfa)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ded2)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff820742c6)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff82075c3a)
Location: include/linux/skbuff.h:2217
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
```
```
In net/mptcp/protocol.c (ffffffff8214c546)
Location: include/linux/skbuff.h:2217
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
In drivers/net/tun.c (ffff8000109e1054)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffff800010bd3278)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffff800010c1c07c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffff800010c99e18)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0b44)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9a54)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffff800010cee744)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (c0ac4e4c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (c0cedf90)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (c0d33ec4)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (c0daa40c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (c0de9ec4)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (c0df1b4c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c0df657c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (c000000000aa219c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (c000000000cb1d08)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (c000000000d0cdbc)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (c000000000dab478)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (c000000000e02ea4)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (c000000000e0d38c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c000000000e133c0)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffe00062aa90)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffe00075d58a)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffe000796146)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffe0007f8fb0)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f7f8)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffe0008378f0)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b8aa)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff8178a6df)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff818d4f8f)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81915bef)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81986850)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3048)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca861)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819cec12)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff8176a02f)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff8188ee0d)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff818cf99f)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff81940310)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fe38)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81987651)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b9d2)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff817baa7f)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81925faf)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81966c1f)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff819f1020)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dac8)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a352e1)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39692)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
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
In drivers/net/tun.c (ffffffff817d2ecd)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In net/core/dev.c (ffffffff81947560)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/drop_monitor.c (ffffffff81988eaf)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/ipv4/udp.c (ffffffff819f940c)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39286)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40c01)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a450c2)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
</details>
</li>
</ul>

## Differences
