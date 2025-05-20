# Function: <code>sk_dst_set</code>

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
In net/core/sock.c (ffffffff81700835)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/route.c (ffffffff8175705d)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81760a35)
Location: include/net/sock.h:1761
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764693)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81783d58)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817844cf)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81786c86)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81793337)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff817a2c73)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc160)
Location: include/net/sock.h:1761
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff81767262)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff817c332b)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ccd67)
Location: include/net/sock.h:1722
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0bf3)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff817f130a)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f1a8f)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff817f3cc6)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81800cc5)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff818115b5)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184ae40)
Location: include/net/sock.h:1722
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff817942e2)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff817f1997)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fca87)
Location: include/net/sock.h:1784
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800a73)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff818223aa)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8182286d)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81824aa6)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81831c15)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff81842ac5)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187cce0)
Location: include/net/sock.h:1784
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff817b26b2)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff8181327e)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181ce63)
Location: include/net/sock.h:1788
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820653)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81843018)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818434a8)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff818457f6)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818531ab)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff818643c6)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a27e0)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff8182a872)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff818928ca)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189bdd7)
Location: include/net/sock.h:1802
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f619)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff818c297e)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c2e88)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff818c525c)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818d2ff4)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff818e4512)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81925150)
Location: include/net/sock.h:1802
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff818749c5)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff818e686a)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f03c7)
Location: include/net/sock.h:1813
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f403a)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff819185ec)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81918991)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff8191ac2c)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8192b383)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff8193ab81)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d510)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff818951d5)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff818d69ee)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff819136c3)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191dfaa)
Location: include/net/sock.h:1898
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921b49)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81946d65)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81947163)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819493ec)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8195a807)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff8196a871)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b33e0)
Location: include/net/sock.h:1898
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff818df705)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff819242b0)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81975d01)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81980964)
Location: include/net/sock.h:1910
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984518)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff819ab3e5)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ab7e3)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819ada3c)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819bf3da)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819d1526)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a21ac0)
Location: include/net/sock.h:1910
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff819118d5)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff819565c7)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff819ac711)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b732f)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bacc8)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff819e20b5)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e24b3)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819e4703)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819f601a)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a08086)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a58530)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff819e3715)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff81a2a382)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81a96bff)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9f84f)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5588)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81acf3bc)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81acfcb3)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81ad21b3)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ae450b)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81af7e63)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b50a60)
Location: include/net/sock.h:1969
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff819e3265)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff81a2add1)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81aa0cdc)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa979f)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafb98)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81adb3c1)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adbc33)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81ade2f0)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81af143b)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81b04dc6)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fd20)
Location: include/net/sock.h:1988
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff819c92b5)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff81a11f61)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81a8bc1c)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9496f)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9aea8)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81ac6422)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac6a75)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81ac9910)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81adcbf4)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81af0626)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e000)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff81bbc087)
Location: include/net/sock.h:2005
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81a78655)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff81acd289)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81b46bac)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b4fdf0)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56318)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81b84c32)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b85299)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81b88184)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81b9bfe4)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81bb127f)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c1532b)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff81c8bc27)
Location: include/net/sock.h:2045
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81bebf75)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff81c4a94a)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81cd3c5d)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfe09)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4433)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81d154cf)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d15d67)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81d19654)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81d2ded6)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81d44839)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0b1b)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff81e332a8)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81d98945)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81e93e8d)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea01c9)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6d80)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81edbcbf)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edc1a7)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81edffe4)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ef5e06)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81f0d8d9)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80c80)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff8200c9a8)
Location: include/net/sock.h:2203
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81e081a0)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81ef2629)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efea19)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05550)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81f3ad8f)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3b23c)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81f3f4c0)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81f55666)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81f6d533)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe0fe5)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff820892fd)
Location: include/net/sock.h:2191
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81ec4bf6)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81fb6742)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2c3f)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc98b6)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff82000e83)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8200134c)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff82007880)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8201bada)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff82033c83)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820aeb69)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff8215ec13)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffff800010ba957c)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffff800010bfdf94)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffff800010c5c8e4)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffff800010c68434)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6cc50)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffff800010c95d48)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c96bbc)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffff800010c99764)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffff800010cac938)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffff800010cc1294)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1ded0)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (c0cca568)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (c0d14e3c)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (c0d6bf84)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c0d774b0)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7b974)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (c0da44d0)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5404)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (c0da982c)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c0db8f18)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c0dcd1e4)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (c0e224c8)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (c000000000c7e584)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (c000000000cde6c4)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (c000000000d5ecfc)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c000000000d6cd90)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c000000000d7225c)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (c000000000da7570)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da7b18)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (c000000000daab94)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c000000000dc2820)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c000000000ddc848)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4c12c)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffe00073c91e)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffe000779c58)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffe0007c5714)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007ce5e2)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d21e6)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffe0007f51c2)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f5522)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffe0007f7006)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffe000806862)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffe000816416)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000860a38)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff818b18d5)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff818f6597)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff8194c581)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195719f)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ab38)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff81981f25)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81982323)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81984573)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81995dba)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819a7e26)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7bc0)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff8186b825)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff818b03c7)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81906071)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81910c8f)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914628)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff8193b9e5)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193bde3)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff8193e033)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8194f87a)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819618e6)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b4980)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff819028d5)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff819475c7)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff819b6d51)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c196f)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5308)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff819ec6f5)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ecaf3)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819eed43)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81a0065a)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a126c6)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a62640)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff81923875)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/filter.c (ffffffff81968ed7)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff819c05e2)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cb35e)
Location: include/net/sock.h:1920
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cedd8)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/datagram.c (ffffffff819f65df)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f69e3)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819f8eb3)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81a0ab1a)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a1d0c4)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6eb40)
Location: include/net/sock.h:1920
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
</details>
</li>
</ul>

## Differences
