# Function: <code>prandom_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff813f8880)
Location: lib/random32.c:78
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/swapfile.c:SyS_swapon
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - block/blk-mq-tag.c:blk_mq_tag_init_last_tag
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_rcv
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff813f8880-ffffffff813f889a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8143fa0d)
Location: lib/random32.c:78
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - block/blk-mq-tag.c:blk_mq_tag_init_last_tag
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_rcv
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8143f700-ffffffff8143f71a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8145cb0d)
Location: lib/random32.c:78
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_rcv
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8145c800-ffffffff8145c81a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81461d1d)
Location: lib/random32.c:78
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81461a30-ffffffff81461a4a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8148dbfd)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/swapfile.c:SYSC_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8148d930-ffffffff8148d94a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff814c297d)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff814c26b0-ffffffff814c26ca: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff814d702d)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff814d6d60-ffffffff814d6d7a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81502e8d)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81502b90-ffffffff81502baa: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81520e2d)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81520b30-ffffffff81520b4a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81583e9d)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/fat/inode.c:fat_fill_inode
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81584010-ffffffff81584096: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff815a0ed0)
Location: lib/random32.c:384
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/fat/inode.c:fat_fill_inode
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/random32.c:prandom_reseed
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff815a0ed0-ffffffff815a0fb6: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff815a7d80)
Location: lib/random32.c:384
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/fat/inode.c:fat_fill_inode
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/random32.c:prandom_reseed
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff815a7d80-ffffffff815a7e67: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81610d00)
Location: lib/random32.c:384
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
  - mm/kfence/core.c:kfence_guarded_alloc
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/fat/inode.c:fat_fill_inode
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/random32.c:prandom_reseed
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/icmp.c:icmp_global_allow
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81610d00-ffffffff81610de4: prandom_u32 (STB_GLOBAL)
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
In kernel/time/clocksource.c (ffffffff811a190b)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In mm/shmem.c (ffffffff81315fc9)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/swapfile.c (ffffffff81382d13)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/kfence/core.c (ffffffff813aeac5)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/ext4/ialloc.c (ffffffff814d6e98)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/ioctl.c (ffffffff814edfc9)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mmp.c (ffffffff814fe286)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - fs/ext4/mmp.c:ext4_multi_mount_protect
```
```
In fs/ext4/super.c (ffffffff8152aaef)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_register_li_request
```
```
In fs/fat/inode.c (ffffffff815619a1)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_inode
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81656107)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/sbitmap.c (ffffffff81773a09)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_init_node
```
```
In net/core/sock.c (ffffffff81bf23c7)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff81c01d4a)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/neighbour.c (ffffffff81c23f7f)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_base_reachable_time
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/netlink/af_netlink.c (ffffffff81cac851)
Location: include/linux/prandom.h:15
Inline: True
```
```
In net/ipv4/route.c (ffffffff81cce883)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_output.c (ffffffff81cdc2aa)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce3022)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4bd2)
Location: include/linux/prandom.h:15
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cf61ee)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81cfef47)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05f39)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c24d)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81d15746)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff81d1b19c)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff81d23aea)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/igmp.c (ffffffff81d31e7e)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/syncookies.c (ffffffff81d5abc3)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81d72133)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
```
```
In net/unix/af_unix.c (ffffffff81d7ff16)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/addrconf.c (ffffffff81d9b732)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff81da0612)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/mcast.c (ffffffff81dc46a1)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca231)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd18be)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd3f7c)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
```
In net/ipv6/syncookies.c (ffffffff81de3895)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff81ded5d9)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
```
In net/packet/af_packet.c (ffffffff81df2802)
Location: include/linux/prandom.h:15
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffff80001062a320)
Location: lib/random32.c:79
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/random32.c:__prandom_timer
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffff80001062a320-ffff80001062a344: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (c07d16a4)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/netlink/af_netlink.c:netlink_autobind
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
c07d1378-c07d139c: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (c0000000007cc3f8)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/netlink/af_netlink.c:netlink_autobind
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
c0000000007cbec0-c0000000007cbef8: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffe00045ab36)
Location: lib/random32.c:79
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/random32.c:__prandom_timer
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/netlink/af_netlink.c:netlink_autobind
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffe00045ab36-ffffffe00045ab6e: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8151940d)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81519110-ffffffff8151912a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff815096fd)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81509410-ffffffff8150942a: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8151549d)
Location: lib/random32.c:79
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff815151a0-ffffffff815151ba: prandom_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 prandom_u32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8152e9f0)
Location: lib/random32.c:79
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - mm/swapfile.c:__do_sys_swapon
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - lib/random32.c:__prandom_timer
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/neighbour.c:pneigh_enqueue
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8152e9f0-ffffffff8152ea21: prandom_u32 (STB_GLOBAL)
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
