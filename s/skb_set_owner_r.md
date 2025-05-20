# Function: <code>skb_set_owner_r</code>

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
In net/core/sock.c (ffffffff81702ef0)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8176cd19)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782ae1)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0bb8)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/packet/af_packet.c (ffffffff81806fb3)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817683b3)
Location: include/net/sock.h:1932
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff817da615)
Location: include/net/sock.h:1932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efc7c)
Location: include/net/sock.h:1932
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f796)
Location: include/net/sock.h:1932
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8187a1fd)
Location: include/net/sock.h:1932
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81874c90-ffffffff81874cee: skb_set_owner_r (STB_LOCAL)
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
In net/core/sock.c (ffffffff817953f3)
Location: include/net/sock.h:1994
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81808fa7)
Location: include/net/sock.h:1994
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8182068c)
Location: include/net/sock.h:1994
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818916de)
Location: include/net/sock.h:1994
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818ab337)
Location: include/net/sock.h:1994
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff817b39af)
Location: include/net/sock.h:2018
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81829268)
Location: include/net/sock.h:2018
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840b9c)
Location: include/net/sock.h:2018
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7d1d)
Location: include/net/sock.h:2018
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818d45fb)
Location: include/net/sock.h:2018
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8182d01f)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff818ae2a2)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c030c)
Location: include/net/sock.h:2032
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ab8b)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8195905f)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81876e18)
Location: include/net/sock.h:2035
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81903951)
Location: include/net/sock.h:2035
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e5d)
Location: include/net/sock.h:2035
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994215)
Location: include/net/sock.h:2035
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819b2dc0)
Location: include/net/sock.h:2035
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff818975b8)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81931b0e)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944604)
Location: include/net/sock.h:2125
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab37)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819e9d1e)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff818e19fb)
Location: include/net/sock.h:2131
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8199520b)
Location: include/net/sock.h:2131
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8bf4)
Location: include/net/sock.h:2131
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39788)
Location: include/net/sock.h:2131
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a582f2)
Location: include/net/sock.h:2131
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81913beb)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819cbd5b)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df894)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70318)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a90a87)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff819e5cfd)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1fd7)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd36)
Location: include/net/sock.h:2190
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b22689)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69f2b)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8bcbe)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab64c)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff819e57cd)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81a3f5fb)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81abcf9b)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d36)
Location: include/net/sock.h:2209
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31089)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78a0b)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b9b134)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbd321)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In net/core/sock.c (ffffffff819cb8dd)
Location: include/net/sock.h:2229
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81a4ea5a)
Location: include/net/sock.h:2229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7de7)
Location: include/net/sock.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3da5)
Location: include/net/sock.h:2229
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1edb9)
Location: include/net/sock.h:2229
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d15)
Location: include/net/sock.h:2229
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8ab1e)
Location: include/net/sock.h:2229
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bacada)
Location: include/net/sock.h:2229
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In net/core/sock.c (ffffffff81a7af6d)
Location: include/net/sock.h:2269
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81b075c3)
Location: include/net/sock.h:2269
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/ipv4/tcp_input.c (ffffffff81b641de)
Location: include/net/sock.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82435)
Location: include/net/sock.h:2269
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3d9f)
Location: include/net/sock.h:2269
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e8d2)
Location: include/net/sock.h:2269
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81c56c41)
Location: include/net/sock.h:2269
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c79476)
Location: include/net/sock.h:2269
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In net/core/sock.c (ffffffff81bee5cc)
Location: include/net/sock.h:2387
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81c8cd31)
Location: include/net/sock.h:2387
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/ipv4/tcp_input.c (ffffffff81cf307b)
Location: include/net/sock.h:2387
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12935)
Location: include/net/sock.h:2387
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7ab7b)
Location: include/net/sock.h:2387
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb520)
Location: include/net/sock.h:2387
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81df6034)
Location: include/net/sock.h:2387
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81d9e08c)
Location: include/net/sock.h:2422
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81e47bae)
Location: include/net/sock.h:2422
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/ipv4/tcp_input.c (ffffffff81eb76ab)
Location: include/net/sock.h:2422
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8775)
Location: include/net/sock.h:2422
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81f47b4b)
Location: include/net/sock.h:2422
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c60c)
Location: include/net/sock.h:2422
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81fca59e)
Location: include/net/sock.h:2422
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81e0c900)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81ea332c)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/ipv4/tcp_input.c (ffffffff81f15d8b)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37885)
Location: include/net/sock.h:2410
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa764b)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd05c)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8202b3d2)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81ec9270)
Location: include/net/sock.h:2400
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81f6566e)
Location: include/net/sock.h:2400
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
```
In net/ipv4/tcp_input.c (ffffffff81fda162)
Location: include/net/sock.h:2400
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd955)
Location: include/net/sock.h:2400
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff820748fb)
Location: include/net/sock.h:2400
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc171)
Location: include/net/sock.h:2400
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff820faebd)
Location: include/net/sock.h:2400
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffff800010bacfa8)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffff800010c7e9a4)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93418)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38c50)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffff800010d5dea8)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (c0cca2f8)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (c0d8d9c8)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (c0da1c10)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c0e3affc)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (c0e5cc94)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (c000000000c823c8)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (c000000000d88d6c)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3668)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b63c)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (c000000000e96f7c)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffe00073efd0)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0c94)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f294c)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875e82)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffe000893ed8)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff818b3beb)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8196bbcb)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f704)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f9a8)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a30117)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8186db3b)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819256bb)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819391c4)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc768)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819ed307)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81904beb)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819d639b)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9ed4)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a428)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a9bcc7)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81925c8b)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819dffbb)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d04)
Location: include/net/sock.h:2141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86c68)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81aa649b)
Location: include/net/sock.h:2141
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
