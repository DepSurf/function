# Function: <code>sock_rps_record_flow</code>

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
In net/ipv4/tcp.c (ffffffff81766250)
Location: include/net/sock.h:890
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81788a99)
Location: include/net/sock.h:890
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff817938e2)
Location: include/net/sock.h:890
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_sendpage
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
In net/ipv4/tcp.c (ffffffff817d27b0)
Location: include/net/sock.h:892
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff817f63f9)
Location: include/net/sock.h:892
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818026fe)
Location: include/net/sock.h:892
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In net/ipv4/tcp.c (ffffffff81802ba8)
Location: include/net/sock.h:913
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81826ea0)
Location: include/net/sock.h:913
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff8183368e)
Location: include/net/sock.h:913
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In net/ipv4/tcp.c (ffffffff81822988)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81848623)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818543ee)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In net/ipv4/tcp.c (ffffffff818a1aa8)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff818c8083)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818d427e)
Location: include/net/sock.h:930
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In net/ipv4/tcp.c (ffffffff818f65c8)
Location: include/net/sock.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8192a996)
Location: include/net/sock.h:937
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In net/ipv4/tcp.c (ffffffff819264b8)
Location: include/net/sock.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8195a196)
Location: include/net/sock.h:965
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
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
In net/ipv4/tcp.c (ffffffff81988e58)
Location: include/net/sock.h:968
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819bed60)
Location: include/net/sock.h:968
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819fe550)
Location: include/net/sock.h:968
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff819c02b8)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819f59a0)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a35140)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81aa9997)
Location: include/net/sock.h:1024
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ae3f00)
Location: include/net/sock.h:1024
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a0e0)
Location: include/net/sock.h:1024
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81ab6dbf)
Location: include/net/sock.h:1039
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81af0e10)
Location: include/net/sock.h:1039
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b38a20)
Location: include/net/sock.h:1039
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81aa1fbf)
Location: include/net/sock.h:1043
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81adc5d0)
Location: include/net/sock.h:1043
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b26710)
Location: include/net/sock.h:1043
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81b5dd92)
Location: include/net/sock.h:1055
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81b9b9c0)
Location: include/net/sock.h:1055
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81bec170)
Location: include/net/sock.h:1055
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81cec7a7)
Location: include/net/sock.h:1101
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81d2dca2)
Location: include/net/sock.h:1101
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81d846a2)
Location: include/net/sock.h:1101
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81eb0689)
Location: include/net/sock.h:1139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ef5bc2)
Location: include/net/sock.h:1139
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81f51fc2)
Location: include/net/sock.h:1139
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81f0eb3b)
Location: include/net/sock.h:1141
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81f54f62)
Location: include/net/sock.h:1141
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:__inet_accept
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81fb19d2)
Location: include/net/sock.h:1141
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81fd2ca6)
Location: include/net/sock.h:1118
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8201b1d2)
Location: include/net/sock.h:1118
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:__inet_accept
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff8207f0f2)
Location: include/net/sock.h:1118
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffff800010c72860)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffff800010cac6d8)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffff800010cf57f8)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (c0d7f790)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c0db82ac)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (c0dfc234)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (c000000000d776f0)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c000000000dc1c78)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (c000000000e1b9d8)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffe0007d60b6)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffe00080616c)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffe0008411d8)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81960128)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81995740)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819d47d0)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff81919c18)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8194f200)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81991590)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff819ca8f8)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819fffe0)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f250)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In net/ipv4/tcp.c (ffffffff819d4468)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81a0a582)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ad12)
Location: include/net/sock.h:978
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
```
</details>
</li>
</ul>

## Differences
