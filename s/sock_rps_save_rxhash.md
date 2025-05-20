# Function: <code>sock_rps_save_rxhash</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177d979)
Location: include/net/sock.h:897
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177faee)
Location: include/net/sock.h:897
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81786f40)
Location: include/net/sock.h:897
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv4/syncookies.c (ffffffff817ab2a8)
Location: include/net/sock.h:897
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff817e1912)
Location: include/net/sock.h:897
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f173d)
Location: include/net/sock.h:897
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff817ea63c)
Location: include/net/sock.h:899
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ecfe7)
Location: include/net/sock.h:899
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff817f4212)
Location: include/net/sock.h:899
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv4/syncookies.c (ffffffff81818d98)
Location: include/net/sock.h:899
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff8184fc52)
Location: include/net/sock.h:899
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f630)
Location: include/net/sock.h:899
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8181b16c)
Location: include/net/sock.h:933
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d920)
Location: include/net/sock.h:933
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81827d12)
Location: include/net/sock.h:933
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv4/syncookies.c (ffffffff8184a5f8)
Location: include/net/sock.h:933
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81884132)
Location: include/net/sock.h:933
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891575)
Location: include/net/sock.h:933
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8183b822)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183df54)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81848990)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/syncookies.c (ffffffff8186df94)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff818aa4bd)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7a9b)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff818bb256)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd49c)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff818c83b8)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/syncookies.c (ffffffff818ee90a)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff8192cfcd)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a90b)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81910996)
Location: include/net/sock.h:957
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913071)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff8191e29c)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/syncookies.c (ffffffff8194521a)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81984c5d)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993fe2)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8193f27b)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941831)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff8194ceee)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff8197550a)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff819bb243)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca8f2)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819a3783)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5e35)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff819b16a7)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff819df0bc)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81a29e56)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39517)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819da3a3)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dce05)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff819e840b)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81a1614c)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81a60976)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a700a7)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac763d)
Location: include/net/sock.h:1044
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9f72)
Location: include/net/sock.h:1044
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81ad6348)
Location: include/net/sock.h:1044
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81b07123)
Location: include/net/sock.h:1044
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81b5747c)
Location: include/net/sock.h:1044
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69cb0)
Location: include/net/sock.h:1044
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad2f7d)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5ec7)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81ae269d)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv4/syncookies.c (ffffffff81b15314)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81b6599c)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78790)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81abdbad)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0f24)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81acd850)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81b03124)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81b56133)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66a90)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81b7b082)
Location: include/net/sock.h:1075
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e77b)
Location: include/net/sock.h:1075
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81b8c22d)
Location: include/net/sock.h:1075
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81bc5364)
Location: include/net/sock.h:1075
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81c1c7b0)
Location: include/net/sock.h:1075
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e640)
Location: include/net/sock.h:1075
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0ba23)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0f042)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81d1c828)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81d5a529)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81db9038)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb2d8)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ed1983)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4ba2)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81ee3831)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81f24959)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81f88fa9)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c368)
Location: include/net/sock.h:1159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81f30101)
Location: include/net/sock.h:1165
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33870)
Location: include/net/sock.h:1165
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81f430a2)
Location: include/net/sock.h:1165
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81f844ef)
Location: include/net/sock.h:1165
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81fe8368)
Location: include/net/sock.h:1165
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffcdc6)
Location: include/net/sock.h:1165
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff5f91)
Location: include/net/sock.h:1142
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff99e3)
Location: include/net/sock.h:1142
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff8200900b)
Location: include/net/sock.h:1142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff8204ae8d)
Location: include/net/sock.h:1142
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff820b6ebc)
Location: include/net/sock.h:1142
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cbee6)
Location: include/net/sock.h:1142
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffff800010c8d448)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c90480)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffff800010c9d850)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffff800010cd1e20)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffff800010d26568)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d389dc)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (c0d9c5a4)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (c0d9ec08)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (c0dab298)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (c0ddbb28)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (c0e29b64)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c0e3ad90)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (c000000000d9c554)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9eff0)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (c000000000daf124)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (c000000000df0118)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (c000000000e561c4)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b32c)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffe0007ed8ae)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007f005a)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffe0007fa84e)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffe000823126)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffe000866bfe)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875c2e)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8197a213)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197cc75)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff8198827b)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff819b57dc)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81a00006)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f737)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81933cd3)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936735)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff81941d3b)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff819725cc)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff819bcdc6)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc4f7)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819e49e3)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7445)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff819f2a4b)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81a2007c)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81a6aa86)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a1b7)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819eeb23)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f1115)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/udp.c (ffffffff819fcf4b)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/syncookies.c (ffffffff81a2b57c)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/udp.c (ffffffff81a77096)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a869f7)
Location: include/net/sock.h:998
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
</details>
</li>
</ul>

## Differences
