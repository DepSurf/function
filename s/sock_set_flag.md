# Function: <code>sock_set_flag</code>

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
In drivers/net/tun.c (ffffffff815ede5d)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffffffff816fb9e2)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81700709)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/core/sock.c:sk_set_memalloc
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff8174df23)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762dca)
Location: include/net/sock.h:751
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817648c4)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff817658f7)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b10d)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81775700)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c967)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/icmp.c (ffffffff8178df23)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/unix/af_unix.c (ffffffff817bfdaa)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81805a5b)
Location: include/net/sock.h:751
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
In drivers/net/tun.c (ffffffff8164ce1d)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffffffff81762442)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8176ab4a)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff817ba0d6)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf176)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0fe7)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff817d49c3)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff817debbd)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff817e665e)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea26c)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff817f496c)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff817fb4fa)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/unix/af_unix.c (ffffffff8182d1ba)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff8187661f)
Location: include/net/sock.h:753
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
In drivers/net/tun.c (ffffffff8167eb5d)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffffffff8178f472)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81797c6a)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff817e9af8)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fef90)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800ea7)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81804717)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8180ef9b)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81816d9e)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818aa9)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81825a3c)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff8182c3aa)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_sk_init
```
```
In net/unix/af_unix.c (ffffffff8185ec9a)
Location: include/net/sock.h:774
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818aab9a)
Location: include/net/sock.h:774
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
In drivers/net/tun.c (ffffffff81693d34)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffffffff817ad3f2)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff817b582a)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81809729)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f238)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820c07)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81824987)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8182eeeb)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81837023)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839288)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff81847ad9)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff8184d95a)
Location: include/net/sock.h:788
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81882f2c)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818d1638)
Location: include/net/sock.h:788
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
In drivers/net/tun.c (ffffffff816fdb64)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffffffff81825382)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8182dcf3)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff8188867c)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e1a8)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fbfd)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff818a65e5)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff818adf0b)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff818b66bf)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba54c)
Location: include/net/sock.h:788
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c7539)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff818cd69c)
Location: include/net/sock.h:788
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819048f8)
Location: include/net/sock.h:788
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81956591)
Location: include/net/sock.h:788
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
In drivers/net/tun.c (ffffffff8173bc76)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffffffff8186f332)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818780c3)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff818dc09e)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2bcb)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4c5d)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff818fb685)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8190358b)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8190beff)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190efdc)
Location: include/net/sock.h:795
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191e731)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81923a78)
Location: include/net/sock.h:795
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8195a127)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff8199fe37)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819b19cf)
Location: include/net/sock.h:795
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff819cbff6)
Location: include/net/sock.h:795
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
In drivers/net/tun.c (ffffffff8175f5b0)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8188f7f2)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818985a3)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81908a6b)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8192063b)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192215d)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819295d5)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819316db)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8193a1dc)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d40c)
Location: include/net/sock.h:823
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194d531)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81952868)
Location: include/net/sock.h:823
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198ec87)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff819d66ce)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819e8daf)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a050fe)
Location: include/net/sock.h:823
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffff8179cde6)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff818d984e)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818e2b56)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81969e98)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982f70)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198523e)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8198c505)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81994e0b)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199e484)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a183d)
Location: include/net/sock.h:826
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b1cfd)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff819b7121)
Location: include/net/sock.h:826
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819fa2a9)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81a45b41)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a590e9)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a7465c)
Location: include/net/sock.h:826
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffff817c0886)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8190b82e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81914d36)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff819a0908)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b97d9)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb32e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819c2e55)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819cb95b)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819d4f71)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d84ed)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e8a83)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff819ede21)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a30f29)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c731)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a8f1f9)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aaafec)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffff8188a966)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffffffff819dda1e)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e6cd6)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81a7a088)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa432b)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa622e)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aae569)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ab890b)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac198b)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4b7e)
Location: include/net/sock.h:873
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad6d3a)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81adbc01)
Location: include/net/sock.h:873
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b25668)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81b771c4)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b8b5ef)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba6f6c)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ba9fb7)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
```
```
In net/mptcp/subflow.c (ffffffff81baef28)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In drivers/net/tun.c (ffffffff81898b66)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In net/socket.c (ffffffff819dd40e)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e6506)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/filter.c (ffffffff81a2ae1e)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a82ee8)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae96b)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab087e)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81ab832d)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ac3c7b)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad050e)
Location: include/net/sock.h:879
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae331a)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81ae85f1)
Location: include/net/sock.h:879
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b34078)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81b85fa0)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b9a5b9)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb62ac)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bb9df5)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bc1ac1)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In drivers/net/tun.c (ffffffff8187b2a6)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In net/socket.c (ffffffff819c3662)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819cbf36)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/filter.c (ffffffff81a11ffb)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a6bfb8)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99aeb)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ba5e)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aa3627)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81aaed8b)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb64e)
Location: include/net/sock.h:879
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81aca127)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81ad3881)
Location: include/net/sock.h:879
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b21bb8)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/udp.c (ffffffff81b54c45)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81b74c50)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b89528)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba661c)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ba91d5)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bb240a)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mptcp/sockopt.c (ffffffff81bbc069)
Location: include/net/sock.h:879
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In drivers/net/tun.c (ffffffff8190caa6)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In net/socket.c (ffffffff81a72ef2)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81a7b596)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/filter.c (ffffffff81acd36c)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81b255c6)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54f58)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b5707e)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81b5f7c7)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81b6ba6b)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78863)
Location: include/net/sock.h:891
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b889a7)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81b92525)
Location: include/net/sock.h:891
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be70e8)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/udp.c (ffffffff81c1b505)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81c3f55c)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81c55638)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c7416c)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c78e35)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81c8066e)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mptcp/sockopt.c (ffffffff81c8bc09)
Location: include/net/sock.h:891
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In drivers/net/tun.c (ffffffff81a61384)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In net/socket.c (ffffffff81be5773)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81befe83)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/filter.c (ffffffff81c4ac7f)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81cae0ed)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2b20)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4fed)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81cee27f)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81cfabdb)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff834cc2dd)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81d15976)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81d19e67)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff834cc958)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81d439d4)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81d7e719)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/udp.c (ffffffff81db7c34)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81ddda4c)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81df53c8)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e17a1c)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e1d9e5)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81e26318)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mptcp/sockopt.c (ffffffff81e3328c)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mctp/af_mctp.c (ffffffff81e37a39)
Location: include/net/sock.h:931
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sock_set_flag(struct sock *sk, enum sock_flags flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bec6cd)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In net/socket.c (ffffffff81d92e33)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81d9c423)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
Direct callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81e6b6bd)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4009)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7c3d)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81eb14df)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ebf71b)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83f0eb9d)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81edc986)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ee0a47)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff83f0f3f1)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81f0ca14)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81f4b815)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/udp.c (ffffffff81f87c54)
Location: include/net/sock.h:969
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fafbfc)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81fc7d48)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee9cc)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ffab45)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81fff51d)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
```
In net/mptcp/sockopt.c (ffffffff8200c98c)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mctp/af_mctp.c (ffffffff82010c94)
Location: include/net/sock.h:969
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff81d98730-ffffffff81d98740: sock_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sock_set_flag(struct sock *sk, enum sock_flags flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c44ab0)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In net/socket.c (ffffffff81e0122e)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81e0ac73)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
Direct callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81ec76fd)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02859)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0647d)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81f0fb6f)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81f1dbf4)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff837351ad)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81f3bc6d)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3fcc7)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff83735a01)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81f6c5a1)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81fab5bc)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/udp.c (ffffffff81fe8104)
Location: include/net/sock.h:971
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff82010254)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff82028cec)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206aafc)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82072b8c)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff8207b638)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
```
In net/mptcp/sockopt.c (ffffffff820892e1)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mctp/af_mctp.c (ffffffff8208d504)
Location: include/net/sock.h:971
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff81e06da0-ffffffff81e06db0: sock_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sock_set_flag(struct sock *sk, enum sock_flags flag);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfa610)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In net/socket.c (ffffffff81ebd92e)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81ec7663)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81f8aa3d)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc6cae)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca76d)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81fd3d5f)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81fe22c4)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8396976d)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff82001d8d)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82005987)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff8396a071)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff82032cf1)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff820789ac)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/udp.c (ffffffff820b6344)
Location: include/net/sock.h:942
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820df1e4)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff820f872c)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e20c)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214b8a0)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff82150c09)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
```
In net/mptcp/sockopt.c (ffffffff8215f061)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mctp/af_mctp.c (ffffffff821639c4)
Location: include/net/sock.h:942
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
**Symbols:**

```
ffffffff81ec3690-ffffffff81ec36a0: sock_set_flag (STB_LOCAL)
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
In drivers/net/tun.c (ffff8000109dad84)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/socket.c (ffff800010ba0dc4)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffff800010bada70)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffff800010c4f070)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6af64)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c92c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffff800010c75c5c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffff800010c7e55c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c87be8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8b044)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9bfc8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffff800010ca39ac)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (ffff800010cf1184)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffff800010d467f4)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffff800010d5c428)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7e6ac)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (c0ac1ca8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (c0cc30f8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c0ccb5f8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (c0d5f1d0)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (c0d7a02c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (c0d7be30)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c0d842f4)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (c0d8d580)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d96f38)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (c0d9b2e8)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (c0da86f0)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (c0db0650)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (c0df823c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (c0e48f60)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (c0e5c444)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e790b0)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (c000000000a9d2e8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (c000000000c74d94)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c000000000c8339c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (c000000000d4d774)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (c000000000d70334)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72c20)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c000000000d7d504)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (c000000000d887cc)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d948d0)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (c000000000d99ca8)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (c000000000dae03c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (c000000000db7298)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (c000000000e16130)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (c000000000e7c518)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (c000000000e97f00)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebe6b8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffe000625cde)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffe000738b28)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffe00073fc86)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffe0007bad18)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0c54)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2284)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffe0007d8e48)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0914)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8eea)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ecc86)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fb022)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffe0007ff7b6)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (ffffffe00083d40e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffe0008813ce)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffe0008925c8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac092)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffff81785356)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff818ab82e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818b4d36)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81940778)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959649)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b19e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81962cc5)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8196b7cb)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81974de1)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197835d)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819888f3)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff8198dbc1)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819d05b9)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bdc1)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a2e889)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a37c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffff81764ca6)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8186577e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8186ec86)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff818fa268)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81913139)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914c8e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8191c7b5)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819252bb)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8192e8a1)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931e1d)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819423b3)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81947681)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198d379)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff819d8b81)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819eba79)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a06f6c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffff817b5706)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff818fc82e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81905d36)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81991908)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3e19)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c596e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819cd495)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819d5f9b)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819df5b1)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2b2d)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f30c3)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff819f8461)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3b039)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81a86841)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a9a439)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab622c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In drivers/net/tun.c (ffffffff817cf8e6)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8191d82e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81926d66)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff819b43f8)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd86f)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf44e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819d7025)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819dfb9b)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e9261)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ecc4d)
Location: include/net/sock.h:831
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fb98e)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81a02781)
Location: include/net/sock.h:831
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a48817)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81a93401)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81aa717b)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac234c)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
