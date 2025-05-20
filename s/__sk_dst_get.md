# Function: <code>__sk_dst_get</code>

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
In net/core/sock.c (ffffffff81700760)
Location: include/net/sock.h:1710
Inline: True
Inline callers:
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff8176cb06)
Location: include/net/sock.h:1710
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81775117)
Location: include/net/sock.h:1710
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a096)
Location: include/net/sock.h:1710
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d26b)
Location: include/net/sock.h:1710
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781f5b)
Location: include/net/sock.h:1710
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/datagram.c (ffffffff81783c44)
Location: include/net/sock.h:1710
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc27b)
Location: include/net/sock.h:1710
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
In net/core/sock.c (ffffffff8176b3e2)
Location: include/net/sock.h:1671
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff817e0d28)
Location: include/net/sock.h:1671
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff817e49b2)
Location: include/net/sock.h:1671
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff817e72ad)
Location: include/net/sock.h:1671
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea915)
Location: include/net/sock.h:1671
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817efa65)
Location: include/net/sock.h:1671
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/datagram.c (ffffffff817f11f6)
Location: include/net/sock.h:1671
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81845632)
Location: include/net/sock.h:1671
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184a1c2)
Location: include/net/sock.h:1671
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81863753)
Location: include/net/sock.h:1671
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
In net/core/sock.c (ffffffff817984b5)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff8181112a)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81814e02)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81817c9e)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181aeb5)
Location: include/net/sock.h:1733
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81820475)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/datagram.c (ffffffff81822288)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff818773c9)
Location: include/net/sock.h:1733
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187c052)
Location: include/net/sock.h:1733
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81895d73)
Location: include/net/sock.h:1733
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
In net/core/sock.c (ffffffff817b604f)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81827eb8)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81834fea)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81838201)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b741)
Location: include/net/sock.h:1738
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81840995)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/datagram.c (ffffffff81842ef8)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff8189c6c9)
Location: include/net/sock.h:1738
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a1a1e)
Location: include/net/sock.h:1738
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff818bc303)
Location: include/net/sock.h:1738
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
In net/core/sock.c (ffffffff8182e0ac)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff818a9eb6)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff818b4473)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7912)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff818c0105)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0caa)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff818c2858)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff8191c729)
Location: include/net/sock.h:1752
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81924394)
Location: include/net/sock.h:1752
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff8193f3e3)
Location: include/net/sock.h:1752
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
In net/core/sock.c (ffffffff8187896d)
Location: include/net/sock.h:1763
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff818fefd3)
Location: include/net/sock.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81909a7f)
Location: include/net/sock.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d3c6)
Location: include/net/sock.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915c55)
Location: include/net/sock.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8191678b)
Location: include/net/sock.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff819184b8)
Location: include/net/sock.h:1763
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81974c99)
Location: include/net/sock.h:1763
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197c84e)
Location: include/net/sock.h:1763
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819981f3)
Location: include/net/sock.h:1763
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
In net/core/sock.c (ffffffff8189940c)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff8192d313)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81937d2f)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b79b)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81944405)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944f2b)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff81946c38)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff819aa8dd)
Location: include/net/sock.h:1848
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b27ef)
Location: include/net/sock.h:1848
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819ceb83)
Location: include/net/sock.h:1848
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
In net/core/sock.c (ffffffff818e370c)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81996dba)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8199b795)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff8199fb54)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a89c5)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a955e)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff819ab2bb)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81a17d31)
Location: include/net/sock.h:1860
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a20f59)
Location: include/net/sock.h:1860
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a3d85c)
Location: include/net/sock.h:1860
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
In net/core/sock.c (ffffffff819158ec)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff819cd93a)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819d21bd)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff819d672b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df6a5)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e01fb)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff819e1f8b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81a4e981)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a579c9)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a744cc)
Location: include/net/sock.h:1870
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
In net/core/sock.c (ffffffff819e8a7c)
Location: include/net/sock.h:1919
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81ab9b0a)
Location: include/net/sock.h:1919
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81abe9c1)
Location: include/net/sock.h:1919
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac26ce)
Location: include/net/sock.h:1919
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81accb15)
Location: include/net/sock.h:1919
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd7eb)
Location: include/net/sock.h:1919
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81acf28b)
Location: include/net/sock.h:1919
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81b462b1)
Location: include/net/sock.h:1919
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4fc0f)
Location: include/net/sock.h:1919
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6e6dc)
Location: include/net/sock.h:1919
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
In net/core/sock.c (ffffffff819e8bd9)
Location: include/net/sock.h:1934
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81ac4f10)
Location: include/net/sock.h:1934
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81aca321)
Location: include/net/sock.h:1934
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace137)
Location: include/net/sock.h:1934
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad8b15)
Location: include/net/sock.h:1934
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad982b)
Location: include/net/sock.h:1934
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81adb28b)
Location: include/net/sock.h:1934
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81b54dee)
Location: include/net/sock.h:1934
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5ec95)
Location: include/net/sock.h:1934
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b7d18c)
Location: include/net/sock.h:1934
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
In net/core/sock.c (ffffffff819ced0f)
Location: include/net/sock.h:1951
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81ab014e)
Location: include/net/sock.h:1951
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ab58c4)
Location: include/net/sock.h:1951
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab92cf)
Location: include/net/sock.h:1951
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3b85)
Location: include/net/sock.h:1951
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4910)
Location: include/net/sock.h:1951
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81ac62eb)
Location: include/net/sock.h:1951
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81b4287e)
Location: include/net/sock.h:1951
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4d4e0)
Location: include/net/sock.h:1951
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6bd6c)
Location: include/net/sock.h:1951
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
In net/core/sock.c (ffffffff81a7e42c)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81b6cf3d)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81b72904)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76693)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b82245)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b83053)
Location: include/net/sock.h:1991
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81b84afb)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81c07fce)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c147f9)
Location: include/net/sock.h:1991
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81c33bf7)
Location: include/net/sock.h:1991
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
In net/core/sock.c (ffffffff81bf1f3e)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc402)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81d01ee9)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05ea8)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d12705)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d1364a)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff81d1537f)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81da2ce4)
Location: include/net/sock.h:2112
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0143)
Location: include/net/sock.h:2112
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81dd1477)
Location: include/net/sock.h:2112
Inline: True
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
In net/core/sock.c (ffffffff81d9f6ea)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0f92)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7110)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb230)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed8525)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed95ea)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff81edbb6f)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81f720d4)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f81d40)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/datagram.c (ffffffff81fa2a87)
Location: include/net/sock.h:2149
Inline: True
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
In net/core/sock.c (ffffffff81e0d662)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f502)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81f259c1)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2abfd)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f37635)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f386ca)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff81f3ac3f)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81fd21c4)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1ae7)
Location: include/net/sock.h:2137
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/datagram.c (ffffffff82003333)
Location: include/net/sock.h:2137
Inline: True
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
In net/core/sock.c (ffffffff81eca7f2)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff81fe3bbf)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81fed985)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_delack_max
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef81c)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd705)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe78a)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff82000d2f)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff8209f754)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820afa07)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/datagram.c (ffffffff820d2103)
Location: include/net/sock.h:2127
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
In net/core/sock.c (ffff800010bae9bc)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffff800010c804b0)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffff800010c84dac)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffff800010c8965c)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffff800010c93070)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93df4)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffff800010c95c38)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffff800010d13364)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1cbc8)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (ffff800010d3ceec)
Location: include/net/sock.h:1870
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
In net/core/sock.c (c0ccc1d8)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (c0d8f700)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (c0d93f38)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (c0d9869c)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (c0da1a38)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (c0da2660)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (c0da4394)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (c0e184a4)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (c0e218f8)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (c0e40158)
Location: include/net/sock.h:1870
Inline: True
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
In net/core/sock.c (c000000000c84798)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (c000000000d8b060)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c000000000d90a74)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (c000000000d96994)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (c000000000da33a8)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (c000000000da43c8)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (c000000000da73f4)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (c000000000e3ecdc)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4afa4)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (c000000000e70f74)
Location: include/net/sock.h:1870
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
In net/core/sock.c (ffffffe000740800)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffe0007e24e8)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffe0007e660e)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea4d8)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f279e)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f33b4)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffe0007f50dc)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffe000858b00)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000860296)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (ffffffe000879732)
Location: include/net/sock.h:1870
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
In net/core/sock.c (ffffffff818b58ec)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff8196d7aa)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8197202d)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff8197659b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f515)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8198006b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff81981dfb)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff819ee011)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7059)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a13b5c)
Location: include/net/sock.h:1870
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
In net/core/sock.c (ffffffff8186f83c)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff8192729a)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8192bafd)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff8193005b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938fd5)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939b2b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff8193b8bb)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff819aadd1)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b3e19)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819d091c)
Location: include/net/sock.h:1870
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
In net/core/sock.c (ffffffff819068ec)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff819d7f7a)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819dc7fd)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0d6b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9ce5)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea83b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff819ec5cb)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81a58a91)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a61ad9)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a7e5dc)
Location: include/net/sock.h:1870
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
In net/core/sock.c (ffffffff8192791e)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/tcp_input.c (ffffffff819e1bba)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819e647d)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_timer.c (ffffffff819eaa2b)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3ad5)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f46ab)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
```
In net/ipv4/datagram.c (ffffffff819f64b0)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv6/route.c (ffffffff81a64c68)
Location: include/net/sock.h:1870
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6df9e)
Location: include/net/sock.h:1870
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a8ae72)
Location: include/net/sock.h:1870
Inline: True
```
</details>
</li>
</ul>

## Differences
