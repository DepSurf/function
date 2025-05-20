# Function: <code>lock_sock_nested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700fe0)
Location: net/core/sock.c:2431
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/skbuff.c:skb_socket_splice
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/filter.c:sk_get_filter
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81700fe0-ffffffff81701041: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767b60)
Location: net/core/sock.c:2504
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/skbuff.c:skb_socket_splice
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81767b60-ffffffff81767bc6: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794b80)
Location: net/core/sock.c:2531
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81794b80-ffffffff81794be6: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b2d70)
Location: net/core/sock.c:2695
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff817b2d70-ffffffff817b2dd6: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182b060)
Location: net/core/sock.c:2756
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_tx_work
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/skbuff.c:skb_send_sock
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff8182b060-ffffffff8182b0c6: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81877730)
Location: net/core/sock.c:2831
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:sock_hash_update_elem
  - kernel/bpf/sockmap.c:sock_map_update_elem
  - kernel/bpf/sockmap.c:smap_tx_work
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_tcp_close
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/skbuff.c:skb_send_sock
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff81877730-ffffffff81877796: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897d60)
Location: net/core/sock.c:2780
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff81897d60-ffffffff81897dc6: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e2280)
Location: net/core/sock.c:2923
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff818e2280-ffffffff818e22e1: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914430)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff81914430-ffffffff81914491: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5780)
Location: net/core/sock.c:3067
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:tun_attach_filter
  - drivers/net/tun.c:tun_attach_filter
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_getsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm.c:pm_worker
```
**Symbols:**

```
ffffffff819e5780-ffffffff819e57e1: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e7b90)
Location: net/core/sock.c:3046
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:tun_attach_filter
  - drivers/net/tun.c:tun_attach_filter
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp6_release
  - net/mptcp/protocol.c:mptcp_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_getsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_check_fastclose
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff819e7b90-ffffffff819e7bf1: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cdfb0)
Location: net/core/sock.c:3069
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_msg_wait_data
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff819cdb60-ffffffff819cdbc1: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7dad7)
Location: net/core/sock.c:3202
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_fasync
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
**Symbols:**

```
ffffffff81a7d370-ffffffff81a7d3be: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf1177)
Location: net/core/sock.c:3388
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_fasync
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mctp/af_mctp.c:mctp_bind
```
**Symbols:**

```
ffffffff81bf09b0-ffffffff81bf0a06: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9d937)
Location: net/core/sock.c:3477
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_fasync
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mctp/af_mctp.c:mctp_bind
```
**Symbols:**

```
ffffffff81d9cf80-ffffffff81d9cfd6: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0c1ae)
Location: net/core/sock.c:3510
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_fasync
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_eof
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_splice_eof
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_splice_eof
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mctp/af_mctp.c:mctp_bind
```
**Symbols:**

```
ffffffff81e0b7d0-ffffffff81e0b826: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec8b50)
Location: net/core/sock.c:3520
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_fasync
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_eof
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_splice_eof
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind_sk
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_pre_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind_sk
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_splice_eof
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_pre_connect
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_pre_connect
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_v6
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
  - net/mctp/af_mctp.c:mctp_bind
```
**Symbols:**

```
ffffffff81ec81c0-ffffffff81ec8216: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baba78)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffff800010baba78-ffff800010babb3c: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc81bc)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
c0cc81bc-c0cc822c: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7f160)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
c000000000c7f160-c000000000c7f230: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073f3a8)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffe00073f3a8-ffffffe00073f448: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4430)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff818b4430-ffffffff818b4491: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186e380)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_open
  - drivers/net/vxlan.c:vxlan_open
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff8186e380-ffffffff8186e3e1: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905430)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
  - net/netfilter/nf_conntrack_proto.c:getorigdst
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff81905430-ffffffff81905491: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lock_sock_nested(struct sock *sk, int subclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81924070)
Location: net/core/sock.c:2938
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
  - net/socket.c:sock_fasync
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/filter.c:sk_get_filter
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/datagram.c:ip4_datagram_connect
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/devinet.c:ip_mc_config
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrconf.c:ipv6_mc_config
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/strparser/strparser.c:strp_sock_lock
```
**Symbols:**

```
ffffffff81924070-ffffffff819240ca: lock_sock_nested (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
