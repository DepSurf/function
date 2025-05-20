# Function: <code>tcp_send_head</code>

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
In net/ipv4/tcp.c (ffffffff8176942e)
Location: include/net/tcp.h:1490
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817721cd)
Location: include/net/tcp.h:1490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff817759a2)
Location: include/net/tcp.h:1490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_may_send_now
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a6f2)
Location: include/net/tcp.h:1490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:1490
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
In net/ipv4/tcp.c (ffffffff817d5e3a)
Location: include/net/tcp.h:1503
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817ddb8a)
Location: include/net/tcp.h:1503
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff817e6864)
Location: include/net/tcp.h:1503
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_may_send_now
```
```
In net/ipv4/tcp_timer.c (ffffffff817e79ee)
Location: include/net/tcp.h:1503
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:1503
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
In net/ipv4/tcp.c (ffffffff81805e4f)
Location: include/net/tcp.h:1575
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8180ddbf)
Location: include/net/tcp.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81816fa4)
Location: include/net/tcp.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_may_send_now
```
```
In net/ipv4/tcp_timer.c (ffffffff818181b1)
Location: include/net/tcp.h:1575
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:1575
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
In net/ipv4/tcp.c (ffffffff81826172)
Location: include/net/tcp.h:1626
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8182e2c7)
Location: include/net/tcp.h:1626
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81837414)
Location: include/net/tcp.h:1626
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_may_send_now
```
```
In net/ipv4/tcp_timer.c (ffffffff818386b9)
Location: include/net/tcp.h:1626
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:1626
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
In net/ipv4/tcp.c (ffffffff818a4caf)
Location: include/net/tcp.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff818b0200)
Location: include/net/tcp.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff818b6ac4)
Location: include/net/tcp.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7dd8)
Location: include/net/tcp.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff818fa55d)
Location: include/net/tcp.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819056ca)
Location: include/net/tcp.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8190c300)
Location: include/net/tcp.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d79d)
Location: include/net/tcp.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff81928494)
Location: include/net/tcp.h:1690
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81933870)
Location: include/net/tcp.h:1690
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8193a5e0)
Location: include/net/tcp.h:1690
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8193bb8b)
Location: include/net/tcp.h:1690
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff8198b863)
Location: include/net/tcp.h:1730
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819978eb)
Location: include/net/tcp.h:1730
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8199e92a)
Location: include/net/tcp.h:1730
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ff3a)
Location: include/net/tcp.h:1730
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff819c20c8)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819ce47b)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819d543a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff819d6afa)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff81aa8e40)
Location: include/net/tcp.h:1781
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81aba564)
Location: include/net/tcp.h:1781
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1d7a)
Location: include/net/tcp.h:1781
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac360a)
Location: include/net/tcp.h:1781
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff81ab32e0)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ac59a4)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_probe
```
```
In net/ipv4/tcp_output.c (ffffffff81acd7ea)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81acf07c)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bba31a)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/ipv4/tcp.c (ffffffff81a9e540)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0bb0)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81ab89aa)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81aba1bc)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81ba96cc)
Location: include/net/tcp.h:1799
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/ipv4/tcp.c (ffffffff81b5a0f0)
Location: include/net/tcp.h:1792
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d9f4)
Location: include/net/tcp.h:1792
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81b75bca)
Location: include/net/tcp.h:1792
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81b761d5)
Location: include/net/tcp.h:1792
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81c78d36)
Location: include/net/tcp.h:1792
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/ipv4/tcp.c (ffffffff81ce87ce)
Location: include/net/tcp.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81cfce70)
Location: include/net/tcp.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81d054ca)
Location: include/net/tcp.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06f01)
Location: include/net/tcp.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81e1f444)
Location: include/net/tcp.h:1848
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
In net/ipv4/tcp.c (ffffffff81eb2df6)
Location: include/net/tcp.h:1868
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1a30)
Location: include/net/tcp.h:1868
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81eca5ca)
Location: include/net/tcp.h:1868
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecadd5)
Location: include/net/tcp.h:1868
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff5f9c)
Location: include/net/tcp.h:1868
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
In net/ipv4/tcp.c (ffffffff81f118e1)
Location: include/net/tcp.h:1881
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81f2000d)
Location: include/net/tcp.h:1881
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81f29111)
Location: include/net/tcp.h:1881
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29915)
Location: include/net/tcp.h:1881
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff820720ca)
Location: include/net/tcp.h:1881
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
In net/ipv4/tcp.c (ffffffff81fce85e)
Location: include/net/tcp.h:1983
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81fe46ed)
Location: include/net/tcp.h:1983
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81fedc51)
Location: include/net/tcp.h:1983
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee485)
Location: include/net/tcp.h:1983
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff821461c8)
Location: include/net/tcp.h:1983
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
In net/ipv4/tcp.c (ffff800010c74a88)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffff800010c80eec)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffff800010c880c8)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffff800010c89984)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (c0d83150)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c0d9014c)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (c0d973b8)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (c0d98ad4)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (c000000000d7c3c4)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c000000000d8bd78)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (c000000000d94f24)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (c000000000d96e44)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffe0007d7e90)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2e50)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffe0007e934a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea86c)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff81961f38)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8196e2eb)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819752aa)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff8197696a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff8191ba28)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81927ddb)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8192ed6a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff8193042a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff819cc708)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819d8abb)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819dfa7a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff819e113a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp.c (ffffffff819d6298)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819e270b)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819e972a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff819eae0a)
Location: include/net/tcp.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
</details>
</li>
</ul>

## Differences
