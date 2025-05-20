# Function: <code>sk_state_load</code>

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
In net/ipv4/inet_connection_sock.c (ffffffff8176548a)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff817666c1)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177b443)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817ef4b1)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff817d1a9a)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff817d2be1)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e8cb3)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185e099)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff8180194a)
Location: include/net/sock.h:2306
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81802771)
Location: include/net/sock.h:2306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818ea0)
Location: include/net/sock.h:2306
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818901d6)
Location: include/net/sock.h:2306
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff81821b2a)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81825037)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839642)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b6798)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/inet_connection_sock.c (ffffffff818a0b43)
Location: include/net/sock.h:2347
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff818a39ad)
Location: include/net/sock.h:2347
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8dd2)
Location: include/net/sock.h:2347
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819395c8)
Location: include/net/sock.h:2347
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
