# Function: <code>sock_sndtimeo</code>

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
In net/core/sock.c (ffffffff81702623)
Location: include/net/sock.h:2091
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff8174e505)
Location: include/net/sock.h:2091
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff817690bc)
Location: include/net/sock.h:2091
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff817935fe)
Location: include/net/sock.h:2091
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff817c1427)
Location: include/net/sock.h:2091
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In net/core/sock.c (ffffffff81769853)
Location: include/net/sock.h:2064
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff817ba6a5)
Location: include/net/sock.h:2064
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff817d603a)
Location: include/net/sock.h:2064
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81800e07)
Location: include/net/sock.h:2064
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8182ea19)
Location: include/net/sock.h:2064
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff81796773)
Location: include/net/sock.h:2130
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff817ea045)
Location: include/net/sock.h:2130
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8180604a)
Location: include/net/sock.h:2130
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81831d58)
Location: include/net/sock.h:2130
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81860499)
Location: include/net/sock.h:2130
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff817b4b43)
Location: include/net/sock.h:2154
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81809d15)
Location: include/net/sock.h:2154
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff818264dc)
Location: include/net/sock.h:2154
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff818532c7)
Location: include/net/sock.h:2154
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81884b9f)
Location: include/net/sock.h:2154
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff8182cd86)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81888c75)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff818a45eb)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff818d311d)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81905d79)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In kernel/bpf/sockmap.c (ffffffff811cfa69)
Location: include/net/sock.h:2175
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
```
In net/core/sock.c (ffffffff81876b7b)
Location: include/net/sock.h:2175
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff818dc6c3)
Location: include/net/sock.h:2175
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff818fa35e)
Location: include/net/sock.h:2175
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff819294fc)
Location: include/net/sock.h:2175
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8195c84e)
Location: include/net/sock.h:2175
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff8189734b)
Location: include/net/sock.h:2261
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff819090a3)
Location: include/net/sock.h:2261
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8192828e)
Location: include/net/sock.h:2261
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff819586ac)
Location: include/net/sock.h:2261
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff819779c6)
Location: include/net/sock.h:2261
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81991878)
Location: include/net/sock.h:2261
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff818e179b)
Location: include/net/sock.h:2267
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff8196a3f6)
Location: include/net/sock.h:2267
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8198b1f4)
Location: include/net/sock.h:2267
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff819bd1ee)
Location: include/net/sock.h:2267
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e14c5)
Location: include/net/sock.h:2267
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819fcaa6)
Location: include/net/sock.h:2267
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81a567b6)
Location: include/net/sock.h:2267
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff8191398b)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff819a0e66)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819c1a77)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff819f3dfe)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18285)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a33736)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81a8dc96)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff819e6045)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81a7a676)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81aad2a4)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81ae3454)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b095ef)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b22e66)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b28a4c)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81b88652)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff81bacee1)
Location: include/net/sock.h:2338
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffffffff819e5415)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81a834e6)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81ab4674)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81af0844)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17769)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b31856)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b36c93)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81b9812f)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff81bbf911)
Location: include/net/sock.h:2359
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffffffff819cb47a)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81a6c5b6)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81a9f7d4)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81adbeb6)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05347)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b1f586)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b24844)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81b870d8)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff81baf4d9)
Location: include/net/sock.h:2395
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffffffff81a7ab0a)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81b25c06)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81b5b584)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81b9b0e5)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc7c51)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81be41a6)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81be9884)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81c53a49)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff81c7d1b1)
Location: include/net/sock.h:2454
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffffffff81beea2b)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81cae7be)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81cea725)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81d2cf3a)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d213)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81d7b632)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81d8235d)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81df7254)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff81e227f0)
Location: include/net/sock.h:2577
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffffffff81d9b07b)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81e6bdfe)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81eae621)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81ef4a8c)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f28013)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81f486c2)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81f4f8a0)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81fcb8c0)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff81ffb4f2)
Location: include/net/sock.h:2623
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffffffff81e0a26b)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81ec7e5e)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81f0c6ba)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/af_inet.c (ffffffff81f54460)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87497)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81fa8532)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81faf193)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff8202cb67)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff8207787a)
Location: include/net/sock.h:2611
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffffffff81ec6c5b)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81f8b26e)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81fd079f)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/af_inet.c (ffffffff8201a693)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eb17)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff82075822)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8207c735)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff820fc5fe)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/mptcp/protocol.c (ffffffff8214c8d9)
Location: include/net/sock.h:2601
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/sock.c (ffff800010bab3e0)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffff800010c4f578)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffff800010c748e4)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffff800010cab344)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4084)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffff800010cf3700)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffff800010d594f0)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (c0cc9fbc)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (c0d5f6e8)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (c0d82f40)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (c0db7d80)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (c0dddf5c)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (c0dfa978)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (c0e5b21c)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (c000000000c81c94)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (c000000000d4ddf4)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (c000000000d7bbc8)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (c000000000dbfaf8)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (c000000000df3548)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (c000000000e19714)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (c000000000e951fc)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffe00073ed1c)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffe0007bb1d4)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffe0007d7cf4)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffe000804ce6)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824e78)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffe000840090)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffe000891746)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff818b398b)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81940cd6)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819618e7)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81993b9e)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7915)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819d2dc6)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81a2d326)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff8186d8db)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff818fa7c6)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8191b3d7)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff8194d65e)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974705)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8198fb86)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff819ea516)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff8190498b)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff81991e66)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819cc0b7)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff819fe43e)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22395)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a3d846)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81a98ed6)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff81925a2b)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/netlink/af_netlink.c (ffffffff819b4956)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819d5c47)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/af_inet.c (ffffffff81a087ce)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2d769)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a492f6)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/packet/af_packet.c (ffffffff81aa5570)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
