# Function: <code>sk_mem_charge</code>

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
In net/core/sock.c (ffffffff81702f29)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff8174a3f6)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81765dca)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176bdd2)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817744af)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782b1a)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0be8)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/packet/af_packet.c (ffffffff81806fe6)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff817683ec)
Location: include/net/sock.h:1323
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff817b7316)
Location: include/net/sock.h:1323
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff817d630c)
Location: include/net/sock.h:1323
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff817da645)
Location: include/net/sock.h:1323
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff817e135f)
Location: include/net/sock.h:1323
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efca9)
Location: include/net/sock.h:1323
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f7c2)
Location: include/net/sock.h:1323
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8187a22a)
Location: include/net/sock.h:1323
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8179542c)
Location: include/net/sock.h:1379
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff817e6db6)
Location: include/net/sock.h:1379
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff818062f2)
Location: include/net/sock.h:1379
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81808fd7)
Location: include/net/sock.h:1379
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8181182f)
Location: include/net/sock.h:1379
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818206b9)
Location: include/net/sock.h:1379
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189170a)
Location: include/net/sock.h:1379
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818ab36b)
Location: include/net/sock.h:1379
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
In net/core/sock.c (ffffffff817b39e8)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/netlink/af_netlink.c (ffffffff81806769)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81826ead)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8182929c)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81831a9f)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840bc9)
Location: include/net/sock.h:1382
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7d49)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff818d4632)
Location: include/net/sock.h:1382
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
In net/core/sock.c (ffffffff8182d05b)
Location: include/net/sock.h:1386
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff8183945c)
Location: include/net/sock.h:1386
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/netlink/af_netlink.c (ffffffff81885439)
Location: include/net/sock.h:1386
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff818a4de9)
Location: include/net/sock.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff818ae2d9)
Location: include/net/sock.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff818b47fe)
Location: include/net/sock.h:1386
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c033c)
Location: include/net/sock.h:1386
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193abba)
Location: include/net/sock.h:1386
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81959099)
Location: include/net/sock.h:1386
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
In kernel/bpf/sockmap.c (ffffffff811ccdd4)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_tx_work
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In net/core/sock.c (ffffffff818774b1)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81883b96)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/netlink/af_netlink.c (ffffffff818d8c63)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff818fa91f)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81903994)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81909e48)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e98)
Location: include/net/sock.h:1401
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199424f)
Location: include/net/sock.h:1401
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819b2e02)
Location: include/net/sock.h:1401
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
In net/core/sock.c (ffffffff818975f7)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff818a452d)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff818dce2a)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818e6456)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81905453)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819287ef)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81931b51)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819380f9)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194463f)
Location: include/net/sock.h:1439
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff819777c1)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab71)
Location: include/net/sock.h:1439
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819e9d60)
Location: include/net/sock.h:1439
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
In net/core/sock.c (ffffffff818e1a32)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff818efb8b)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff8192b069)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81935ddd)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8196686f)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff8198b759)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8199524c)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff8199b553)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8c2f)
Location: include/net/sock.h:1442
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e12e9)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a397c5)
Location: include/net/sock.h:1442
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a5833e)
Location: include/net/sock.h:1442
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
In net/core/sock.c (ffffffff81913c22)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81921baf)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff8195d3da)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81968afd)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8199d263)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819c1faa)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819cbd9c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff819d1f7b)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df8cf)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a186b5)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70355)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a90acd)
Location: include/net/sock.h:1452
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
In net/core/sock.c (ffffffff819e5d34)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff819f54a1)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81a319fc)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3bcc9)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a764a3)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81aad75f)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81ab2018)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81abae33)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accd71)
Location: include/net/sock.h:1500
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b093e3)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/xfrm/espintcp.c (ffffffff81b226c6)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69f68)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8bd02)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bab70f)
Location: include/net/sock.h:1500
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff819e5806)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff819f4f8c)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81a33d44)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3f639)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a7f213)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81ab4ad6)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81abcfdc)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81ac61d3)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8d71)
Location: include/net/sock.h:1516
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17bfd)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/xfrm/espintcp.c (ffffffff81b310c6)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78a48)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b9b175)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bbd361)
Location: include/net/sock.h:1516
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In net/core/sock.c (ffffffff819cb916)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff819db115)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81a1afcd)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a4eaa5)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a681f3)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81a9fc82)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7e28)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81ab13e3)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3de0)
Location: include/net/sock.h:1532
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b057ce)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/xfrm/espintcp.c (ffffffff81b1edf6)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d52)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81b8ab6e)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bacb1a)
Location: include/net/sock.h:1532
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In net/core/sock.c (ffffffff81a7afa6)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81a8b7b9)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81ace501)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81b0760b)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81b21713)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81b5ba3b)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81b64231)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81b6e2f3)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82470)
Location: include/net/sock.h:1542
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc832b)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/xfrm/espintcp.c (ffffffff81be3ddf)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e90f)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81c56c89)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c794b6)
Location: include/net/sock.h:1542
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_try_coalesce
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
In net/core/sock.c (ffffffff81bee60b)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81c00e92)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81c49f1f)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81c8cd74)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ca9cd3)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81cea9f6)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81cf30c0)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_output.c (ffffffff81cfd773)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12970)
Location: include/net/sock.h:1648
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dbc6)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
```
In net/xfrm/espintcp.c (ffffffff81d7abba)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb55a)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81df6071)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e1f0fc)
Location: include/net/sock.h:1648
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In io_uring/net.c (ffffffff81795ddd)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In net/core/sock.c (ffffffff81d9e0cb)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81db023a)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81dffb93)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81e47bf1)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81e66cd3)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81eaebae)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81eb76f0)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_output.c (ffffffff81ec2383)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed87b0)
Location: include/net/sock.h:1681
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27876)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
```
In net/xfrm/espintcp.c (ffffffff81f47b8a)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c646)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81fca5db)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff81ff5cb5)
Location: include/net/sock.h:1681
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In io_uring/net.c (ffffffff817d6a72)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In net/core/sock.c (ffffffff81e0c93f)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81e20556)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e7158f)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea336f)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ec2a93)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81f0cc56)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81f15dd0)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_output.c (ffffffff81f20993)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f378c0)
Location: include/net/sock.h:1672
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87063)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
```
In net/xfrm/espintcp.c (ffffffff81fa768a)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd096)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff8202b40f)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82071d91)
Location: include/net/sock.h:1672
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In io_uring/net.c (ffffffff8181ac42)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In net/core/sock.c (ffffffff81ec92af)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81ede42a)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81f30c80)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f656b1)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f85de3)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81fd0d46)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81fda1ac)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5093)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd990)
Location: include/net/sock.h:1647
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204e6a3)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
```
In net/xfrm/espintcp.c (ffffffff8207493a)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc1ab)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff820faefa)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/mptcp/protocol.c (ffffffff82145fb4)
Location: include/net/sock.h:1647
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/sock.c (ffff800010bacfec)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffff800010bbc210)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffff800010c00e24)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffff800010c0f95c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffff800010c4b92c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffff800010c74cc0)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffff800010c7e9e8)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffff800010c84b44)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93460)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3ec0)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38c8c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffff800010d5deec)
Location: include/net/sock.h:1452
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
In net/core/sock.c (c0cca340)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (c0cd8688)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (c0d1995c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c0d262a4)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (c0d5b694)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (c0d8344c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c0d8da10)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (c0d93e20)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (c0da1c60)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (c0ddddac)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (c0e3b04c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (c0e5cce0)
Location: include/net/sock.h:1452
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
In net/core/sock.c (c000000000c82410)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (c000000000c95450)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (c000000000ce8570)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c000000000cfa790)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (c000000000d48b50)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (c000000000d7c278)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (c000000000d88db4)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (c000000000d909d8)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (c000000000da36b4)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (c000000000df3270)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b688)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (c000000000e96fc4)
Location: include/net/sock.h:1452
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
In net/core/sock.c (ffffffe00073effa)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffe00074af96)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffe00077ee26)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffe00078b488)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffe0007b7c0c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffe0007d8134)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0cbc)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffe0007e64e4)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f296e)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824cde)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875ea8)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffe000893f00)
Location: include/net/sock.h:1452
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
In net/core/sock.c (ffffffff818b3c22)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff818c1baf)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff818fd3aa)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81908acd)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8193d0d3)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff81961e1a)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8196bc0c)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff81971deb)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f73f)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7d45)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f9e5)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a3015d)
Location: include/net/sock.h:1452
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
In net/core/sock.c (ffffffff8186db72)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff8187baef)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff818b71da)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818c28dd)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818f6bd3)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff8191b90a)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819256fc)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff8192b8bb)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819391ff)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974b35)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc7a5)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff819ed34d)
Location: include/net/sock.h:1452
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
In net/core/sock.c (ffffffff81904c22)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81912baf)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff8194e3da)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81959afd)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8198e263)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819cc5ea)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819d63dc)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff819dc5bb)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9f0f)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a227c5)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a465)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81a9bd0d)
Location: include/net/sock.h:1452
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
In net/core/sock.c (ffffffff81925cc2)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/datagram.c (ffffffff81933d2f)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff8196fdaa)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8197bd1d)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819b0b03)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
```
```
In net/ipv4/tcp.c (ffffffff819d617a)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819dfffc)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/tcp_output.c (ffffffff819e623b)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3d3f)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dba6)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86ca5)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/packet/af_packet.c (ffffffff81aa64d8)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences
