# Function: <code>sock_owned_by_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv4/route.c (ffffffff817c3197)
Location: include/net/sock.h:1448
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec073)
Location: include/net/sock.h:1448
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/sock.h:1448
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860c1b)
Location: include/net/sock.h:1448
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/sock.h:1504
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/sock.h:1504
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
In net/socket.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/sock.h:1507
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
In net/core/sock.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/sock.h:1511
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/sock.h:1511
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
In net/core/sock.c (ffffffff81875115)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8187dbca)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff818e67d2)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f56eb)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818fb34e)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8190606e)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff8190b82e)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cac7)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191251b)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e28)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81974cf0)
Location: include/net/sock.h:1524
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81995511)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff818959e5)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8189e79a)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81913626)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a2b)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81934210)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81939afe)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ae07)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940cf2)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819415e5)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff819aa938)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbdf3)
Location: include/net/sock.h:1563
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff818dff01)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff818e9018)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81975c76)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985437)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81997e90)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff8199ddcf)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f187)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a52d0)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5be1)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81a17d92)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a8eb)
Location: include/net/sock.h:1573
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff819120b1)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8191b178)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff819ac686)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc4c)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff819cea20)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff819d488f)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5d37)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbfc6)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc9a1)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81a4e9e2)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7148e)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff819e4061)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff819ededb)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81a96b6e)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6464)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81ababa0)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81ac120f)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2210)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac9109)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a71)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81b46312)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6ad97)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81bac650)
Location: include/net/sock.h:1632
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
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
In net/core/sock.c (ffffffff819e7b51)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff819edb7b)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81aa0c46)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0ab4)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5fe8)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81accc7f)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdc40)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad50a9)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad59c1)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81b54e51)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7982a)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81bc0ab1)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81bc342b)
Location: include/net/sock.h:1650
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_error_report
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
In net/core/sock.c (ffffffff819cdb21)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff819d5a5b)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81a8bb76)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bb64)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81ab11ed)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7e3f)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8fb0)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac012b)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a20)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81b428e1)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b68344)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81bb0aa0)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81bb375b)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_set_connected
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
In net/core/sock.c (ffffffff81a7d331)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81a8568b)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81b46b06)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57235)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81b6e04b)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81b7500f)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81b763b0)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dd9b)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e3e0)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81c0803e)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c30044)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81c7eb60)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81c81e8b)
Location: include/net/sock.h:1706
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81c83c07)
Location: include/net/sock.h:1706
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
In net/core/sock.c (ffffffff81bf0961)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81bf82ed)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81cd3ba2)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce51bd)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81cfd4a8)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81d047de)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05b80)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0ddae)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e362)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81da2d67)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd3f7)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81e2430d)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81e27da2)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81e29d9c)
Location: include/net/sock.h:1795
Inline: True
```
```
In net/mptcp/pm.c (ffffffff81e2d360)
Location: include/net/sock.h:1795
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
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
In net/core/sock.c (ffffffff81d9cf21)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81da714d)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81e93dd2)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea83ad)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81ec2068)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81ec978e)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecacd0)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed375c)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3e12)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81f72157)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e4df)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81ffbded)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81fffcd2)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff82001eac)
Location: include/net/sock.h:1816
Inline: True
```
```
In net/mptcp/pm.c (ffffffff82005780)
Location: include/net/sock.h:1816
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
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
In net/core/sock.c (ffffffff81e0b771)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81e191fd)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81ef2572)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06c2d)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81f205d1)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81f282de)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81f297f9)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f32468)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32e06)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81fd2245)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffef83)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff820781bd)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff8207bcef)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff8207dabc)
Location: include/net/sock.h:1807
Inline: True
```
```
In net/mptcp/pm.c (ffffffff82081970)
Location: include/net/sock.h:1807
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
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
In net/core/sock.c (ffffffff81ec8161)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81ed668d)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81fb6690)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcaf4d)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4c3a)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81fecbce)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee379)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff8431)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8f56)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff8209f7d5)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdcc0)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff8214d413)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff82151046)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff82152d7c)
Location: include/net/sock.h:1782
Inline: True
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
In net/core/sock.c (ffff800010baadbc)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffff800010bb5608)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffff800010c5c824)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6dac0)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffff800010c813fc)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffff800010c873d0)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffff800010c88764)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f270)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f908)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffff800010d133e0)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39894)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (c0cc8180)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (c0cd26b4)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (c0d6bed4)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (c0d7bff0)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (c0d906a4)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (c0d967e0)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c0d97bd4)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9e1b0)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c0d9e9c8)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (c0e184f8)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (c0e3c3a4)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (c000000000c7f104)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (c000000000c8c76c)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (c000000000d5ec54)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72ed8)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (c000000000d8c3ac)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (c000000000d93e70)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c000000000d95b00)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9def4)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e920)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (c000000000e3ed6c)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cf74)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffe00073d0ae)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffe0007455fe)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffe0007c56b0)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2db2)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffe0007e3332)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8848)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9b6c)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef3f8)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc2a)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffe000858b4c)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876b1e)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff818b20b1)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff818bb178)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff8194c4f6)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195babc)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff8196e890)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff819746ff)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81975ba7)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197be36)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c811)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff819ee072)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10b1e)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff8186c001)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff818750b8)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff81905fe6)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819155ac)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff81928380)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff8192e1cf)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f667)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819358f6)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819362d1)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff819aae32)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd8de)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff819030b1)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8190c178)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff819b6cc6)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c628c)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff819d9060)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff819deecf)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0377)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e6606)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6fe1)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81a58af2)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b59e)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/sock.c (ffffffff81924031)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8192d2a8)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
```
```
In net/ipv4/route.c (ffffffff819c0544)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfd72)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_input.c (ffffffff819e2ccb)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff819e8b6f)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea037)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f02c6)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0cb1)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv6/route.c (ffffffff81a64ccd)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87dde)
Location: include/net/sock.h:1583
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
</ul>

## Differences
