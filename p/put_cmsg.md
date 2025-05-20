# Function: <code>put_cmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8170ea90)
Location: net/core/scm.c:215
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/core/sock.c:sock_recv_errqueue
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8170ea90-ffffffff8170eb95: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81776240)
Location: net/core/scm.c:215
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81776240-ffffffff8177635b: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff817a34c0)
Location: net/core/scm.c:215
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff817a34c0-ffffffff817a35db: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff817c1600)
Location: net/core/scm.c:216
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff817c1600-ffffffff817c1723: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8183b010)
Location: net/core/scm.c:216
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8183b010-ffffffff8183b133: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81885740)
Location: net/core/scm.c:216
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81885740-ffffffff8188585a: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818a5e70)
Location: net/core/scm.c:216
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff818a5e70-ffffffff818a5f8a: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818f11e0)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff818f11e0-ffffffff818f130e: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81923120)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81923120-ffffffff81923254: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819f67a0)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff819f67a0-ffffffff819f6902: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819f6390)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff819f6390-ffffffff819f64f2: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819dc510)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff819dc510-ffffffff819dc67b: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81a8c750)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81a8c750-ffffffff81a8c8bb: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81c01ff0)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81c01ff0-ffffffff81c0215d: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81db15e0)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_wifi_status
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81db15e0-ffffffff81db179f: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81e21b20)
Location: net/core/scm.c:214
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_wifi_status
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81e21b20-ffffffff81e21cf0: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81edfa40)
Location: net/core/scm.c:220
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_wifi_status
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81edfa40-ffffffff81edfc10: put_cmsg (STB_GLOBAL)
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
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffff800010bbdee8)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffff800010bbdee8-ffff800010bbe290: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (c0cda370)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
c0cda370-c0cda55c: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (c000000000c97320)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
c000000000c97320-c000000000c974fc: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffe00074c14c)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffe00074c14c-ffffffe00074c244: put_cmsg (STB_GLOBAL)
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
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818c3120)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff818c3120-ffffffff818c3254: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8187d060)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8187d060-ffffffff8187d194: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81914120)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81914120-ffffffff81914254: put_cmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int put_cmsg(struct msghdr *msg, int level, int type, int len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819352b0)
Location: net/core/scm.c:213
Inline: False
Direct callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_recv_errqueue
  - net/core/scm.c:put_cmsg_scm_timestamping
  - net/core/scm.c:put_cmsg_scm_timestamping64
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff819352b0-ffffffff819353e4: put_cmsg (STB_GLOBAL)
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
