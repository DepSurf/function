# Function: <code>tcp_write_queue_empty</code>

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
In net/ipv4/tcp_timer.c (ffffffff8177a033)
Location: include/net/tcp.h:1567
Inline: True
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
In net/ipv4/tcp_timer.c (ffffffff817e7246)
Location: include/net/tcp.h:1582
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_output.c (ffffffff81813045)
Location: include/net/tcp.h:1657
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff818179ca)
Location: include/net/tcp.h:1657
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_output.c (ffffffff8183327c)
Location: include/net/tcp.h:1708
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81837dfa)
Location: include/net/tcp.h:1708
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1613
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818ad2ba)
Location: include/net/tcp.h:1613
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff818b6c17)
Location: include/net/tcp.h:1613
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6e23)
Location: include/net/tcp.h:1613
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff818fa6a2)
Location: include/net/tcp.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81902a66)
Location: include/net/tcp.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8190c47b)
Location: include/net/tcp.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c6aa)
Location: include/net/tcp.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff819285d9)
Location: include/net/tcp.h:1701
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81930db0)
Location: include/net/tcp.h:1701
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8193a75b)
Location: include/net/tcp.h:1701
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8193a9d4)
Location: include/net/tcp.h:1701
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff8198b556)
Location: include/net/tcp.h:1741
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81994410)
Location: include/net/tcp.h:1741
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8199eaaf)
Location: include/net/tcp.h:1741
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ed84)
Location: include/net/tcp.h:1741
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff819c1d9b)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819caf60)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819d55bf)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5824)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81aad86a)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ab75db)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1eff)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac29f6)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff81bacc07)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
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
In net/ipv4/tcp.c (ffffffff81ab4c4e)
Location: include/net/tcp.h:1813
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81ac2895)
Location: include/net/tcp.h:1813
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81acd96d)
Location: include/net/tcp.h:1813
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace426)
Location: include/net/tcp.h:1813
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff81bc0476)
Location: include/net/tcp.h:1813
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
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
In net/ipv4/tcp.c (ffffffff81a9fd68)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81aada32)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8b2d)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab95b6)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff81bad5e9)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
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
In net/ipv4/tcp.c (ffffffff81b5bb21)
Location: include/net/tcp.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81b6af26)
Location: include/net/tcp.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81b75d4d)
Location: include/net/tcp.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81b769f2)
Location: include/net/tcp.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff81c7aa51)
Location: include/net/tcp.h:1810
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b140)
Location: include/net/tcp.h:1810
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81cead60)
Location: include/net/tcp.h:1866
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81cf9b3f)
Location: include/net/tcp.h:1866
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81d0566b)
Location: include/net/tcp.h:1866
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06214)
Location: include/net/tcp.h:1866
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff81e1fa53)
Location: include/net/tcp.h:1866
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff81e315bb)
Location: include/net/tcp.h:1866
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81eaebf4)
Location: include/net/tcp.h:1886
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81ebe64f)
Location: include/net/tcp.h:1886
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81eca77b)
Location: include/net/tcp.h:1886
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb582)
Location: include/net/tcp.h:1886
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff81ff6493)
Location: include/net/tcp.h:1886
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff82009bcb)
Location: include/net/tcp.h:1886
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81f0cca8)
Location: include/net/tcp.h:1899
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f1caef)
Location: include/net/tcp.h:1899
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81f292bb)
Location: include/net/tcp.h:1899
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a0cc)
Location: include/net/tcp.h:1899
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff8207266f)
Location: include/net/tcp.h:1899
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff82085ed6)
Location: include/net/tcp.h:1899
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81fd0da0)
Location: include/net/tcp.h:2001
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81fe065b)
Location: include/net/tcp.h:2001
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81feddfb)
Location: include/net/tcp.h:2001
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
```
```
In net/ipv4/tcp_timer.c (ffffffff81feec3c)
Location: include/net/tcp.h:2001
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/mptcp/protocol.c (ffffffff82149b51)
Location: include/net/tcp.h:2001
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_retrans
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b086)
Location: include/net/tcp.h:2001
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffff800010c74b04)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffff800010c7d8a0)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffff800010c8826c)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffff800010c889c0)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (c0d831d8)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c0d8caa4)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c0d97544)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (c0d977a8)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (c000000000d7c044)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c000000000d87720)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c000000000d95180)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (c000000000d95498)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffe0007d7f74)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffe0007e00a6)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffe0007e94aa)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9702)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81961c0b)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8196add0)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8197542f)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81975694)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff8191b6fb)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819248c0)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8192eeef)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f154)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff819cc3db)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819d55a0)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819dfbff)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfe64)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff819d5f6b)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819df180)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819e98af)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9b24)
Location: include/net/tcp.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
</details>
</li>
</ul>

## Differences
