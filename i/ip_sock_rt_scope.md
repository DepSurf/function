# Function: <code>ip_sock_rt_scope</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd3137)
Location: include/net/route.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0860a)
Location: include/net/route.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81d15641)
Location: include/net/route.h:46
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff81d2c57c)
Location: include/net/route.h:46
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
In net/ipv4/route.c (ffffffff81e90a10)
Location: include/net/route.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81eceb43)
Location: include/net/route.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81edb83a)
Location: include/net/route.h:46
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff81ef4eae)
Location: include/net/route.h:46
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
In net/ipv4/route.c (ffffffff81eef1a9)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05eb7)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ceb6)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81f3a8fa)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff81f5478e)
Location: include/net/route.h:43
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81f84e09)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81fb330f)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca063)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1d2f)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff820009ed)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff8201a9e4)
Location: include/net/route.h:43
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8204b55c)
Location: include/net/route.h:43
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
