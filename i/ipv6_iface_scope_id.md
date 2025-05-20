# Function: <code>ipv6_iface_scope_id</code>

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
In net/ipv4/ping.c (ffffffff817a3548)
Location: include/net/ipv6.h:361
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff817c2ab9)
Location: include/net/ipv6.h:361
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff817e312b)
Location: include/net/ipv6.h:361
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff817e5753)
Location: include/net/ipv6.h:361
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff817f5489)
Location: include/net/ipv6.h:361
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f745e)
Location: include/net/ipv6.h:361
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff818105b0)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8182fb19)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff818513c7)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81853a0c)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff8186454b)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818665ae)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81841ab0)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81861599)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff818833c9)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8188571c)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81896cc0)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81898c9e)
Location: include/net/ipv6.h:378
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81863200)
Location: include/net/ipv6.h:379
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81885cdb)
Location: include/net/ipv6.h:379
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff818a808d)
Location: include/net/ipv6.h:379
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818abae5)
Location: include/net/ipv6.h:379
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff818bd208)
Location: include/net/ipv6.h:379
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818beea0)
Location: include/net/ipv6.h:379
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff818e3330)
Location: include/net/ipv6.h:420
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81906e8b)
Location: include/net/ipv6.h:420
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff8192ab3d)
Location: include/net/ipv6.h:420
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8192e6a5)
Location: include/net/ipv6.h:420
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81940328)
Location: include/net/ipv6.h:420
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81941fe0)
Location: include/net/ipv6.h:420
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81939cc6)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8195de6b)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81982e50)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8198762a)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81998ef1)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199ae1a)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81969953)
Location: include/net/ipv6.h:428
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819929ab)
Location: include/net/ipv6.h:428
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff819b9507)
Location: include/net/ipv6.h:428
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bdc37)
Location: include/net/ipv6.h:428
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819cfa04)
Location: include/net/ipv6.h:428
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d176a)
Location: include/net/ipv6.h:428
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff819d05d1)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819fe2c7)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81a28006)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2c71d)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e71b)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a4050a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81a07121)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a34eb7)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81a5ea6f)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6325d)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7538b)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a7717a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81af7721)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b29d3e)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81b57fd4)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c1ad)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6f5c7)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b7142a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81b04601)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b3867e)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81b66679)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6a89d)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7e0f7)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b8009a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81aef611)
Location: include/net/ipv6.h:487
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b2632b)
Location: include/net/ipv6.h:487
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81b5480c)
Location: include/net/ipv6.h:487
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b58e3d)
Location: include/net/ipv6.h:487
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6ccd7)
Location: include/net/ipv6.h:487
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6ec9a)
Location: include/net/ipv6.h:487
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81bb0b9e)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81becee8)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81c1bca9)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c203f5)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81c34b91)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36bba)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81d44103)
Location: include/net/ipv6.h:544
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81d855d8)
Location: include/net/ipv6.h:544
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81db8442)
Location: include/net/ipv6.h:544
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd15c)
Location: include/net/ipv6.h:544
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd2535)
Location: include/net/ipv6.h:544
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd46ca)
Location: include/net/ipv6.h:544
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81f0d5d2)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81f53088)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81f8847b)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8d17c)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa39b5)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa5d2a)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81f6d234)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2a5d)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81fe8d8b)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fed94c)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff82004294)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8200659a)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff82033988)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff82080214)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff820b68b7)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bb55c)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff820d3054)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d53fa)
Location: include/net/ipv6.h:578
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffff800010cc0040)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffff800010cf5960)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffff800010d25f2c)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d28570)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffff800010d3dd40)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d40808)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (c0dcc528)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (c0dfc3a8)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (c0e2a36c)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d630)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c0e40ff8)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (c0e43204)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (c000000000ddb3d8)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (c000000000e1bb74)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (c000000000e53ca8)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e5991c)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c000000000e72284)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e74e0c)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffe000816ad6)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffe0008412ec)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffe0008652b2)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe000869df4)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffe00087a366)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c0ee)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff819a6ec1)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819d4547)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff819fe0ff)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a028ed)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a14a1b)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a1680a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81960981)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81991307)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff819baebf)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bf6ad)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819d17db)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d35ca)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/netfilter/nf_conntrack_proto.c (ffffffff819a456f)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
```
```
In net/ipv4/ping.c (ffffffff81a11761)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a3efc7)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81a68b7f)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6d36d)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7f49b)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8128a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
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
In net/ipv4/ping.c (ffffffff81a1c0d1)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a4aa87)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/udp.c (ffffffff81a7516a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a7998d)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8bd5b)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8db5a)
Location: include/net/ipv6.h:486
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
```
</details>
</li>
</ul>

## Differences
