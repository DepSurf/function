# Function: <code>skb_wifi_acked_valid</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e01a3c)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81e097c1)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe8c8)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81f6d194)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff82003ce7)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81ebe3fc)
Location: include/linux/skbuff.h:1208
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81ec61b2)
Location: include/linux/skbuff.h:1208
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2aee)
Location: include/linux/skbuff.h:1208
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff82033907)
Location: include/linux/skbuff.h:1208
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff820d2a98)
Location: include/linux/skbuff.h:1208
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
