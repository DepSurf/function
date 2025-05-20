# Function: <code>net_tx_rndhash</code>

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
In net/ipv4/tcp_input.c (ffffffff8176e026)
Location: include/net/sock.h:1691
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81774fee)
Location: include/net/sock.h:1691
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a5ad)
Location: include/net/sock.h:1691
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c67b)
Location: include/net/sock.h:1691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81783fb5)
Location: include/net/sock.h:1691
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f00ae)
Location: include/net/sock.h:1691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff817f42c1)
Location: include/net/sock.h:1691
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/sock.c (ffffffff8176b5da)
Location: include/net/sock.h:1652
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff817dc44b)
Location: include/net/sock.h:1652
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff817e1fae)
Location: include/net/sock.h:1652
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff817e77e1)
Location: include/net/sock.h:1652
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e9fc4)
Location: include/net/sock.h:1652
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff817f1547)
Location: include/net/sock.h:1652
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185eef9)
Location: include/net/sock.h:1652
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818639d2)
Location: include/net/sock.h:1652
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
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
In net/core/sock.c (ffffffff817986ad)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff8180c37d)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8181251e)
Location: include/net/sock.h:1714
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81817f5c)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181a741)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81822123)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189108a)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81895f51)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/sock.c (ffffffff817b6246)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff8182c500)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8183278e)
Location: include/net/sock.h:1719
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81838474)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183aed4)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81842d8d)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff8186e27d)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b765e)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bc64c)
Location: include/net/sock.h:1719
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff818c84be)
Location: include/net/sock.h:1719
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
In net/core/sock.c (ffffffff8182e7de)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff818ab3d3)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff818b193e)
Location: include/net/sock.h:1733
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7b90)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bab04)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff818c26f0)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff818eec0d)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a4a4)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193f772)
Location: include/net/sock.h:1733
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff8194ba74)
Location: include/net/sock.h:1733
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
In net/core/sock.c (ffffffff81878c71)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81900816)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81906b7e)
Location: include/net/sock.h:1744
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d4a2)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f57f)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81918338)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff8194551d)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993470)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819984e8)
Location: include/net/sock.h:1744
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff819a4d10)
Location: include/net/sock.h:1744
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
In net/core/sock.c (ffffffff81899629)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff8192e96e)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff8193532e)
Location: include/net/sock.h:1829
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b888)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d9a6)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81946a8c)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff819758d0)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c980b)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819ceeb1)
Location: include/net/sock.h:1829
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff819db814)
Location: include/net/sock.h:1829
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
In net/core/sock.c (ffffffff818e3cca)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81991f2c)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81998cef)
Location: include/net/sock.h:1841
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8199fcd8)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1df1)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ab0de)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff819df41b)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38284)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a3da3b)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81a4a49e)
Location: include/net/sock.h:1841
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
In net/core/sock.c (ffffffff81915eab)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819c8d15)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff819cf80f)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819d68af)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8ab1)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819e1dae)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a16488)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6edcc)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a746ab)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81a81066)
Location: include/net/sock.h:1851
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
In net/core/sock.c (ffffffff819e93f2)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4082)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81abc60f)
Location: include/net/sock.h:1900
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2899)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac54f7)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81acf61f)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b07499)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67a02)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6e8b3)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81b7bd05)
Location: include/net/sock.h:1900
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff819e92b4)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81abe9b1)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81ac79af)
Location: include/net/sock.h:1912
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace1e5)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1186)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81adb624)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b15899)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76221)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b7d48f)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81b8ad7b)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff819cf3d1)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81aaad22)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2a0f)
Location: include/net/sock.h:1928
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab937b)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abc177)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81ac6694)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b036ab)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64c55)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6c073)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81b79bde)
Location: include/net/sock.h:1928
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff81a7f058)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81b6722a)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f8df)
Location: include/net/sock.h:1968
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81b767d4)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79277)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81b84ea4)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81bc593b)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2ce80)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81c33f0c)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81c44888)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff81bf23c7)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81cf61ee)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81cfef47)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05f39)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d087ca)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81d15746)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81d5abc3)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca231)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd18be)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81de3895)
Location: include/net/sock.h:2089
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff81d9fce6)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ebabfe)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3f97)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb1fb)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81eced3e)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_plb.c (ffffffff81edb6b0)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
```
```
In net/ipv4/datagram.c (ffffffff81edb942)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81f25033)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b244)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81fa2ecc)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81fb5f15)
Location: include/net/sock.h:2126
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff81e0e523)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81f19092)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff81f222a7)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29d1f)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d0c3)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_plb.c (ffffffff81f3a770)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
```
```
In net/ipv4/datagram.c (ffffffff81f3aa05)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81f84bc3)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffc648)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff82003785)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff8201662e)
Location: include/net/sock.h:2114
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff81ecafc9)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81fdd959)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5f67)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee88f)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1f34)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_plb.c (ffffffff820008e0)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
```
```
In net/ipv4/datagram.c (ffffffff82000af5)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff8204abc9)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c9980)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820d255c)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/core/sock.c (ffff800010baeb24)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffff800010c7a854)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffff800010c8249c)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffff800010c897e0)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d7e4)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffff800010c95f74)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffff800010cd21ac)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37684)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3d090)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffff800010d4c830)
Location: include/net/sock.h:1851
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
In net/core/sock.c (c0ccc8a4)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (c0d881f8)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (c0d912cc)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (c0d988b4)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9b838)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c0da475c)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (c0ddc03c)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (c0e39a0c)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e40304)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (c0e4db30)
Location: include/net/sock.h:1851
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
In net/core/sock.c (c000000000c84afc)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (c000000000d85494)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (c000000000d8d7f4)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (c000000000d96bd0)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9a2a0)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c000000000da719c)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (c000000000df060c)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69f94)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c000000000e71200)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (c000000000e82fa8)
Location: include/net/sock.h:1851
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
In net/core/sock.c (ffffffe000740874)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffe0007de57a)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffe0007e427a)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea69e)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed188)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffe0007f4f58)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffe00082356e)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874ac0)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe0008798e4)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffe00088559e)
Location: include/net/sock.h:1851
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
In net/core/sock.c (ffffffff818b5eab)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81968b85)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff8196f67f)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8197671f)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978921)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81981c1e)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff819b5b18)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e45c)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a13d3b)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81a206f6)
Location: include/net/sock.h:1851
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
In net/core/sock.c (ffffffff8186fdfb)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81922675)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff8192914f)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819301df)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819323e1)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff8193b6de)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81972908)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb21c)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819d0afb)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff819dd4b6)
Location: include/net/sock.h:1851
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
In net/core/sock.c (ffffffff81906eab)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819d3355)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff819d9e4f)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0eef)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e30f1)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ec3ee)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a203b8)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78edc)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7e7bb)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81a8b176)
Location: include/net/sock.h:1851
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
In net/core/sock.c (ffffffff81927ef1)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819dcefb)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_output.c (ffffffff819e3abf)
Location: include/net/sock.h:1851
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819eabb2)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ed211)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819f62ac)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a2b8b8)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8567a)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a8b1e9)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/syncookies.c (ffffffff81a97d98)
Location: include/net/sock.h:1851
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
</ul>

## Differences
