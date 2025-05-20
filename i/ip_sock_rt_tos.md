# Function: <code>ip_sock_rt_tos</code>

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
In net/ipv4/route.c (ffffffff81cd3126)
Location: include/net/route.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08614)
Location: include/net/route.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81d1564a)
Location: include/net/route.h:54
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff81d2c57f)
Location: include/net/route.h:54
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
In net/ipv4/route.c (ffffffff81e90a58)
Location: include/net/route.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81eceb51)
Location: include/net/route.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81edb843)
Location: include/net/route.h:54
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff81ef4eb1)
Location: include/net/route.h:54
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
In net/ipv4/route.c (ffffffff81eef1f1)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05ecf)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ceed)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81f3a903)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff81f54791)
Location: include/net/route.h:51
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81f84e2a)
Location: include/net/route.h:51
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
In net/ipv4/route.c (ffffffff81fb335d)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca092)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1d5e)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff82000a0a)
Location: include/net/route.h:51
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/af_inet.c (ffffffff8201aa32)
Location: include/net/route.h:51
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8204b5a0)
Location: include/net/route.h:51
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
