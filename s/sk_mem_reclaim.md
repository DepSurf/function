# Function: <code>sk_mem_reclaim</code>

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
In net/core/sock.c (ffffffff817029c8)
Location: include/net/sock.h:1400
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff8170e1f2)
Location: include/net/sock.h:1400
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81768135)
Location: include/net/sock.h:1400
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b1a5)
Location: include/net/sock.h:1400
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_timer.c (ffffffff81779b4a)
Location: include/net/sock.h:1400
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c9a4)
Location: include/net/sock.h:1400
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/af_inet.c (ffffffff8179482d)
Location: include/net/sock.h:1400
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81769bf8)
Location: include/net/sock.h:1307
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff817758df)
Location: include/net/sock.h:1307
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d4a1b)
Location: include/net/sock.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff817d9b1a)
Location: include/net/sock.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6d1e)
Location: include/net/sock.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea2c9)
Location: include/net/sock.h:1307
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/af_inet.c (ffffffff8180217f)
Location: include/net/sock.h:1307
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81796b28)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff817a2b5f)
Location: include/net/sock.h:1363
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8180476f)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8180a4bc)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff8181745e)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818b06)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/af_inet.c (ffffffff8183310f)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff817b4f18)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff817c0d2d)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff818249e4)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8182ef41)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff818377fd)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818392e5)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/af_inet.c (ffffffff81854a7d)
Location: include/net/sock.h:1366
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff8182d348)
Location: include/net/sock.h:1370
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff8183a74d)
Location: include/net/sock.h:1370
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff818a66e7)
Location: include/net/sock.h:1370
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff818adf62)
Location: include/net/sock.h:1370
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6f42)
Location: include/net/sock.h:1370
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff818d491d)
Location: include/net/sock.h:1370
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81877129)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81884e8d)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff818fb788)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819035d3)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c71c)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff8192aadd)
Location: include/net/sock.h:1385
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff818978c9)
Location: include/net/sock.h:1423
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff818a58fd)
Location: include/net/sock.h:1423
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff819296d8)
Location: include/net/sock.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8193172e)
Location: include/net/sock.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ab70)
Location: include/net/sock.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81959ffd)
Location: include/net/sock.h:1423
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff818e1dda)
Location: include/net/sock.h:1426
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff818f0c21)
Location: include/net/sock.h:1426
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff8198c631)
Location: include/net/sock.h:1426
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81994e64)
Location: include/net/sock.h:1426
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ef17)
Location: include/net/sock.h:1426
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff819bec63)
Location: include/net/sock.h:1426
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81913faa)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81922b6d)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff819c2fa0)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819cb9b4)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff819d59b7)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff819f5893)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff819e5c5a)
Location: include/net/sock.h:1484
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff819f62ab)
Location: include/net/sock.h:1484
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff81aae5f6)
Location: include/net/sock.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ab281f)
Location: include/net/sock.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2c02)
Location: include/net/sock.h:1484
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81ae3be7)
Location: include/net/sock.h:1484
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff819e572a)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff819f5aeb)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff81ab8843)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81abdb5f)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace632)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81af0b07)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff819cb83a)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff819dbc93)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff81aa3b43)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81aa84c8)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab97c2)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81adc2bd)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81a7aeca)
Location: include/net/sock.h:1526
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81a8be19)
Location: include/net/sock.h:1526
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff81b5fcf3)
Location: include/net/sock.h:1526
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81b64738)
Location: include/net/sock.h:1526
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76bf7)
Location: include/net/sock.h:1526
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81b9b4dd)
Location: include/net/sock.h:1526
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81bf2183)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81c01712)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff81cee824)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81cf351d)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06438)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81d2d4e2)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81d9e513)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81db0aa4)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81dfeec6)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
```
```
In net/core/skmsg.c (ffffffff81e471d8)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/ipv4/tcp.c (ffffffff81eb18a7)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6b6d)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81eca103)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/af_inet.c (ffffffff81ef5352)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2640e)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81f483ca)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81ff517a)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
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
In net/core/sock.c (ffffffff81e0cd23)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81e20f64)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81e70996)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
```
```
In net/core/skmsg.c (ffffffff81ea2c6b)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/ipv4/tcp.c (ffffffff81f0ffb2)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f14f8d)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81f28c53)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/af_inet.c (ffffffff81f54c32)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8608f)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f80)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff82071976)
Location: include/net/sock.h:1653
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
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
In net/core/sock.c (ffffffff81ec96b3)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81edee39)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/filter.c (ffffffff81f30026)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
```
```
In net/core/skmsg.c (ffffffff81f64f9b)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/ipv4/tcp.c (ffffffff81fd41b2)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81fd94cd)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81fed6f3)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/af_inet.c (ffffffff8201aea2)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d66f)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff82075240)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff82145af6)
Location: include/net/sock.h:1628
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
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
In net/core/sock.c (ffff800010babccc)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffff800010bbd460)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffff800010c75d6c)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffff800010c7e5ac)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffff800010c88b90)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffff800010cab688)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (c0cca88c)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (c0cd98fc)
Location: include/net/sock.h:1436
Inline: True
```
```
In net/ipv4/tcp.c (c0d8443c)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d8d5ec)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (c0d97894)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (c0db8500)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (c000000000c82280)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (c000000000c96b3c)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (c000000000d7d650)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d88860)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (c000000000d9574c)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (c000000000dc1e64)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffe00073f2e8)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffe00074bc4a)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffe0007d8f80)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0982)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e98c2)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffe000806328)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff818b3faa)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff818c2b6d)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff81962e10)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8196b824)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff81975827)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81995633)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff8186defa)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff8187caad)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff8191c900)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81925314)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f2e7)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff8194f0f3)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff81904faa)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81913b6d)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff819cd5e0)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819d5ff4)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfff7)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff819ffed3)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/sock.c (ffffffff8192607a)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/stream.c (ffffffff81934cfd)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/tcp.c (ffffffff819d7170)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819dfbf4)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9cb5)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/af_inet.c (ffffffff81a0a003)
Location: include/net/sock.h:1436
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
</details>
</li>
</ul>

## Differences
