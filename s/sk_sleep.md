# Function: <code>sk_sleep</code>

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
In drivers/net/tun.c (ffffffff815eda5f)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff817023a6)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8170c8e1)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/stream.c (ffffffff8170deb6)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764fcb)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81768c61)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d245)
Location: include/net/sock.h:1657
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81793654)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff817bdc18)
Location: include/net/sock.h:1657
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_connect
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
In drivers/net/tun.c (ffffffff8164cb95)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff817695e6)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81775331)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81775bce)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d154b)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff817d55c1)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea8ef)
Location: include/net/sock.h:1618
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81800e58)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8182b118)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff8167e8c6)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff817964f9)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817a2621)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817a2ca6)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81801416)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8180553b)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ae8f)
Location: include/net/sock.h:1674
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81831d9a)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8185cb48)
Location: include/net/sock.h:1674
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff81693abb)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff817b46b9)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817c0131)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817c0e03)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818218e8)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8182501b)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b717)
Location: include/net/sock.h:1678
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81853309)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff818812c8)
Location: include/net/sock.h:1678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff816fd8eb)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff8182c919)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81839b41)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8183a823)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a066c)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818a398b)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818d3164)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81902458)
Location: include/net/sock.h:1692
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/bpf/sockmap.c (ffffffff811cec0a)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
```
```
In drivers/net/tun.c (ffffffff8173c978)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81877804)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81884289)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81884f9c)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f543c)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818f878e)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/af_inet.c (ffffffff81929580)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81959db0)
Location: include/net/sock.h:1703
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff81760e88)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81898924)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818a406e)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818a559e)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922d7c)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81958730)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977dfc)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8199081c)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff8179eb1d)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff818e2eb8)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818ef382)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818f08c1)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985733)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff819bd26b)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e18fb)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819fbf09)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff817c25ad)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81915098)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81921332)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81922813)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc426)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff819f3e7b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1890b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a32b99)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff8188d088)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff819e8408)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_wait_for_wmem
```
```
In net/core/datagram.c (ffffffff819f4fc6)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f63b5)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa588c)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/af_inet.c (ffffffff81ae3300)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b086fa)
Location: include/net/sock.h:1859
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b2479c)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/mptcp/protocol.c (ffffffff81babcf1)
Location: include/net/sock.h:1859
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
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
In drivers/net/tun.c (ffffffff8189b302)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff819e80a8)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_wait_for_wmem
```
```
In net/core/datagram.c (ffffffff819f49e6)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f5ecc)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafefc)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/af_inet.c (ffffffff81af06e0)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b1689a)
Location: include/net/sock.h:1871
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b331fc)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/mptcp/protocol.c (ffffffff81bbc381)
Location: include/net/sock.h:1871
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
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
In drivers/net/tun.c (ffffffff8187df92)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff819ce1d8)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819dab7e)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819dc05c)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/skmsg.c (ffffffff81a4cd7a)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_wait_data
  - net/core/skmsg.c:sk_msg_wait_data
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c05a)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81adbf3c)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b20f38)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/mptcp/protocol.c (ffffffff81bab131)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
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
In drivers/net/tun.c (ffffffff8190f777)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81a7da88)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81a8b1fe)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81a8c29c)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b578fa)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81b9b170)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6f4a)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc886a)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81be5ff8)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/unix/unix_bpf.c (ffffffff81beb60a)
Location: include/net/sock.h:1927
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
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
In drivers/net/tun.c (ffffffff81a62d3a)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81bf1128)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81c009ae)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81c01b39)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce58df)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81d2cfc3)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c094)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e09a)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7d1e8)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/unix/unix_bpf.c (ffffffff81d83a73)
Location: include/net/sock.h:2048
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
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
In drivers/net/tun.c (ffffffff81bedfea)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81d9d8e8)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81dafc7e)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81db0ef9)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8adf)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81ef48e2)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f266b4)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f285f6)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81f4a564)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/unix/unix_bpf.c (ffffffff81f51273)
Location: include/net/sock.h:2085
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
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
In drivers/net/tun.c (ffffffff81c4651a)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81e0c158)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81e1feee)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81e213e9)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0735f)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81f54260)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86374)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88166)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81faa204)
Location: include/net/sock.h:2072
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/unix/unix_bpf.c (ffffffff81fb0bd2)
Location: include/net/sock.h:2072
Inline: True
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
In drivers/net/tun.c (ffffffff81cfbe2a)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81ec8afa)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81edddce)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81edf199)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb6a4)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff8201a4b0)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d954)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f886)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff82077624)
Location: include/net/sock.h:2062
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
```
In net/unix/unix_bpf.c (ffffffff8207e272)
Location: include/net/sock.h:2062
Inline: True
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
In drivers/net/tun.c (ffff8000109dce38)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffff800010badf30)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffff800010bbc700)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffff800010bbd57c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ddd8)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffff800010cab3a4)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd43fc)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf233c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (c0ac24c4)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (c0ccb9cc)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c0cd8ad4)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c0cd95ac)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (c0d7c9f8)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (c0db7e10)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (c0dde5c8)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c0dfa27c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (c000000000aa283c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (c000000000c8390c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c000000000c957e8)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c000000000c966cc)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (c000000000d74560)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (c000000000dbfb74)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (c000000000df2444)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c000000000e1878c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffe000627b48)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffe00073ff10)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffe00074a84c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffe00074b9d4)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d34f4)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffe000804d12)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffe000825372)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083f46c)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff8178707d)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff818b5098)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818c1332)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818c2813)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c296)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81993c1b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7f9b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819d2229)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff817669cd)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff8186efe8)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8187b272)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8187c753)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915d86)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff8194d6db)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974d8b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198efe9)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff817b742d)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81906098)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81912332)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81913813)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6a66)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff819fe4bb)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22a1b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a3cca9)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In drivers/net/tun.c (ffffffff817cf4ca)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff819270c8)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819334d2)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81934996)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d05b6)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/af_inet.c (ffffffff81a0884b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2de0e)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a48265)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
</details>
</li>
</ul>

## Differences
