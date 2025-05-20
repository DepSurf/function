# Function: <code>tcp_call_bpf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182ca69)
Location: include/net/tcp.h:2044
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_output.c (ffffffff81834f89)
Location: include/net/tcp.h:2044
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183da51)
Location: include/net/tcp.h:2044
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81841135)
Location: include/net/tcp.h:2044
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp.c (ffffffff818a3c75)
Location: include/net/tcp.h:2009
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff818ab9a5)
Location: include/net/tcp.h:2009
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff818b4409)
Location: include/net/tcp.h:2009
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bdb17)
Location: include/net/tcp.h:2009
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp.c (ffffffff818f6436)
Location: include/net/tcp.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff81900d27)
Location: include/net/tcp.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81909a18)
Location: include/net/tcp.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d205)
Location: include/net/tcp.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913994)
Location: include/net/tcp.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
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
In net/ipv4/tcp.c (ffffffff8192401f)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff8192ef37)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81937cc8)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b570)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81942144)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff8195986b)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff81986ee7)
Location: include/net/tcp.h:2148
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819924d4)
Location: include/net/tcp.h:2148
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff8199b3f6)
Location: include/net/tcp.h:2148
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f987)
Location: include/net/tcp.h:2148
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a6747)
Location: include/net/tcp.h:2148
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff819be332)
Location: include/net/tcp.h:2148
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff819bd677)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819c8b8d)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819d1e16)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819d6539)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcb6e)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff819f4f62)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff81aa87c4)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81ab44f5)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81abed55)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac25d8)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca686)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81ae30f2)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff81ab2d34)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81abee06)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81aca6d1)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace077)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad40e6)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad65f6)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81aeffde)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b773f5)
Location: include/net/tcp.h:2253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp.c (ffffffff81a9df84)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81aab0de)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5552)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9212)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf183)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac1665)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81adb71e)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65efd)
Location: include/net/tcp.h:2258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp.c (ffffffff81b5ab58)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81b6715b)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81b72553)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81b7653f)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7ccbb)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f0cf)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81b9b69c)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2df7d)
Location: include/net/tcp.h:2250
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp.c (ffffffff81ce9330)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81cf63bc)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81d01c44)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05f9d)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cbf3)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0ea21)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81d2d343)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb8bd)
Location: include/net/tcp.h:2310
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:2358
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81ebadcc)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6dc4)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb2ee)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2633)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4501)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed898a)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/af_inet.c (ffffffff81ef47a3)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c9bd)
Location: include/net/tcp.h:2358
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81eabfb0-ffffffff81eac084: tcp_call_bpf.constprop.0.isra.0 (STB_LOCAL)
ffffffff820ae768-ffffffff820ae7a8: tcp_call_bpf.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:2383
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81f1925d)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81f25682)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29d83)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31313)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33519)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37a9a)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/af_inet.c (ffffffff81f5408a)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd40d)
Location: include/net/tcp.h:2383
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81f0a830-ffffffff81f0a904: tcp_call_bpf.constprop.0.isra.0 (STB_LOCAL)
ffffffff8212fc25-ffffffff8212fc57: tcp_call_bpf.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:2579
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81fddb0c)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9f42)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee8f3)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff72a3)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9681)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdb6a)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/af_inet.c (ffffffff8201b841)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_listen_sk
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cb181)
Location: include/net/tcp.h:2579
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81fce8b0-ffffffff81fce984: tcp_call_bpf.constprop.0.isra.0 (STB_LOCAL)
ffffffff82211911-ffffffff82211943: tcp_call_bpf.constprop.0.isra.0.cold (STB_LOCAL)
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
In net/ipv4/tcp.c (ffff800010c71940)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffff800010c7a7a0)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffff800010c84a04)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffff800010c892a0)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f758)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffff800010caadf0)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (c0d7e394)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (c0d88714)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (c0d93cac)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (c0d98314)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (c0d9f500)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (c0db7774)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (c000000000d75dc8)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (c000000000d857e0)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (c000000000d9087c)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (c000000000d96538)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ec38)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (c000000000dc1150)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffe0007d4570)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffe0007de4e6)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffe0007e63e4)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea1ea)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efe08)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffe000805a86)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff8195d4e7)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819689fd)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81971c86)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819763a9)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c9de)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81994d02)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff81916fd7)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819224ed)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff8192b756)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8192fe69)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8193649e)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff8194e7c2)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff819c7cb7)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819d31cd)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819dc456)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0b79)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e71ae)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff819ff5a2)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
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
In net/ipv4/tcp.c (ffffffff819d1807)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819dcd73)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819e60d6)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea839)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0e7e)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/af_inet.c (ffffffff81a096a2)
Location: include/net/tcp.h:2176
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
```
</details>
</li>
</ul>

## Differences
