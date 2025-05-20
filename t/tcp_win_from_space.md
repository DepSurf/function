# Function: <code>tcp_win_from_space</code>

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
In net/ipv4/tcp_input.c (ffffffff8176b4a8)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81775cb1)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177fd25)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff817ab7dc)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff817ff69a)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff817da48a)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff817e4ac6)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed245)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff818192d2)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff8186f016)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff81808e1d)
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81814f16)
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181db55)
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff8184ab50)
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff818a1f81)
Location: include/net/tcp.h:1266
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff818290ff)
Location: include/net/tcp.h:1303
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818350cb)
Location: include/net/tcp.h:1303
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d9af)
Location: include/net/tcp.h:1303
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff8186e55e)
Location: include/net/tcp.h:1303
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff818c85b2)
Location: include/net/tcp.h:1303
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff818ae10c)
Location: include/net/tcp.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b455d)
Location: include/net/tcp.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bda6f)
Location: include/net/tcp.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff818eeeed)
Location: include/net/tcp.h:1284
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff8194bb6b)
Location: include/net/tcp.h:1284
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff818f62f3)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff819037c6)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81909b77)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913908)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81945833)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819a4e41)
Location: include/net/tcp.h:1301
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff81923ea3)
Location: include/net/tcp.h:1359
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81931966)
Location: include/net/tcp.h:1359
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81937e23)
Location: include/net/tcp.h:1359
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819420b8)
Location: include/net/tcp.h:1359
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81975bb5)
Location: include/net/tcp.h:1359
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819db931)
Location: include/net/tcp.h:1359
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff81986673)
Location: include/net/tcp.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff8199507d)
Location: include/net/tcp.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8199958d)
Location: include/net/tcp.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a66b8)
Location: include/net/tcp.h:1361
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff819df70a)
Location: include/net/tcp.h:1361
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a4a5c9)
Location: include/net/tcp.h:1361
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff819bcde3)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff819cbbcd)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819cff88)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcade)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81a16771)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a8119d)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff81aa7ca3)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1dc1)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81abcfd7)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca5f9)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81b07735)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b7be34)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff81bafa24)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp.c (ffffffff81ab2213)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81abcd81)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ac8739)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad6569)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81b15b09)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b8ae81)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/protocol.c (ffffffff81bbde10)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/subflow.c (ffffffff81bc32f4)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81bc4add)
Location: include/net/tcp.h:1403
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
In net/ipv4/tcp.c (ffffffff81a9d4a3)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81ab00b6)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ab346d)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac15d9)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81b03917)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b79ce4)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/protocol.c (ffffffff81bae003)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/subflow.c (ffffffff81bb3624)
Location: include/net/tcp.h:1395
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81bb5167)
Location: include/net/tcp.h:1395
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
In net/ipv4/tcp.c (ffffffff81b59376)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81b6ce98)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81b7033b)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f03f)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81bc5bae)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81c44995)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/protocol.c (ffffffff81c7b282)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/subflow.c (ffffffff81c81d41)
Location: include/net/tcp.h:1388
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81c839b4)
Location: include/net/tcp.h:1388
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
In net/ipv4/tcp.c (ffffffff81ce7622)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc2fc)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81cff8c4)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e999)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81d5ae9e)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81de399a)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/protocol.c (ffffffff81e202cb)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/subflow.c (ffffffff81e278d1)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff81e299bf)
Location: include/net/tcp.h:1420
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
In net/ipv4/tcp.c (ffffffff81eaaea2)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0e8c)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ec4964)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4479)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81f2530e)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81fb601a)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/protocol.c (ffffffff81ff77a4)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/subflow.c (ffffffff81fff7a1)
Location: include/net/tcp.h:1436
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff82001aaf)
Location: include/net/tcp.h:1436
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
In net/ipv4/tcp.c (ffffffff81f095b2)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f3fc)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f232cd)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33499)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81f84e9f)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff82016733)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/protocol.c (ffffffff82073c8f)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
```
In net/mptcp/subflow.c (ffffffff8207b871)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff8207df6f)
Location: include/net/tcp.h:1434
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_dss
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
In net/ipv4/tcp.c (ffffffff81fd4f8e)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_window_clamp
```
```
In net/ipv4/tcp_input.c (ffffffff81fe3ad4)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fe76b7)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9611)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff8204b611)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff820e575b)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffff800010c6f084)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffff800010c7e834)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffff800010c8262c)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f6e0)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffff800010cd23f0)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffff800010d4c920)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (c0d7dc60)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (c0d8d820)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (c0d91cb4)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (c0d9f46c)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (c0ddc2b4)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (c0e4dc18)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (c000000000d753b0)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (c000000000d88b68)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (c000000000d8e1c0)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9eba0)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (c000000000df088c)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (c000000000e830a4)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffe0007d3dfc)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0b54)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4942)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efd86)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffe000823768)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffe000885688)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff8195cc53)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff8196ba3d)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8196fdf8)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c94e)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff819b5e01)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a2082d)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff81916743)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff8192552d)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819298c8)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8193640e)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81972bf1)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819dd5ed)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff819c7423)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff819d620d)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819da5c8)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e711e)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81a206a1)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a8b2ad)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp.c (ffffffff819d0f73)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
```
In net/ipv4/tcp_input.c (ffffffff819dfe2d)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819e424a)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0dee)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81a2bba1)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a97ecf)
Location: include/net/tcp.h:1382
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
</ul>

## Differences
