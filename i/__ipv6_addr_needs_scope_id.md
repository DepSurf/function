# Function: <code>__ipv6_addr_needs_scope_id</code>

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
In net/ipv4/ping.c (ffffffff817a2a14)
Location: include/net/ipv6.h:354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff817c2abe)
Location: include/net/ipv6.h:354
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/udp.c (ffffffff817e2811)
Location: include/net/ipv6.h:354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff817e51ff)
Location: include/net/ipv6.h:354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff817e78b8)
Location: include/net/ipv6.h:354
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff817f267b)
Location: include/net/ipv6.h:354
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff817f410f)
Location: include/net/ipv6.h:354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f7463)
Location: include/net/ipv6.h:354
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
In net/ipv4/ping.c (ffffffff818105b5)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8182fb1e)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81850cf2)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818548cd)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81855cf0)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff818613be)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81864550)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818665b3)
Location: include/net/ipv6.h:371
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
In net/ipv4/ping.c (ffffffff81841ab5)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8186159e)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81882b41)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818865ff)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81887ab0)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff818932fe)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81896cc5)
Location: include/net/ipv6.h:371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81898ca3)
Location: include/net/ipv6.h:371
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
In net/ipv4/ping.c (ffffffff81863205)
Location: include/net/ipv6.h:372
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81885ce0)
Location: include/net/ipv6.h:372
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/udp.c (ffffffff818a9582)
Location: include/net/ipv6.h:372
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818ac660)
Location: include/net/ipv6.h:372
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff818ae0d7)
Location: include/net/ipv6.h:372
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff818b98c1)
Location: include/net/ipv6.h:372
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff818bd20d)
Location: include/net/ipv6.h:372
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818beea5)
Location: include/net/ipv6.h:372
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
In net/ipv4/ping.c (ffffffff818e3335)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81906e90)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/udp.c (ffffffff8192bfc2)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8192f03a)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81930d57)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff8193c841)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff8194032d)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81941fe5)
Location: include/net/ipv6.h:413
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
In net/ipv4/ping.c (ffffffff81939ccf)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8195de70)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff819841c3)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81987e61)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff819898ba)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff819958bc)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81998ef6)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199ae23)
Location: include/net/ipv6.h:401
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
In net/ipv4/ping.c (ffffffff8196995c)
Location: include/net/ipv6.h:421
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819929b0)
Location: include/net/ipv6.h:421
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff819ba730)
Location: include/net/ipv6.h:421
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819be7b5)
Location: include/net/ipv6.h:421
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff819c01a3)
Location: include/net/ipv6.h:421
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff819cc19e)
Location: include/net/ipv6.h:421
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819cfa09)
Location: include/net/ipv6.h:421
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d1773)
Location: include/net/ipv6.h:421
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
In net/ipv4/ping.c (ffffffff819d05d6)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819fe2cc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81a2981b)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2d892)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a2efd8)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81a3ac7b)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e720)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a40513)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffff81a07126)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a34ebc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81a60377)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a643ff)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a65b28)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81a718fb)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a75390)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a77183)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffff81af7726)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b29d43)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81b58eae)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5ce67)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b5e469)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81b6b1ee)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6f5cc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b71433)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffff81b04606)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b38683)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81b674eb)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b6a4)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b6cc40)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81b79c6e)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7e0fc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b800a3)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffff81aef616)
Location: include/net/ipv6.h:480
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b26330)
Location: include/net/ipv6.h:480
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81b556c5)
Location: include/net/ipv6.h:480
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b599f8)
Location: include/net/ipv6.h:480
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b5afb7)
Location: include/net/ipv6.h:480
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81b6879b)
Location: include/net/ipv6.h:480
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6ccdc)
Location: include/net/ipv6.h:480
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6eca3)
Location: include/net/ipv6.h:480
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
In net/ipv4/ping.c (ffffffff81bb0ba3)
Location: include/net/ipv6.h:483
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81beceed)
Location: include/net/ipv6.h:483
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81c1e19e)
Location: include/net/ipv6.h:483
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c2101e)
Location: include/net/ipv6.h:483
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81c226c7)
Location: include/net/ipv6.h:483
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81c30465)
Location: include/net/ipv6.h:483
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81c34b96)
Location: include/net/ipv6.h:483
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36bc3)
Location: include/net/ipv6.h:483
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
In net/ipv4/ping.c (ffffffff81d4410c)
Location: include/net/ipv6.h:537
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81d855dd)
Location: include/net/ipv6.h:537
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81dba80e)
Location: include/net/ipv6.h:537
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbe0dc)
Location: include/net/ipv6.h:537
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81dbf482)
Location: include/net/ipv6.h:537
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81dcdb61)
Location: include/net/ipv6.h:537
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd253a)
Location: include/net/ipv6.h:537
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd46d3)
Location: include/net/ipv6.h:537
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
In net/ipv4/ping.c (ffffffff81f0d5db)
Location: include/net/ipv6.h:570
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81f5308d)
Location: include/net/ipv6.h:570
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81f8a8bb)
Location: include/net/ipv6.h:570
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8e314)
Location: include/net/ipv6.h:570
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81f8fbd2)
Location: include/net/ipv6.h:570
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81f9ed91)
Location: include/net/ipv6.h:570
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa39ba)
Location: include/net/ipv6.h:570
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa5d33)
Location: include/net/ipv6.h:570
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
In net/ipv4/ping.c (ffffffff81f6d23d)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2a62)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81fea1cf)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81feeb02)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81ff0402)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81fff856)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff82004299)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820065a3)
Location: include/net/ipv6.h:571
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
In net/ipv4/ping.c (ffffffff82033991)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff82080219)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff820b81f0)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bc6d4)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff820bdfd2)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff820ce623)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff820d3059)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d5403)
Location: include/net/ipv6.h:571
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
In net/ipv4/ping.c (ffff800010cc0044)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffff800010cf5968)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffff800010d259f4)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d2a50c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffff800010d2bbd0)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffff800010d3a360)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffff800010d3dd44)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d4080c)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (c0dcc548)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c0dfc3ac)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (c0e2928c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2e2f4)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (c0e2fa40)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (c0e3c884)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c0e40ffc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (c0e43208)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (c000000000ddb3e0)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c000000000e1bb7c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (c000000000e5553c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e5b418)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (c000000000e5d23c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (c000000000e6d590)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c000000000e7228c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e74e14)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffe000816ade)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffe0008412fc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffe000866496)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe00086ad38)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffe00086bed0)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffe000876ffc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffe00087a37c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c106)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffff819a6ec6)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819d454c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff819ffa07)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a03a8f)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a051b8)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81a10f8b)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a14a20)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a16813)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffff81960986)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8199130c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff819bc7c7)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819c084f)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff819c1f78)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff819cdd4b)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819d17e0)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d35d3)
Location: include/net/ipv6.h:479
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
In net/netfilter/nf_conntrack_proto.c (ffffffff819a4579)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
```
```
In net/ipv4/ping.c (ffffffff81a11766)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a3efcc)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81a6a487)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6e50f)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a6fc38)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81a7ba0b)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7f4a0)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a81293)
Location: include/net/ipv6.h:479
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
In net/ipv4/ping.c (ffffffff81a1c0d6)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a4aa8c)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/udp.c (ffffffff81a76aa4)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a7ab41)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a7c274)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ping.c (ffffffff81a8825b)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8bd60)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8db63)
Location: include/net/ipv6.h:479
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
```
</details>
</li>
</ul>

## Differences
