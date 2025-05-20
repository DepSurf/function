# Function: <code>refcount_read</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8137444a)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff8138e100)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff81395252)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In drivers/pci/slot.c (ffffffff814b9e06)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/net/tun.c (ffffffff81693b51)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff817b6451)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff817b6f20)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff817bd73d)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff817c01e0)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/dev.c (ffffffff817cbe8e)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff817dcaba)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff817edeb3)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/sched/sch_generic.c (ffffffff817fc97e)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_api.c (ffffffff817ff76a)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81806f81)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/inetpeer.c (ffffffff81813fc7)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/ip_input.c (ffffffff818151ea)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81816869)
Location: include/linux/refcount.h:39
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81819d03)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f035)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fbe7)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820eeb)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81822044)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8182c641)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81835cd1)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_small_queue_check
  - net/ipv4/tcp_output.c:tcp_small_queue_check
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818396c5)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818412c9)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff818417bd)
Location: include/linux/refcount.h:39
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8184393e)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818464a6)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/arp.c (ffffffff8184cab6)
Location: include/linux/refcount.h:39
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81854ab9)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81862cd6)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff8186dfcf)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8187042f)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81875a91)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff8187df8a)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/unix/af_unix.c (ffffffff818808f7)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff8188a791)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8188bff2)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/raw.c (ffffffff818abf66)
Location: include/linux/refcount.h:39
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b681d)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:reqsk_put
```
```
In net/ipv6/datagram.c (ffffffff818bd70d)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/ipv6/syncookies.c (ffffffff818c8721)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff818c9e1a)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce66f)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff818ced2e)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff818d6167)
Location: include/linux/refcount.h:39
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/audit_tree.c (ffffffff8114b097)
Location: include/linux/refcount.h:40
Inline: True
```
```
In kernel/bpf/sockmap.c (ffffffff811b0e3c)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In fs/notify/mark.c (ffffffff812bcc45)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be7c9)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff813991da)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff813b3595)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff813ba9a2)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In drivers/pci/slot.c (ffffffff814fa206)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/net/tun.c (ffffffff816fd984)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff817bfff8)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
```
In net/core/sock.c (ffffffff8182ea11)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff8182f516)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81835b56)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81839bf6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/dev.c (ffffffff8184778e)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff8185768a)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/rtnetlink.c (ffffffff8185b6eb)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff8186a0f3)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/sched/sch_api.c (ffffffff8187d4da)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81885d31)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff818943ba)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81895a09)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8189833c)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dfe9)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189eb7b)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a03cf)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818a10b9)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff818ab52b)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff818b52d3)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8e55)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0a98)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff818c0fdd)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818c337e)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c5ed6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/arp.c (ffffffff818cc776)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818d4959)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff818e2e06)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff818ee949)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f0e2f)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f61a7)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff818fee3a)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/unix/af_unix.c (ffffffff81901af7)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff8190b996)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8190d2e2)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/raw.c (ffffffff8192ea16)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193964d)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:reqsk_put
```
```
In net/ipv6/datagram.c (ffffffff8194082d)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/ipv6/syncookies.c (ffffffff8194bce6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff8194d505)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953539)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81953c1e)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff8195bd07)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/audit_tree.c (ffffffff81159b98)
Location: include/linux/refcount.h:40
Inline: True
```
```
In kernel/bpf/sockmap.c (ffffffff811cc85c)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In fs/notify/mark.c (ffffffff812e57b5)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e726e)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff813c8c35)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff813e3cdb)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff813eb7b7)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff8145a6cf)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff8145aac2)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In block/blk-core.c (ffffffff8147fb8f)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue_node
```
```
In block/blk-tag.c (ffffffff81485cbd)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81486dad)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
```
```
In block/blk-mq.c (ffffffff81492235)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In drivers/pci/slot.c (ffffffff8152acc6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/net/tun.c (ffffffff8173c9f3)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff8180a9fa)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff81878e8d)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff818799f6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff8187ff86)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff8188433b)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_checksum_complete
  - net/core/datagram.c:__skb_checksum_complete_head
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81886e57)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81891b97)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff818a285b)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/sock_reuseport.c (ffffffff818b9dd6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff818bd4ec)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/sched/sch_api.c (ffffffff818cfc1a)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff818d96d7)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff818e85d6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9c18)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818ec65a)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f29a6)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f374d)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f585e)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818fb3cf)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81900958)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8190a994)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c8f9)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e274)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819148c2)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916540)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81916b2d)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81918ff1)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191b20c)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/arp.c (ffffffff81922c0f)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8192ab19)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff819397ad)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff819459b5)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194775f)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194c3a3)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/xfrm/xfrm_input.c (ffffffff819558fa)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/unix/af_unix.c (ffffffff819597c1)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff8196307d)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff819646e3)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/raw.c (ffffffff81987328)
Location: include/linux/refcount.h:40
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199190c)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff819996f9)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/syncookies.c (ffffffff819a4f42)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819a5ca9)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acf7a)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819ad647)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff819b550b)
Location: include/linux/refcount.h:40
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/audit_tree.c (ffffffff81166e06)
Location: include/linux/refcount.h:41
Inline: True
```
```
In fs/notify/mark.c (ffffffff812fa335)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fc22e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/aio.c (ffffffff8130969c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
```
In fs/fuse/file.c (ffffffff813e1e75)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff813fe4cb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff814063b7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff81477c2f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff81478632)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffff81540b46)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/base/core.c (ffffffff8169d119)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff81760f03)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff818369fa)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff8189983d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff8189a646)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff8189d135)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff818a47ad)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff818a7877)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818b24f7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff818c5a35)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff818e0b4d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff818e48bc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff818e5f88)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffff818ec8ac)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/sched/sch_api.c (ffffffff818fae97)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818feea9)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81905ec7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff81915116)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81916e35)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819197ee)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81920416)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8192126d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922b9e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81929313)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8192e9e0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81938c34)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ac29)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c664)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943072)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944ce0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff819452dd)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819477c1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194978c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/arp.c (ffffffff81951a0f)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8195a039)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff8196943d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff81975d2f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197932f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f630)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff8198e4e1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81998068)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81999092)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bdf68)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c814c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff819d0049)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/syncookies.c (ffffffff819dba27)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819dce73)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3931)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819e3fb7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff819ec7db)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In kernel/fork.c (ffffffff8109a730)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (ffffffff810d62c3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (ffffffff8113f87d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffffffff81173998)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81197344)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffffffff81209c1a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffffffff812d49ed)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8131ad35)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131cbbe)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff8140dd15)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff8142ab18)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff814334f3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff814a58ea)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff814a6457)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffff81570446)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/base/core.c (ffffffff816d5f5a)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/net/tun.c (ffffffff8179eb98)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff818795e1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff818e3e3d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff818e4d23)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff818e7bdb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff818eff27)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff818f3588)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818feaeb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff81911a57)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff8192f1ec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81933efc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff81935b8b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffff8193e748)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff81947b06)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffffffff8195a889)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195e96f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff8196714d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff81977626)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978e15)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8197b9b1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982d38)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c29)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985477)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8198c248)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81992016)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8199ce74)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff8199efc8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0aac)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a762f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a93c1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff819a98dd)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819abe62)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819ade05)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/arp.c (ffffffff819b62da)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819becaf)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff819d0087)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff819df8a1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2e0f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e92e7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff819f9a91)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff81a04035)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a04f94)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1db28)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a2ca6c)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36be4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a3ed6e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81a486b0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81a4a6c9)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a4bad9)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52667)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a52ea4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81a5b97a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81a747e0)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (ffffffff810a0cf0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (ffffffff810e0943)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (ffffffff8114b45d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffffffff8117f808)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a2d04)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffffffff81216f8a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffffffff812e656d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8132d8a5)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f9fe)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff81426e95)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff81444868)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff8144d263)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff814c059a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff814c10e7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffff81591526)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81692872)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff816f9f9a)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767652)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (ffffffff817c2628)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff818ab3fb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff8191601d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff81916eb3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff8191a0bb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81921f50)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81925529)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81930e2b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff819440c7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff8196145c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81966a1c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff8196899b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffff819715d8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff8197cc16)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffffffff81990d39)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81995245)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff8199dbdd)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff819adfb6)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819af785)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819b20b7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9590)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba409)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc8c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819c2b98)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff819c8eef)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819d3934)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5a68)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d766f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de6af)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0054)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff819e059d)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819e2b12)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e4b15)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff819ecffa)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819f58db)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a06bd7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff81a16901)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19dff)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20317)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff81a30711)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff81a3ac1d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bb64)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54758)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a6373c)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d796)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a759de)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81a7f271)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81a8129d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a826a9)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89270)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a89a84)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81a925aa)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81aab196)
Location: include/linux/refcount.h:41
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
In arch/x86/kernel/ioport.c (ffffffff810371f7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81040fa4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/fork.c (ffffffff810a7b55)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/core.c (ffffffff810dcdb5)
Location: include/linux/refcount.h:145
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ef258)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff81141468)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8115c02d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/audit_tree.c (ffffffff81192f25)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/trace/trace.c (ffffffff811bb574)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/bpf/btf.c (ffffffff812260dc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff8122a7ac)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123013d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff81242bc8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81243e1f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812c2323)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/memcontrol.c (ffffffff812f5e6e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff8131db6a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/notify/mark.c (ffffffff81367b02)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8136994e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
```
In fs/io_uring.c (ffffffff81385e4e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_wq_submit_work
```
```
In fs/io-wq.c (ffffffff8138b633)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
```
```
In fs/crypto/keyring.c (ffffffff81392666)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813a5d8d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813c2a61)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813c9a71)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/configfs/item.c (ffffffff813d78e6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff81477395)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/debugfs/file.c (ffffffff81482500)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8148715d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/gc.c (ffffffff814958c8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8149767f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81498efa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8149f153)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff814ed7b3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff814f15d1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814f8f9e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814fb729)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff814ff33d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81501432)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff8150592a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815074ad)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8150a48c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8150dc6e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8150f3ee)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8150f9be)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In crypto/algapi.c (ffffffff815206f5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff81521997)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In block/blk-mq.c (ffffffff8154f1ec)
Location: include/linux/refcount.h:145
Inline: True
```
```
In block/bsg-lib.c (ffffffff815695bc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815dc5c0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff815ea0d1)
Location: include/linux/refcount.h:145
Inline: True
```
```
In lib/kobject.c (ffffffff815eaad1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/pci/slot.c (ffffffff8163f909)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/dma/dmaengine.c (ffffffff81707804)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8174518c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
```
```
In drivers/tty/vt/vt.c (ffffffff81750fd1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754fdd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817791b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/base/core.c (ffffffff817b2ef1)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825dfe)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827a2a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818296c1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bf2f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818398cd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/tun.c (ffffffff8188d103)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff8197b5cc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d4c2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819e4b75)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/request_sock.c (ffffffff819e9855)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff819ebf65)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff819f5190)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff819f99bd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a0609b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff81a14139)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_forced_gc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81a2d113)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81a34ab5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/net-sysfs.c (ffffffff81a3a14c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff81a3ca03)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/core/fib_rules.c (ffffffff81a3f9b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81a44fed)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/sock_map.c (ffffffff81a4efdc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/devlink.c (ffffffff81a5455d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61177)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81a68d49)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6c916)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81a76aec)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81a92e21)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a9756a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81a97e5a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9960f)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81a9d5a3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa40ec)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4ee8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6658)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81aae1cb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81ab455a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81ac04c2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac20a8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4841)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb644)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd28c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv4/tcp_rate.c (ffffffff81acdb6d)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ad00d3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
  - net/ipv4/raw.c:raw_sock_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad2767)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_format_sock
  - net/ipv4/udp.c:udp4_format_sock
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81adaf68)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adc9dd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff81ae3c3d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef220)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81af640e)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81af661d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
  - net/ipv4/ping.c:ping_v4_format_sock
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/nexthop.c (ffffffff81afcf97)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/syncookies.c (ffffffff81b07924)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0931b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b4c7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11b61)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c831)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff81b242e3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_compat_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff81b30212)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81b30fe7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b332b3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b49c5b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bb4e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff81b58ae7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b5cbac)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66b5a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_timewait6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6fc1e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81b79f1d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81b7bf3a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7d3f7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b826b9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84440)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81b85004)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81b8da5a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81ba763a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/ioport.c (ffffffff810382b7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81040f04)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068978)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810a38c8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/core.c (ffffffff810e011f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810ed232)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff8113d708)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff811587bf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/audit_tree.c (ffffffff81190095)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/seccomp.c (ffffffff811a2a70)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/trace/trace.c (ffffffff811b9174)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/bpf/btf.c (ffffffff8122cc6c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff8123254c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812385ed)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8124d319)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124e4af)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812ce01c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/memcontrol.c (ffffffff8130126e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff813289ca)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/notify/mark.c (ffffffff81374e82)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376c3e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
```
In fs/io_uring.c (ffffffff8139a976)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_free
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff8139c813)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
```
```
In fs/crypto/keyring.c (ffffffff813a39e7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813b6ace)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813d4bef)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813dbac3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813e94e6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff81492135)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/dax.c (ffffffff8149d391)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/dax.c:inode_inline_reclaim_one_dmap
  - fs/fuse/dax.c:inode_inline_reclaim_one_dmap
```
```
In fs/debugfs/file.c (ffffffff8149fb90)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814a477d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/gc.c (ffffffff814b3328)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff814b512f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814b697a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff814bcb83)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff8150ae33)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff8150e871)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff815160de)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81518776)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8151c57d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81521612)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81522a5f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152455d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81527304)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8152aad4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8152c22e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8152c802)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In crypto/algapi.c (ffffffff8153d585)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff8153e807)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In block/blk-mq.c (ffffffff8156b19c)
Location: include/linux/refcount.h:145
Inline: True
```
```
In block/bsg-lib.c (ffffffff8158403c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815fa240)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff8160ea11)
Location: include/linux/refcount.h:145
Inline: True
```
```
In lib/kobject.c (ffffffff8160f3f1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/pci/slot.c (ffffffff81665d59)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/dma/dmaengine.c (ffffffff81724a54)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81761400)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
```
```
In drivers/tty/vt/vt.c (ffffffff8176ca01)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817702dd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817939c1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/base/core.c (ffffffff817c7951)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818367f0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818384aa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818393b2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183cf8f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a14d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/tun.c (ffffffff8189b384)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff81c280a5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In drivers/edac/ghes_edac.c (ffffffff8199108b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819e43ea)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/request_sock.c (ffffffff819e95f5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff819eb775)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff819f4bc0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff819f9503)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a06ceb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff81a143e1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_forced_gc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81a2ee97)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81a36df5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/net-sysfs.c (ffffffff81a3c6cc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff81a3f7ac)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/fib_rules.c (ffffffff81a42677)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81a4912d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/sock_map.c (ffffffff81a54baa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69fda)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81a7146e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a752c0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81a7f86c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81a9cccf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81aa152a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81aa1dba)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa357f)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81aa7460)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae713)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf548)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0ca8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ab8426)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81abeeea)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81acbf21)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdb28)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0181)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad75e4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad929c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv4/tcp_rate.c (ffffffff81ad9bcd)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81adc053)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
  - net/ipv4/raw.c:raw_sock_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ade6a7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_format_sock
  - net/ipv4/udp.c:udp4_format_sock
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81ae7a28)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae971c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff81af0b5d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc168)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0327f)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81b0349d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
  - net/ipv4/ping.c:ping_v4_format_sock
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/nexthop.c (ffffffff81b0af52)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/syncookies.c (ffffffff81b15cea)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17b3e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1983b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f2fd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2b00d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff81b33073)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_compat_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ecb9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fc17)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b41bdb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b5887b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5a78e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff81b6711c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b6b3ee)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b750ba)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_timewait6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b7e74e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81b88e6d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81b8af6b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b8c597)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91d34)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93c9f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81b94944)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81b9d710)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81bb64a3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81bc5aa9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/kernel/ioport.c (ffffffff81039df7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81042904)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068bc0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810a44f8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/core.c (ffffffff810e1efc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810f0995)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff8113e958)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81159a2f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/audit_tree.c (ffffffff81190fc5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/seccomp.c (ffffffff811a3540)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/trace/trace.c (ffffffff811b9a3a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff81225e8c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
```
```
In kernel/bpf/btf.c (ffffffff81231a1c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff812366ec)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff81237c81)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123cddd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff81251bd9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81252daf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812d4c51)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8130756e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff8132fa64)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/notify/mark.c (ffffffff8137b842)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d53e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
```
In fs/io-wq.c (ffffffff813a237b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813aac27)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813bdb2e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813dba2b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813e29e3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813f0056)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff814972f5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/dax.c (ffffffff814a2e1c)
Location: include/linux/refcount.h:145
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814a5b90)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814aa74d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/gc.c (ffffffff814b9168)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff814bafdf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814bc7c6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff814c2a23)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff815115af)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff8151526d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8151ca64)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8151efce)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff81522d51)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527a02)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81528c3b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a737)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8152cfca)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff81530ce1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff815324ce)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81532b3e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff815390e1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/algapi.c (ffffffff81545c65)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff81546eb7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In block/blk-mq.c (ffffffff81576fb6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/blk-mq-tag.c (ffffffff81578eb8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff8158ae3c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815dce20)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff815f21a1)
Location: include/linux/refcount.h:145
Inline: True
```
```
In lib/kobject.c (ffffffff815f2b31)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/pci/slot.c (ffffffff816482f9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/dma/dmaengine.c (ffffffff81705d14)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744ed8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vt.c (ffffffff81750591)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753d8d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81776b7a)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/base/core.c (ffffffff817aadc1)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818199c0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b787)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c66a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181ff6b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182d8cd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/tun.c (ffffffff8187e014)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/vfio/vfio.c (ffffffff8188d922)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/md/dm.c (ffffffff81c1a25c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In drivers/edac/ghes_edac.c (ffffffff819755fb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819ca47a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/request_sock.c (ffffffff819cf715)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff819d1d65)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff819dad50)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff819df663)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff819ee3dd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff819fad71)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81a16447)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81a1de99)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/net-sysfs.c (ffffffff81a234dc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/fib_rules.c (ffffffff81a27383)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81a2e07d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/skmsg.c (ffffffff81a4e984)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81a5159b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a524da)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81a59e2e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5dc60)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81a68822)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81a87d91)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c47a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81a8ccea)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e6ef)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81a92604)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a997f7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a858)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bd54)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81aa3720)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81aab31e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81ab480e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8cd8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb28b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac26ce)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac46eb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81ac4c1d)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ac6f12)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ac95e5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81ad2ce8)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad4ddc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff81adc313)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7878)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeea27)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81aeed17)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/nexthop.c (ffffffff81af62ee)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/syncookies.c (ffffffff81b03af1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0570f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05d14)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b072ab)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0cf7d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18c3e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff81b20db6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ba59)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2da47)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b2f8c7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b46b62)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4895e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff81b552f6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b59741)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63e9f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6d35e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81b77c98)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81b79dce)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7b5cd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80f88)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82daf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81b83a2e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81b8c81c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81ba5463)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81bb6628)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/kernel/ioport.c (ffffffff8103f7a7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81048c72)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072f8b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810b5d18)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/core.c (ffffffff810f81a6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81109415)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff81161de8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8117f144)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_pi_state
```
```
In kernel/audit_tree.c (ffffffff811b9ea5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/seccomp.c (ffffffff811ccc20)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/trace/trace.c (ffffffff811e423a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff8125deac)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
```
```
In kernel/bpf/btf.c (ffffffff8126a9bc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff81270ccc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff81272255)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8127785d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8128d3fb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128e69f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff8131afbf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff813512de)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff8137d221)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/notify/mark.c (ffffffff813c85ff)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca43d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
```
In fs/io-wq.c (ffffffff813f18e7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813fa4b7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff8140d91e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff8142d0c5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814344f3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81441f46)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff814eec75)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/dax.c (ffffffff814fb06c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
```
In fs/debugfs/file.c (ffffffff814fdd30)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81502c0d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8150c505)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/gc.c (ffffffff81511998)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8151380f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815151e6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8151b413)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff8156f1af)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff8157321d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8157ab35)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8157d16e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff81580fc1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81585c92)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81586f64)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81588ad7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8158b3ba)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8158f121)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81590a4e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff815910be)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff81597921)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/algapi.c (ffffffff815a6175)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff815a7697)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In block/blk-mq.c (ffffffff815d9741)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/blk-mq-tag.c (ffffffff815de10b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff815efe2c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff81648780)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff8165f311)
Location: include/linux/refcount.h:145
Inline: True
```
```
In lib/kobject.c (ffffffff8165fd11)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/pci/slot.c (ffffffff816b9d06)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/dma/dmaengine.c (ffffffff817815f4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c5d43)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vt.c (ffffffff817d2e30)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d72cd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817fc54a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/base/core.c (ffffffff81833f61)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5c17)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6a33)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa62b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b931d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/tun.c (ffffffff8190f7f9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/vfio/vfio.c (ffffffff81920f6c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/md/dm.c (ffffffff81d29f01)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1e307)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff81a79a1a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/request_sock.c (ffffffff81a7f255)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81a819c5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81a8b3d0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81a8fa43)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a9f67d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff81aac9b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81acccf1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81ad1bdf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/net-sysfs.c (ffffffff81ad7adc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/fib_rules.c (ffffffff81adc116)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81ae365d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff81b027ef)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/skmsg.c (ffffffff81b074f1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81b0951b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b5e3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81b12efe)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b16e20)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81b21e84)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f342)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81b422d0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81b47498)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81b47e22)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81b498df)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81b4da08)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54c77)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55cc8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57457)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81b5f8ab)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81b672a4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81b717ce)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81b75ef8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b785db)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b8054b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82df5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81b833cd)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b85732)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b87e55)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81b91938)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b93c8c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff81b9b533)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7793)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81baedf7)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81baf0e7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/nexthop.c (ffffffff81bb7d9e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/syncookies.c (ffffffff81bc5d9e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc825f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8a02)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bca127)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd01a1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdd02e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff81be5e76)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/unix/unix_bpf.c (ffffffff81beb789)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1baf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3c9b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81bf5c47)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81c0ddb2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81c0fcf4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff81c1ddc3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81c20d6a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b95f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81c3527e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81c427b8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81c44a86)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81c46586)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4cfa8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ee7f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81c4fb3e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81c58bdc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81c72fe3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81c85638)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/kernel/ioport.c (ffffffff81046ed5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81051f73)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081603)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810cc210)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/core.c (ffffffff81114476)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff8111d8ef)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff81194cef)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811b2420)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811b4e2c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/audit_tree.c (ffffffff811ed010)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/seccomp.c (ffffffff81200971)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/trace/trace.c (ffffffff8121b514)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff812a826e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
```
```
In kernel/bpf/btf.c (ffffffff812b7802)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff812bfdac)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff812c1585)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c74fd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff812e2107)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e356c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/madvise.c (ffffffff813780ba)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In mm/zswap.c (ffffffff81386043)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff813c9d2a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff813fce15)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/notify/mark.c (ffffffff8144fbcf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814519f8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
```
In fs/crypto/keyring.c (ffffffff8146d637)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff81482c07)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff814a6a7d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814ae610)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff814bdba6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff8157d8b5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/dax.c (ffffffff8158b53c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
```
In fs/debugfs/file.c (ffffffff8158e920)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff815941cd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8159e475)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/gc.c (ffffffff815a3cf1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff815a5ca9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815a7976)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff815ae61b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d6ea)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81610520)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81618dcc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8161b7ec)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8162017a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81626819)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff8162738d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816291aa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8162c926)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff81630158)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81631bad)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81632c3d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff8163c091)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/algapi.c (ffffffff8164d4f0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff8164e982)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In block/bsg-lib.c (ffffffff816a0f2c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff816da2ab)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/syscall.c (ffffffff8175ebb0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff81778ee1)
Location: include/linux/refcount.h:145
Inline: True
```
```
In lib/kobject.c (ffffffff81779851)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/pci/slot.c (ffffffff817de5e7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8180c104)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:framebuffer_release
```
```
In drivers/dma/dmaengine.c (ffffffff818b7fa2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81902ca5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vt.c (ffffffff81910de9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81915419)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8193b1a8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/base/core.c (ffffffff81975834)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efb67)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f07b0)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4e1d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04fa2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/tun.c (ffffffff81a62dbb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/vfio/vfio.c (ffffffff81a786d6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:__vfio_register_dev
```
```
In drivers/md/dm.c (ffffffff81ef61f3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
```
In drivers/edac/ghes_edac.c (ffffffff81b86a42)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff81bf260d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
```
```
In net/core/request_sock.c (ffffffff81bf3513)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81bf61a5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81c00681)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81c03d40)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81c17d3c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff81c25945)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81c499d1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81c4f452)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81c5884c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/fib_rules.c (ffffffff81c5d460)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81c682e5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff81c839b0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/skmsg.c (ffffffff81c8cc61)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81c8f639)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91be3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81c99b59)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81c9e7cf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81caa83e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81ccbaa0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81ccecd8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81cd4638)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81cd5092)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6f0a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81cdb27e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2878)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce39cb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce53df)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81cee36e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81cf67c1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81cfda30)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05839)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08292)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d108c9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d13405)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81d139dd)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d162ff)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81d1901d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81d22e1c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81d24b84)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff81d2d52a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39fd0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42148)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ping.c (ffffffff81d4241b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/nexthop.c (ffffffff81d4bb53)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/proc.c (ffffffff81d4f698)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/syncookies.c (ffffffff81d5b032)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5daee)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5dfc9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f8bf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d663e1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81d73dfa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff81d7c156)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/unix/unix_bpf.c (ffffffff81d83975)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a5ef)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81d8c9be)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81d8ee17)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81da8db8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81daaf47)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff81dba358)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81dbdb33)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8ef3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81dd2c19)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81de1289)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81de3a87)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81de5a23)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded460)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def854)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81df05f5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/8021q/vlan_core.c (ffffffff81dfa2e7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81e16d6d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81e2b84c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/af_mctp.c (ffffffff81e37c1e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff81e387bd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff81e3ac35)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
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
In arch/x86/kernel/ioport.c (ffffffff81051035)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8105f7a3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093ee3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810e98c0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/core.c (ffffffff8113b7b6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81144c90)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff811d29ef)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811f32a0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811f5f1c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/audit_tree.c (ffffffff812335a0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/seccomp.c (ffffffff81248691)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/trace/trace.c (ffffffff81265064)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff81306a6b)
Location: include/linux/refcount.h:145
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81318e62)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff8132358c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff81324e85)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cecd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8134a652)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134bbfc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/madvise.c (ffffffff813f59c8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In mm/zswap.c (ffffffff81403e73)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8144f2fa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff81483df5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/notify/mark.c (ffffffff814de4ff)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0738)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
```
In fs/crypto/keyring.c (ffffffff814ff3b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/posix_acl.c (ffffffff815159b7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff8153c0bd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff81544c50)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff815558e6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff81623435)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/dax.c (ffffffff81631d7c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
```
In fs/debugfs/file.c (ffffffff816359b0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8163cdbd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81647af5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/gc.c (ffffffff8164d9b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8164fac9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816519d6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff81658d7b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf66a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff816c2f80)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff816cbc2f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff816ce8c3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff816d3664)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff816da6b9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff816db398)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816dda96)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff816e13d6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff816e4dda)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff816e68d5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e7a8d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff816ea00a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff816f386b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/algapi.c (ffffffff81706560)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff81707e02)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In block/bsg-lib.c (ffffffff8175fafc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff817a635b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/syscall.c (ffffffff8188c4d0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/pci/slot.c (ffffffff819011d7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8193aae4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:framebuffer_release
```
```
In drivers/dma/dmaengine.c (ffffffff81a05272)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5cc75)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vt.c (ffffffff81a6bca9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a706c9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b868)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/base/core.c (ffffffff81ae13d4)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d1a7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e6f0)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b722cd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83c52)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/tun.c (ffffffff81bee06b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25a13)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/core/sock.c (ffffffff81d9fe3d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
```
```
In net/core/request_sock.c (ffffffff81da1273)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81da4a85)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81dafe81)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81db3410)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81dc8c6c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff81dd7b85)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81dfec05)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e04a39)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81e0e70c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/fib_rules.c (ffffffff81e13c10)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81e1f5b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff81e3be60)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_del_doit
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/skmsg.c (ffffffff81e47afa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81e4aa65)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4d1b3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81e55e89)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5af5f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81e6790e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b8f0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81e8ef43)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81e94908)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81e95562)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81e974aa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81e9bb54)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3ce5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6411)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea85cf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81eb15a6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81ebb1d1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81ec2680)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81eca969)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81eccd62)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3891)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_twsk_purge
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6609)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9375)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed99bd)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edc4cf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81edf76d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81eea31c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81eec374)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff81ef53a2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02930)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af88)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ping.c (ffffffff81f0b28b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/nexthop.c (ffffffff81f15163)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/proc.c (ffffffff81f192d0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/syncookies.c (ffffffff81f254a2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2779e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f287b2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29fcf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f31171)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3fd6e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff81f492e6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff81f51175)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81f5857f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81f5abce)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81f5d307)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81f784b8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7a837)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff81f8a41c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81f8e042)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99c03)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81fa40d9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81fb36e9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81fb6107)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81fb8243)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc1280)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3924)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81fc4775)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/8021q/vlan_core.c (ffffffff81fcea07)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81fee73d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff82003a1c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/af_mctp.c (ffffffff82010ea4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff82011a8d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff82014205)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff82021d01)
Location: include/linux/refcount.h:145
Inline: True
```
```
In lib/kobject.c (ffffffff820227f1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In arch/x86/kernel/ioport.c (ffffffff81051d65)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81060f03)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096e6c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810f542c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/core.c (ffffffff8114ec2c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff811551b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff811e6cdf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff81207a20)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8120a71c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/audit_tree.c (ffffffff8124a256)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/seccomp.c (ffffffff8125fa7f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/trace/trace.c (ffffffff8127c124)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_events_user.c (ffffffff812c71d5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl
  - kernel/trace/trace_events_user.c:user_event_free
  - kernel/trace/trace_events_user.c:user_event_is_busy
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/bpf/helpers.c (ffffffff81321354)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff813359db)
Location: include/linux/refcount.h:145
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81348c82)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff813537bc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff813550e5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c831)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff8137b692)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137cc4c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/madvise.c (ffffffff81428758)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In mm/zswap.c (ffffffff81436cdc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81484d2a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff814b8635)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/notify/mark.c (ffffffff81514d2f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516fe8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
```
In fs/crypto/keyring.c (ffffffff815368ca)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/posix_acl.c (ffffffff8154d493)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815743e8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8157c840)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff8158d686)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff8165b815)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/dax.c (ffffffff81669fbc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
```
In fs/debugfs/file.c (ffffffff8166dcc0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816752cd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81680018)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/gc.c (ffffffff81686161)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff816883a9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8168a286)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff81691618)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff816f817a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff816fbb30)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff817049a1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff817074de)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8170c534)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff817136a9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff81714a80)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff817170b6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8171a9d6)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8171e444)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8172000a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8172120d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff8172425a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8172d99b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/algapi.c (ffffffff81740750)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff81741522)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In crypto/ahash.c (ffffffff81744c9e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817461b3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff8179e9dc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff817e72c4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff818ce940)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/pci/slot.c (ffffffff81944797)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197eada)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:framebuffer_release
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e2b2)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa73c7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vt.c (ffffffff81ab63c9)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abae88)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81ae71c8)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/base/core.c (ffffffff81b2f639)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc08d7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1f00)
Location: include/linux/refcount.h:145
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5cdd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd79aa)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/tun.c (ffffffff81c4659b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8ec33)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/core/sock.c (ffffffff81e0e5fd)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
```
```
In net/core/request_sock.c (ffffffff81e0fb43)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81e136f5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81e200e7)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81e23ad0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81e371cc)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/neighbour.c (ffffffff81e48995)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81e701c8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e77289)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81e81b4c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/fib_rules.c (ffffffff81e87542)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81e91caf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/skmsg.c (ffffffff81ea3277)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81ea6165)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea88cf)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81eb2214)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb6d2f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff81ec36ee)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9934)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81eed65b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81ef30d8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81ef3d62)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5cda)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81efa5de)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02551)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04bf1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06e4f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f0fc36)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81f1965c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81f208d0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81f294bb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ba3f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32881)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_twsk_purge
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3558e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f3845a)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38a9d)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3b61f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3ed5d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81f49c4c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff81f4c164)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff81f54c82)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62439)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aad5)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ping.c (ffffffff81f6ae6b)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81f74e23)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/proc.c (ffffffff81f78f80)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/syncookies.c (ffffffff81f85032)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87466)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88319)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89b81)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f918d1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f4eb)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff81fa8e96)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff81fb0ad9)
Location: include/linux/refcount.h:145
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb81ac)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81fba97e)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81fbd026)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fd86b8)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdaa47)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff81fea025)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81fecda3)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa5d0)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff82004999)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff82013f0c)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff8201681f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820189c4)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff82022200)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202476f)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff820278b1)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/leftover.c (ffffffff8203e450)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_del_doit
```
```
In net/devlink/core.c (ffffffff82042264)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/8021q/vlan_core.c (ffffffff8204a347)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff8206a836)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff8207fbac)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/af_mctp.c (ffffffff8208dc64)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff8208e87d)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff82091084)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff820a1d51)
Location: include/linux/refcount.h:145
Inline: True
```
```
In lib/kobject.c (ffffffff820a2861)
Location: include/linux/refcount.h:145
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In arch/x86/kernel/ioport.c (ffffffff81058f85)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81067fb3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e3dc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810fea3d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/core.c (ffffffff8115aab7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81161c11)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/stacktrace.c (ffffffff811fca2f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff8121ec30)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff81221c7c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/audit_tree.c (ffffffff81264166)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/seccomp.c (ffffffff81279bcf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/trace/trace.c (ffffffff81296e14)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3b65)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl
  - kernel/trace/trace_events_user.c:user_event_free
  - kernel/trace/trace_events_user.c:user_event_is_busy
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/bpf/helpers.c (ffffffff813439e4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff8135a03b)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8136f3b2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/net_namespace.c (ffffffff8137acac)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff8137dab5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385b2f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff813a4892)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a5eac)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/shrinker.c (ffffffff813e4dc4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/madvise.c (ffffffff81462002)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In mm/zswap.c (ffffffff81470937)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_current_get
```
```
In mm/memcontrol.c (ffffffff814b425a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/exec.c (ffffffff814eab45)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/notify/mark.c (ffffffff8154910f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b3d8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
```
In fs/crypto/keyring.c (ffffffff8156b951)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/posix_acl.c (ffffffff815832c3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815ace74)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff815b5160)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff815c63c6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/fuse/file.c (ffffffff816954f5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/dax.c (ffffffff816a42fc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
```
In fs/debugfs/inode.c (ffffffff816a603c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff816a8423)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816b168d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff816bc408)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/gc.c (ffffffff816c2574)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff816c2eb9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816c6786)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff816cdbe8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/apparmor/apparmorfs.c (ffffffff81734ef0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff8173922a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8174225a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81744f6e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8174a28f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8175290c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getlsmblob_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81753493)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755c19)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81759486)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8175ce84)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea40)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fd30)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff817623d0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81765560)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8176e061)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/algapi.c (ffffffff817815f0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff817823c2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In crypto/ahash.c (ffffffff817874d4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817887f3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff817e248c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff8182d084)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff81920720)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/stackdepot.c (ffffffff819289af)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:depot_fetch_stack
```
```
In drivers/pci/slot.c (ffffffff8198da97)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/video/fbdev/core/fb_info.c (ffffffff819c353a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_info.c:framebuffer_release
```
```
In drivers/dma/dmaengine.c (ffffffff81a99f52)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9e57)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vt.c (ffffffff81b090a9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0dbf8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a598)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/base/core.c (ffffffff81b86e39)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15057)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16690)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a6ec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c64a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87464)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group
  - drivers/gpu/drm/drm_connector.c:drm_connector_list_iter_next
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9b17a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove
  - drivers/gpu/drm/drm_framebuffer.c:drm_fb_release
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c44c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca41b0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1fe3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
```
```
In drivers/gpu/drm/drm_debugfs.c (ffffffff81cb9d59)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs.c:drm_gem_one_name_info
```
```
In drivers/net/tun.c (ffffffff81cfbeab)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/edac/ghes_edac.c (ffffffff81e46543)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/core/sock.c (ffffffff81ecb08d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
```
```
In net/core/request_sock.c (ffffffff81ecc5f3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81ed0725)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81eddfc7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81ee1a30)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81ef51ec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/neighbour.c (ffffffff81f07555)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/filter.c (ffffffff81f2a429)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81f37249)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81f42b2c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/fib_rules.c (ffffffff81f49552)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81f5406e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/skmsg.c (ffffffff81f65590)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81f68c25)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b38f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_api.c (ffffffff81f74cc4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f79acf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81f80a03)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f86b0e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81fad6d3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb16cb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81fb7068)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81fb7cf2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9c8a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81fbe4bd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc82a7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8ef9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb16f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fd3e26)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81fdd9dc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81fe8fae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81fedffb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff077f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8941)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_twsk_purge
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffb72b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe51a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffeb7d)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8200173f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff820050bd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff8200fd6c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv4/icmp.c (ffffffff82012274)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/af_inet.c (ffffffff8201aef2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/igmp.c (ffffffff8201ee74)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff82028a09)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff82031185)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ping.c (ffffffff8203151b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff8203b760)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/proc.c (ffffffff8203f640)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/syncookies.c (ffffffff8204b74d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204d301)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eae6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff8204fa39)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff820512e1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205f631)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c84b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/af_unix.c (ffffffff82076396)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff8207e179)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8208579b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff82087dae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff8208a456)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff820a6038)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff820a849e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/udp.c (ffffffff820b7c01)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff820ba9a3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8240)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff820d3769)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff820e3063)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff820e584b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820e7994)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f1320)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3a7f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff820f7111)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/core.c (ffffffff82100bd4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/devlink/rate.c (ffffffff821195a0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_del_doit
```
```
In net/8021q/vlan_core.c (ffffffff8211c7b7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff8213e467)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff8215509c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/af_mctp.c (ffffffff82164124)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff82164d6d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff821675a2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff82179dd1)
Location: include/linux/refcount.h:134
Inline: True
```
```
In lib/kobject.c (ffffffff8217a8e1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In kernel/fork.c (ffff8000100f56a0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (ffff800010140774)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (ffff8000101b95f8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffff8000101f4f04)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffff80001021f414)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffff8000102a11f8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffff80001038e73c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffff8000103e9e10)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec88c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffff80001050b61c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffff80001052d4c4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffff800010537308)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffff8000105b9c54)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffff8000105bb318)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffff8000106f7088)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010866488)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffff8000108e4740)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff800010968754)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (ffff8000109dcf48)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffff800010afe01c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In drivers/of/dynamic.c (ffff800010b70998)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
```
```
In net/core/sock.c (ffff800010baefc0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffff800010bb0480)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffff800010bb25a0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffff800010bbc614)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffff800010bc13d8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffff800010bce4fc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffff800010be3f48)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffff800010c04cd8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffff800010c0c184)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffff800010c0f49c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffff800010c1995c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffff800010c24818)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffff800010c3d288)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c41ea0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffff800010c4b0dc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffff800010c5e008)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5ffd8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffff800010c63e14)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6aca8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bf84)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6db78)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffff800010c759a8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffff800010c7aaa8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffff800010c86478)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffff800010c88c50)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a530)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffff800010c9233c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93bf4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffff800010c942c0)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffff800010c96a2c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffff800010c991dc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffff800010ca2a78)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffff800010cab6bc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffff800010cbfb8c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffff800010cd251c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5cec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc08c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffff800010cf0828)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffff800010cfbcdc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffff800010cfd130)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffff800010d189dc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffff800010d29238)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36098)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffff800010d3e344)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffff800010d4a504)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffff800010d4ca08)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffff800010d4ea04)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d56038)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffff800010d567e4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffff800010d60324)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffff800010d7f08c)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (c0353df4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
```
```
In kernel/futex.c (c0400df8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (c0434be0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/trace/trace.c (c045d864)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (c04d1340)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (c0574e44)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (c05c135c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (c05c2f90)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (c06c64fc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (c06e5c7c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (c06ee18c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (c07685b8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (c0769604)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (c08912dc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (c096bbbc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (c09d3168)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3e77c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (c0ac2548)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (c0bdd4e4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In drivers/of/dynamic.c (c0c52fec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
```
```
In net/core/sock.c (c0cccaec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (c0ccd7ec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (c0cd0820)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (c0cd8920)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (c0cdc3e8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (c0ce7de8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (c0cfe3fc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (c0d1e1a0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (c0d246c0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (c0d269dc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (c0d2f3b8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (c0d3bdb8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (c0d4ed3c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d53be8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (c0d5bc2c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (c0d6d8f0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c0d6f7c0)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (c0d73998)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (c0d79d50)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7ad74)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c158)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d84034)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (c0d88328)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c0d957ac)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_small_queue_check
  - net/ipv4/tcp_output.c:tcp_small_queue_check
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (c0d979e0)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d9a688)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (c0da0484)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (c0da24b8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (c0da2a4c)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (c0da50fc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c0da80d8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/arp.c (c0daf8dc)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (c0db8544)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (c0dcb658)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (c0ddc410)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (c0ddfb38)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (c0de588c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (c0df6c58)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (c0e00ee8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (c0e04298)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ip6_fib.c (c0e1ebac)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (c0e2cc80)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/tcp_ipv6.c (c0e38f98)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (c0e41624)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (c0e4bb24)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (c0e4dcfc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c0e4f288)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (c0e5663c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c0e56fa8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (c0e5fe28)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (c0e79248)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (c00000000013b7d4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (c00000000018fe08)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (c00000000021ec30)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (c000000000269b00)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In kernel/trace/trace.c (c0000000002a0da0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (c00000000035341c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (c00000000048574c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (c0000000004f1b2c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3304)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
```
In fs/fuse/file.c (c000000000650750)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (c000000000679648)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (c000000000686044)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (c00000000074022c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (c000000000741ae0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (c000000000875df0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905868)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (c000000000979aec)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fe3c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (c000000000aa28ec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (c000000000bebfe4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In drivers/of/dynamic.c (c000000000c4c16c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
```
```
In net/core/sock.c (c000000000c84d00)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (c000000000c85ea0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (c000000000c8a0a8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (c000000000c946a8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (c000000000c9a51c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (c000000000cac148)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (c000000000cc7328)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (c000000000ceee98)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (c000000000cf7444)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (c000000000cfa0cc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (c000000000d06300)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (c000000000d17fa4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (c000000000d36a88)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3dd80)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (c000000000d49348)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (c000000000d60c2c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c000000000d62db8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (c000000000d66054)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (c000000000d6ffa4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d7155c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73100)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d7d158)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (c000000000d8550c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c000000000d9295c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (c000000000d95870)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c000000000d98cb0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (c000000000da1c40)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (c000000000da41a4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (c000000000da4990)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (c000000000da866c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dabdb4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/arp.c (c000000000db61d8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dc1eac)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (c000000000ddac34)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (c000000000df0a3c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (c000000000df55dc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe090)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (c000000000e13958)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (c000000000e234e8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (c000000000e24be0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ip6_fib.c (c000000000e46af8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (c000000000e5a420)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/tcp_ipv6.c (c000000000e684a4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (c000000000e72a9c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (c000000000e805b4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (c000000000e831d0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c000000000e8527c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f108)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c000000000e8fb80)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (c000000000e9b340)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (c000000000ebf2ec)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (ffffffe0000c1a4c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/futex.c (ffffffe00013d92e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffffffe00016803e)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffffffe00017ab28)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffffffe0001d0554)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffffffe00025e340)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffe00029f028)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0572)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffe000376262)
Location: include/linux/refcount.h:41
Inline: True
```
```
In security/keys/gc.c (ffffffe00038f1b2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffe000396648)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffe00040002c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffe000400e1e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffe0004c9096)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053bea2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffe000579638)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d4182)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (ffffffe000627c2c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffe0006efeba)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In drivers/of/dynamic.c (ffffffe000724920)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:of_changeset_destroy
```
```
In net/core/sock.c (ffffffe000740aea)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffe0007412c4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffe000744734)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/datagram.c (ffffffe00074a748)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffe00074dff8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffe00075892e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffe00076a928)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffe00078393c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffe000789546)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffe00078b046)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffe000791e8c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffe00079cc9c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffffffe0007ad75e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b170e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffe0007b83a4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffe0007c6bbc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c808e)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffe0007ca68c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d09ba)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d191e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2ebe)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d8b1c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffe0007de740)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7ac0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9974)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb89a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1916)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f324e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffe0007f37b4)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffe0007f5c86)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f7724)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/arp.c (ffffffe0007fea1e)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffe000806350)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffe0008158f2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffe0008238a0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008268fa)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b5ba)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffe00083cde0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffe00084664a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffe0008474ea)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d9b2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffffffe000869aa4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873714)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:reqsk_free
```
```
In net/ipv6/datagram.c (ffffffe00087a93e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffe0008839f2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffe00088577c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffe0008870f8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d8fa)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffe00088e18e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffe00089579c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffe0008ac214)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (ffffffff8109a610)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (ffffffff810daaf3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (ffffffff81143a7d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffffffff81177e28)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119b324)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffffffff8120f5da)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffffffff812deb4d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81325e85)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327fde)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff8141f475)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff8143ce48)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff81445843)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff814b8b7a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff814b96c7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffff815853b6)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816582f2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff816bf78a)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bd42)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (ffffffff817870f8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff8185127b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff818b601d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff818b6eb3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff818ba0bb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff818c1f50)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff818c5529)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818d0e2b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff818e4097)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff8190142c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff819069ec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff8190896b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffff819115a8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff8191ca86)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffffffff81930ba9)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819350b5)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff8193da4d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff8194de26)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f5f5)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81951f27)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959400)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a279)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bafc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81962a08)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81968d5f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819737a4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff819758d8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819774df)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e51f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197fec4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff8198040d)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81982982)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81984985)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff8198cdb6)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8199567b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff819a6977)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff819b5f91)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b948f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bf9a7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff819cfda1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff819da2ad)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff819db1f4)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3de8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a02dcc)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ce26)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a1506e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81a1e901)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81a2092d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a21d39)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28900)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a29114)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81a31c3a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81a4a526)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (ffffffff81089050)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (ffffffff810c9b03)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (ffffffff811368ad)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffffffff8116afc8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8118e3a4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffffffff8120236e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffffffff812cec81)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81316a25)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81318b7e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff8140fef5)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff8142d8b8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff81436293)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff814a959a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff814aa0e7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffff81574186)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81638682)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff8169aa3a)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f51a2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (ffffffff81766a48)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/vxlan.c (ffffffff81770b04)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_stop
```
```
In drivers/md/dm.c (ffffffff8181888b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff8186ff6d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff81870e03)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff8187400b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff8187be90)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff8187f469)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8188acef)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff8189ded7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff818bb25c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff818c081c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff818c277b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffff818cb368)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff818d6836)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffffffff818ea6a9)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818eebb5)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff818f754d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff81907916)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819090e5)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8190ba17)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912ef0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913d69)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819155ec)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8191c4f8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8192284f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8192d274)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f398)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930f9f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81937fdf)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939984)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81939ecd)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8193c442)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8193e445)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81946876)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8194f13b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81960437)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff81972d81)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197627f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c797)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff8198cb61)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff8199706d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81997fb4)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0ba8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffffffff819bfb8c)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9be6)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff819d1e2e)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff819db6c1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff819dd6ed)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819deaf9)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e56c0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819e6304)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff819eee2a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81a07116)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (ffffffff8109a5c0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (ffffffff810d6e73)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (ffffffff8114192d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffffffff81175bf8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811990f4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffffffff8120d37a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffffffff812dc95d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81323955)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325aae)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff8141b615)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff81438fe8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff814418e3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff814b4c0a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff814b5757)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffff81585276)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816866b2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff816edc5a)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175ab12)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (ffffffff817b74a8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff818a08ab)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff8190701d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff81907eb3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff8190b0bb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81912f50)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81916529)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81921e2b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff819350c7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff8195245c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81957a1c)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff8195999b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffff819625d8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff8196dc16)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffffffff81981d39)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81986245)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff8198ebdd)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b615)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:seq_show
```
```
In net/ipv4/ip_input.c (ffffffff819b85f6)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9dc5)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819bc6f7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3bd0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a49)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c62cc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819cd1d8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff819d352f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819ddf74)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff819e00a8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1caf)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8cef)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea694)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff819eabdd)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819ed152)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819ef155)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff819f763a)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819fff1b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a11217)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff81a20831)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23f0f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a427)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff81a3a821)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff81a44d2d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a45c74)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e868)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a6d84c)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a778a6)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a7faee)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81a89381)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81a8b3ad)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a8c7b9)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a944b0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a94cc4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81a9d7ea)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81ab63d6)
Location: include/linux/refcount.h:41
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
In kernel/fork.c (ffffffff810a2240)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:free_task
```
```
In kernel/sched/fair.c (ffffffff810e2823)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/futex.c (ffffffff8114d15d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/audit_tree.c (ffffffff811833b8)
Location: include/linux/refcount.h:41
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a6d54)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/events/core.c (ffffffff8121c21a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_mmap_close
```
```
In fs/exec.c (ffffffff812ed707)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81335695)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337809)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/fuse/file.c (ffffffff81432205)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In security/keys/gc.c (ffffffff8145014d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/proc.c (ffffffff81458c13)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In crypto/algapi.c (ffffffff814cd68a)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
```
```
In crypto/proc.c (ffffffff814ce1f7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In drivers/pci/slot.c (ffffffff8159f726)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a0cb2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/base/core.c (ffffffff8170849a)
Location: include/linux/refcount.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817760f2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/net/tun.c (ffffffff817cf549)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/md/dm.c (ffffffff818bcad2)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
```
```
In net/core/sock.c (ffffffff8192804d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/request_sock.c (ffffffff81928ef3)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff8192c1bb)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff819340d0)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/net_namespace.c (ffffffff81937729)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81943b2b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff819567d7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/sock_reuseport.c (ffffffff81973ea7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/net-sysfs.c (ffffffff81979afc)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/skmsg.c (ffffffff8197bbc4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/net-traces.c (ffffffff81984848)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/devlink.c (ffffffff81990066)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_destroy
```
```
In net/sched/sch_api.c (ffffffff819a4279)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a9245)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/netlink/af_netlink.c (ffffffff819b149d)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/ip_input.c (ffffffff819c1e56)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3805)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819c6007)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd623)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce4d6)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfde8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819d6d68)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff819dd0d6)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819e7bf4)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9d68)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb9ff)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2a4f)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4500)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff819f4a5d)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819f7032)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f9945)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:__first_packet_length
```
```
In net/ipv4/arp.c (ffffffff81a0185f)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81a0a04b)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a1bb87)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
```
```
In net/ipv4/syncookies.c (ffffffff81a2bd31)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2f371)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a359b7)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
```
```
In net/unix/af_unix.c (ffffffff81a45671)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
```
```
In net/ipv6/ip6_output.c (ffffffff81a509ed)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81a5194c)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6ace8)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a79e6c)
Location: include/linux/refcount.h:41
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84016)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81a8c3ae)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/netfilter.c (ffffffff81a95fe1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/syncookies.c (ffffffff81a97fc1)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a99538)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa05f6)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81aa0e14)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/8021q/vlan_core.c (ffffffff81aa99ea)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/xdp/xsk.c (ffffffff81ac24f6)
Location: include/linux/refcount.h:41
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
