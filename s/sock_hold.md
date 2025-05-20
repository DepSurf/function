# Function: <code>sock_hold</code>

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
In security/apparmor/af_unix.c (ffffffff81393f35)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff815ef812)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff817017fc)
Location: include/net/sock.h:586
Inline: True
```
```
In net/core/skbuff.c (ffffffff8170643b)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/netlink/af_netlink.c (ffffffff8174ba84)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/netfilter/nf_queue.c (ffffffff81752668)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff817607fa)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764c95)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8176a2fa)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b338)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81779ecd)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177be8c)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8178433b)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81786415)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
```
In net/ipv4/ping.c (ffffffff817a240d)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff817bd51b)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_peer_get
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dcd9c)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/udp.c (ffffffff817e477b)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f142a)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/packet/af_packet.c (ffffffff81803d4f)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In security/apparmor/af_unix.c (ffffffff813cf728)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff8164e438)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff81768a7c)
Location: include/net/sock.h:579
Inline: True
```
```
In net/core/skbuff.c (ffffffff8176e4cf)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/netlink/af_netlink.c (ffffffff817b8a7c)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff817be798)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ccb1a)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1205)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff817d6d6a)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff817e7b61)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebca5)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff817f1902)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff817f4b26)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81811824)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff8182d458)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184ad3c)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860800)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff8187506b)
Location: include/net/sock.h:579
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/audit.c (ffffffff811353c8)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In security/apparmor/af_unix.c (ffffffff813e6e08)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81680148)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff8179598c)
Location: include/net/sock.h:600
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e852c)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff817ee068)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fc83a)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818010c5)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81806d8a)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81818321)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c616)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81822682)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81825bed)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81842d34)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff8185ef38)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187cbdc)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818927c6)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff818a952b)
Location: include/net/sock.h:600
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In security/apparmor/af_unix.c (ffffffff813f3bed)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff816954de)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff817b3bec)
Location: include/net/sock.h:614
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8180850c)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff8180e198)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181cbd6)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820e31)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8182746f)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff81838823)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183ce8f)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff818432d2)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81847bee)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff818645da)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff818831c6)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a26af)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8dd2)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff818d027f)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/bpf/sockmap.c (ffffffff811b12b4)
Location: include/net/sock.h:618
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8141bdcd)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff8170008b)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff8182ccd1)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff818336ff)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8188736c)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff8188d678)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189bb26)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a03a0)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818a6275)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7f6c)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc5ca)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff818c2c92)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff818c763e)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff818e471e)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81904b96)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81925013)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bc92)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81955193)
Location: include/net/sock.h:618
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/bpf/xskmap.c (ffffffff811cb009)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811cf53a)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In security/apparmor/af_unix.c (ffffffff8144e0ad)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff8173dc75)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff81876ac6)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff8187db6d)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818da9fc)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff818e12a8)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f0098)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f56fa)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818fb2e5)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff818ff086)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819084e1)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cb08)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819120ec)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81918782)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff8191e77f)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff8193aff7)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81959f73)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d3bf)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819950c1)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff819aed8e)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/bpf/xskmap.c (ffffffff811de925)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In security/apparmor/af_unix.c (ffffffff8146b07d)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81761aeb)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff81897296)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff8189e73d)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff818e5db0)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffff819072dc)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff8190de48)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191d988)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a3a)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81929235)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8192d431)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81939b39)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ae48)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819408b6)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81946f52)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff8194d57f)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff8196ace8)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff8198ead3)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b328f)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb9a8)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff819e5786)
Location: include/net/sock.h:645
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/bpf/xskmap.c (ffffffff811f4288)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In security/apparmor/af_unix.c (ffffffff8149807c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff8179f7c6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff818e16e6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff818e8fb5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff81935722)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffff81968596)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff8196fa28)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197fd43)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985446)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8198c157)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81990834)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8199de10)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f1d0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4e0e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff819ab5d2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819b1d3e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff819d19a7)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff819fa552)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a219af)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a44a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81a551c0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a746a9)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (ffffffff814b1fac)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff817c3a56)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff819138d6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff8191b115)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff819684e2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffff8199f036)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff819a6398)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b66e3)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc5b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819c2aa7)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819c44f6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819d48d0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5d80)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbb0e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff819e22a2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819e8ac4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81a0850a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81a311d2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5841f)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70feb)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81a8bdb0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81aab058)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (ffffffff8151136d)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff8188f42c)
Location: include/net/sock.h:689
Inline: True
```
```
In net/core/sock.c (ffffffff819e61b2)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff819ede5d)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff81a3bf20)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81a4e569)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/netlink/af_netlink.c (ffffffff81a7882b)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f72c)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0f56)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6473)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aae06c)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1854)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81abfd89)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac225c)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8c5a)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81ad02a9)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad6e59)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81af7c3e)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81b24a72)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b50908)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a82a)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81b891bf)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ba6fd8)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff81babe86)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81bafc6c)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/token.c (ffffffff81bb1ca9)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm.c (ffffffff81bb22e1)
Location: include/net/sock.h:689
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_schedule_work
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
In security/apparmor/af_unix.c (ffffffff8152e1bd)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff8189d7ae)
Location: include/net/sock.h:696
Inline: True
```
```
In net/core/sock.c (ffffffff819e5379)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff819edafd)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff81a4000c)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81a54549)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/netlink/af_netlink.c (ffffffff81a81b2b)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a9971c)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aab526)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0ac3)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ab82ef)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81abc814)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81acb7f4)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdc8c)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4bfa)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81adc2b9)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae3439)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81b04b1e)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81b33b02)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fbc8)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b792fd)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81b98cbf)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81bb6317)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff81bbe351)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81bc3719)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81bc533d)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In security/apparmor/af_unix.c (ffffffff815344ec)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff8187fffe)
Location: include/net/sock.h:696
Inline: True
```
```
In net/core/sock.c (ffffffff819cb3a0)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff819d59e3)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff81a4e8a1)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81a503b2)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/netlink/af_netlink.c (ffffffff81a6ac17)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a84a2c)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9674b)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bb73)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aa35ed)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7920)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ab69a9)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8ffc)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfc95)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81ac7229)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ace345)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81af0386)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81b21653)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4dead)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67e33)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81b87bc7)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ba6687)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff81badad1)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81bb3d85)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81bb5b79)
Location: include/net/sock.h:696
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In security/apparmor/af_unix.c (ffffffff81592a6c)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff819118ad)
Location: include/net/sock.h:708
Inline: True
```
```
In net/core/sock.c (ffffffff81a7aa25)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff81a85613)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff81b05251)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81b08fb2)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/netlink/af_netlink.c (ffffffff81b2421b)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51bcb)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57245)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81b5f78d)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81b63009)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81b73ae1)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81b763fc)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b913)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81b85a49)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8cd0e)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81bb0390)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81be67f3)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c151bd)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2fac2)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81c540f4)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81c741d7)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff81c7a50e)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81c824c4)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81c849e9)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In security/apparmor/af_unix.c (ffffffff81634861)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81a647c1)
Location: include/net/sock.h:747
Inline: True
```
```
In net/core/sock.c (ffffffff81bee917)
Location: include/net/sock.h:747
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bf83c0)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/skmsg.c (ffffffff81c8d531)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81c8f011)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/netlink/af_netlink.c (ffffffff81cada5c)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdf776)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce51cb)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81cee249)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1cca)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81d0316c)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05bd8)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0ab55)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/udp.c (ffffffff81d1b407)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81d439aa)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81d7dd76)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db09a9)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcceed)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81df3488)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81e17a87)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff81e1ec01)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81e281f2)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81e2ab05)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mctp/af_mctp.c (ffffffff81e37aff)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In security/apparmor/af_unix.c (ffffffff816e9795)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81befa31)
Location: include/net/sock.h:773
Inline: True
```
```
In net/core/sock.c (ffffffff81d9af47)
Location: include/net/sock.h:773
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da7212)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/skmsg.c (ffffffff81e45b95)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81e4a261)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81e6b03c)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fc56)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea83bb)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81eb14a8)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81eb652a)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ec8135)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecad28)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed042a)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/udp.c (ffffffff81ee1dfd)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f0c9ea)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81f4b12e)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f7f949)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e010)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81fc8248)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81feea37)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff81ff55a1)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff8200079d)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff82002c95)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mctp/af_mctp.c (ffffffff82010d6f)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/route.c (ffffffff820130da)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_alloc
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
In security/apparmor/af_unix.c (ffffffff81722f85)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81c47fb5)
Location: include/net/sock.h:775
Inline: True
```
```
In net/core/sock.c (ffffffff81e0990e)
Location: include/net/sock.h:775
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e192c2)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/skmsg.c (ffffffff81ea11ae)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81ea5971)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81ec6b5c)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe4a6)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06c3b)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81f0fb38)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81f1494c)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81f26bcc)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29863)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2f0da)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81f3bc18)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f403b2)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f6c540)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81faaece)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fdfba9)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffea82)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff8202836d)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff8206ab5f)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff82078545)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff8207c947)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff8207dc78)
Location: include/net/sock.h:775
Inline: True
```
```
In net/mctp/af_mctp.c (ffffffff8208d5d5)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/route.c (ffffffff8208fefa)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_alloc
```
```
In net/handshake/request.c (ffffffff820933a8)
Location: include/net/sock.h:775
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
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
In security/apparmor/af_unix.c (ffffffff81761a25)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81cfd935)
Location: include/net/sock.h:758
Inline: True
```
```
In net/core/sock.c (ffffffff81ec62fe)
Location: include/net/sock.h:758
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed6752)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
```
In net/core/skmsg.c (ffffffff81f6388e)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81f68431)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81f89dcc)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2686)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcaf5b)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81fd3d28)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8e77)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81feb5b4)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee3dc)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff462a)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff82001d38)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82005d49)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff82032c90)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff820782be)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff8207e782)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820ad9b9)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd7dc)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff820f7bcd)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff8213e26f)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mptcp/protocol.c (ffffffff8214d727)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff82151e47)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff82152f51)
Location: include/net/sock.h:758
Inline: True
```
```
In net/mctp/af_mctp.c (ffffffff82163a95)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/route.c (ffffffff82166439)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_alloc
```
```
In net/handshake/request.c (ffffffff82169c58)
Location: include/net/sock.h:758
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
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
In security/apparmor/af_unix.c (ffff8000105a97dc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffff8000109de600)
Location: include/net/sock.h:647
Inline: True
```
```
In net/core/sock.c (ffff800010ba98d4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffff800010bb5578)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffff800010c0e3f8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffff800010c4c384)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffff800010c55b94)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffff800010c67c0c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6dac8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffff800010c75884)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffff800010c7b78c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffff800010c87460)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffff800010c88814)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ee34)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffff800010c96e88)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffff800010c9c058)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffff800010cc17d0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffff800010cf0bc4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1dd98)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39448)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffff800010d58690)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffff800010d7e6dc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (c07595fc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (c0ac3554)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (c0cc7e88)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (c0cd263c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (c0d266a0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (c0d5d0c0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (c0d655a4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (c0d76aec)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (c0d7bffc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (c0d83f80)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d87968)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c0d96838)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c0d97c3c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9dd74)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (c0da4a44)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (c0da8744)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (c0dcb8e0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (c0df8a80)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (c0e223c4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (c0e3bf70)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (c0e5812c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (c0e790f0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (c000000000726dd8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (c000000000a9f760)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (c000000000c809f0)
Location: include/net/sock.h:647
Inline: True
```
```
In net/core/skbuff.c (c000000000c8c6b4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (c000000000cf9d44)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (c000000000d4ad48)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (c000000000d563a8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (c000000000d6be74)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72eec)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (c000000000d7d064)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d7f118)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c000000000d93ef8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c000000000d95bb8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d9e4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (c000000000da7808)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (c000000000dae0e4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (c000000000ddcbe0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (c000000000e16b38)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4bfb0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6ca8c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (c000000000e90cc0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (c000000000ebe6ec)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (ffffffe0003f290c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffe000628e80)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffe00073ce16)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffe0007455a2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffe00078add8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffe0007b9e72)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffe0007c0006)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007ce092)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d5a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffe0007d8a56)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007da17e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffe0007e88ae)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9bdc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef0d6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffe0007f5348)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffe0007fb092)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffe000815b52)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffe00083cf70)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe00086092a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008767c4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffe00089064a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffe0008ac100)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (ffffffff814aa58c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81788536)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff818b38d6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff818bb115)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff819084b2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffff8193eea6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff81946208)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81956553)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bacb)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81962917)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81964366)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81974740)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81975bf0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b97e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81982112)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81988934)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff819a82aa)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff819d0862)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7aaf)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a1067b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81a2b440)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a4a3e8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (ffffffff8149afac)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff81767e86)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff8186d826)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff81875055)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff818c22c2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffff818f89a6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff818ffcf8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81910043)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819155bb)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8191c407)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8191de56)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8192e210)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f6b0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193543e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff8193bbd2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819423f4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81961d6a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff8198d622)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b486f)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd43b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff819e8630)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a06fd8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (ffffffff814a662c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff817b88d6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff819048d6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff8190c115)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff819594e2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffff81990036)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff81997398)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c0d23)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c629b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819cd0e7)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819ceb36)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819def10)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819e03c0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e614e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff819ec8e2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819f3104)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81a12b4a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81a3b2e2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6252f)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b0fb)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81a96ff0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ab6298)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/apparmor/af_unix.c (ffffffff814beee0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In drivers/net/tun.c (ffffffff817d1816)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/sock.c (ffffffff81925976)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff8192d245)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/skmsg.c (ffffffff8197b61b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/netlink/af_netlink.c (ffffffff819b2905)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff819ba078)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff819ca703)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfd81)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819d6c77)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819d86c6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819e8bae)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea07e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efe0e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff819f67d2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819fb9cf)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81a1d51a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81a48ac9)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:__unix_insert_socket
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6ea2f)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8793b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/packet/af_packet.c (ffffffff81aa2080)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ac23b8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
</details>
</li>
</ul>

## Differences
