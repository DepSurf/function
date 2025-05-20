# Function: <code>sock_orphan</code>

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
In net/core/sock.c (ffffffff817040c2)
Location: include/net/sock.h:1669
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff8174df0f)
Location: include/net/sock.h:1669
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764a57)
Location: include/net/sock.h:1669
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8176a301)
Location: include/net/sock.h:1669
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff817bfd93)
Location: include/net/sock.h:1669
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81805a47)
Location: include/net/sock.h:1669
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff8176ab32)
Location: include/net/sock.h:1630
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff817ba0c2)
Location: include/net/sock.h:1630
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0fc7)
Location: include/net/sock.h:1630
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff817d6d71)
Location: include/net/sock.h:1630
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff8182d1a3)
Location: include/net/sock.h:1630
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff8187660b)
Location: include/net/sock.h:1630
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff81797c52)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff817e9ade)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800e87)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81806d91)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff8185ec83)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818aab8b)
Location: include/net/sock.h:1686
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff817b5812)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81809715)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820be7)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81827476)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff81882f15)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818d1629)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff8182dcd5)
Location: include/net/sock.h:1704
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81888668)
Location: include/net/sock.h:1704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fbd7)
Location: include/net/sock.h:1704
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff818a6282)
Location: include/net/sock.h:1704
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff819048e1)
Location: include/net/sock.h:1704
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81956582)
Location: include/net/sock.h:1704
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff818780bb)
Location: include/net/sock.h:1715
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff818dc08e)
Location: include/net/sock.h:1715
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4c55)
Location: include/net/sock.h:1715
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff818fb2f2)
Location: include/net/sock.h:1715
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff8195a11f)
Location: include/net/sock.h:1715
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819b19c0)
Location: include/net/sock.h:1715
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff819cbfe7)
Location: include/net/sock.h:1715
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff8189859b)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81908a5b)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922155)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81929242)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff8198ec7f)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819e8da0)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a05220)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff818e2b4e)
Location: include/net/sock.h:1812
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81969e90)
Location: include/net/sock.h:1812
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985236)
Location: include/net/sock.h:1812
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8198c166)
Location: include/net/sock.h:1812
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff819fa2a1)
Location: include/net/sock.h:1812
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a590d9)
Location: include/net/sock.h:1812
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a7485e)
Location: include/net/sock.h:1812
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81914d2e)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff819a0900)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb326)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff819c2ab6)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff81a30f21)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a8f1e9)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab2a1)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff819e6cce)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81a7a080)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6226)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81aae09a)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff81b25660)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b8b5df)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba76e2)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/subflow.c (ffffffff81bade31)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In net/core/sock.c (ffffffff819e64fe)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81a82ee0)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0876)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81ab831d)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/unix/af_unix.c (ffffffff81b34070)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b9a5a9)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb65c5)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bc007f)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bc0eac)
Location: include/net/sock.h:1883
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In net/core/sock.c (ffffffff819cbf2e)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81a6bfb0)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ba56)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81aa3617)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/unix/af_unix.c (ffffffff81b21bb0)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b89518)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba5585)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81baff2f)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bb0fac)
Location: include/net/sock.h:1899
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In net/core/sock.c (ffffffff81a7b58e)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81b255b7)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57076)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81b5f7b7)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/unix/af_unix.c (ffffffff81be70e0)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81c55628)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c7310d)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c7dd51)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81c7f099)
Location: include/net/sock.h:1939
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In net/core/sock.c (ffffffff81befe7b)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81cae0e5)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4fe5)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81cee270)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/unix/af_unix.c (ffffffff81d7e711)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81df53b9)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16e72)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e22231)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81e24977)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mctp/af_mctp.c (ffffffff81e37a31)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In net/core/sock.c (ffffffff81d9c41b)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81e6b6b5)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7c35)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81eb14d0)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/unix/af_unix.c (ffffffff81f4b80d)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81fc7d39)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee842)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ffa6a6)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mctp/af_mctp.c (ffffffff82010c8c)
Location: include/net/sock.h:2097
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In net/core/sock.c (ffffffff81e0ac6b)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81ec76f5)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06475)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81f0fb60)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/unix/af_unix.c (ffffffff81fab5b4)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff82028cdd)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a952)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82076e77)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close
```
```
In net/mctp/af_mctp.c (ffffffff8208d4fc)
Location: include/net/sock.h:2084
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In net/core/sock.c (ffffffff81ec765b)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81f8aa35)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca765)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81fd3d50)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/unix/af_unix.c (ffffffff820789a4)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff820f871d)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e583)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214bc5b)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close
```
```
In net/mctp/af_mctp.c (ffffffff821639bc)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In net/core/sock.c (ffff800010bada38)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffff800010c4f038)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c8f4)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffff800010c75884)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffff800010cf114c)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffff800010d5c3f0)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f1d4)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (c0ccb5f0)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (c0d5f1c4)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (c0d7be28)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (c0d83f80)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (c0df8234)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c0e5c434)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e79348)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (c000000000c8338c)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (c000000000d4d764)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72c14)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (c000000000d7d078)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (c000000000e16120)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c000000000e97eec)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf42c)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffe00073fc76)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffe0007bad0a)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2274)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffe0007d8a64)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffe00083d400)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffe0008925ba)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac2f2)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff818b4d2e)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81940770)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b196)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff81962926)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff819d05b1)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a2e879)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a631)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff8186ec7e)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff818fa260)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914c86)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8191c416)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff8198d371)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819eba69)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a07221)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81905d2e)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff81991900)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5966)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff819cd0f6)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff81a3b031)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a9a429)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab64e1)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81926d5e)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/netlink/af_netlink.c (ffffffff819b43f0)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf446)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff819d6c86)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/unix/af_unix.c (ffffffff81a4880f)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81aa716b)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac2601)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
