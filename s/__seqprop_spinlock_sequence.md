# Function: <code>__seqprop_spinlock_sequence</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e57b3)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff8118c27b)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In mm/filemap.c (ffffffff81258766)
Location: include/linux/seqlock.h:277
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bec28)
Location: include/linux/seqlock.h:277
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cf6ef)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812e796d)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff8132dfa9)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8133f7de)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81349641)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81361094)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff81380d5a)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
```
```
In block/badblocks.c (ffffffff8157882e)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8158c327)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff8196ce2a)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81a144c9)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a29fd6)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1584)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81aa54d6)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab04b3)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7b7b)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ae6938)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81b035ed)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c658)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1c31b)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ae46)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sched/cputime.c (ffffffff810e7783)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff8118e760)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff8125cdf0)
Location: include/linux/seqlock.h:277
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c3cad)
Location: include/linux/seqlock.h:277
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d693a)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812ef0dd)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff813345f5)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81345c5e)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81350021)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81367b74)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff81388602)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff8158057e)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff815931e7)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff8194f90c)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff819fae58)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a11226)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c4d4)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81a90596)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b691)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2d1b)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad1c09)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81aeee2d)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa2c8)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a00b)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b188e5)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b28a76)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sched/cputime.c (ffffffff810fee23)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff811b7570)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff81298d6a)
Location: include/linux/seqlock.h:277
Inline: True
```
```
In mm/page_alloc.c (ffffffff81307b46)
Location: include/linux/seqlock.h:277
Inline: True
```
```
In mm/hugetlb.c (ffffffff8131c6fa)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813373e7)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81381f3d)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8139387b)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8139e3e1)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff813b6724)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff813d5943)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff815e589e)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff815fa497)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff819f4d8c)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81aaca98)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81ac7782)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/inetpeer.c (ffffffff81b47614)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81b4c16d)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56cc1)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b808cc)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81b90859)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81baf1fd)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbafc8)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcce2b)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdccd5)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81bef15e)
Location: include/linux/seqlock.h:277
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/build_policy.c (ffffffff81139706)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff811ea2cf)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff812ef5dd)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In mm/page_alloc.c (ffffffff8136fcc4)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In mm/hugetlb.c (ffffffff813878e6)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813a8cfe)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81403c40)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81415071)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81421586)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff8143bd1a)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff8145fb38)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff8169496e)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff816ac827)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff81b5e99b)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81c25a02)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c3d2d2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81cd481b)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81cd8d62)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3d45)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10ccb)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81d21d39)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81d4253c)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f0fb)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62c0b)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81d73a9e)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81d87012)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sched/build_policy.c (ffffffff81163ec6)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff812304af)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff8135a114)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In mm/page_alloc.c (ffffffff813ec338)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In mm/hugetlb.c (ffffffff81405d2f)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81429dcf)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff8148e0a4)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff814a057e)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814adab6)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff814ca34a)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff814efc02)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff817534ce)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8176b0c2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff81cf8889)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81dd7c42)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81df5102)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81e94afb)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81e996a2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6795)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6a4b)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ee9189)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81f0b3cc)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18cfb)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d7ab)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3fade)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81f54fb2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sched/build_policy.c (ffffffff811746a6)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff81246fd4)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff8138bb76)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In mm/page_alloc.c (ffffffff8142134f)
Location: include/linux/seqlock.h:275
Inline: True
```
```
In mm/hugetlb.c (ffffffff814392b2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/slub.c (ffffffff8145f1c1)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff814c37e7)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff814d58a8)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814e2896)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff8150058a)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff81526929)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff8178f68e)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff817aa1a2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff81d607b8)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81e46f66)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81e66af2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81ef32cb)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81ef7fa2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f061ca)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_sk_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35a81)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81f4827d)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff81f6afac)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78966)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8d47b)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f3fe)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81fb49c2)
Location: include/linux/seqlock.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sys.c (ffffffff81123adb)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_policy.c (ffffffff81182a7d)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff81260e4c)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff813b56e6)
Location: include/linux/seqlock.h:227
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144e0b7)
Location: include/linux/seqlock.h:227
Inline: True
```
```
In mm/slub.c (ffffffff8145a32e)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472de2)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In fs/namei.c (ffffffff814f5cb7)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81507c9c)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81516686)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff815351aa)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff8155aeee)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In fs/proc/base.c (ffffffff815a30d3)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff815ac3e7)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/badblocks.c (ffffffff817d1dee)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:_badblocks_check
```
```
In block/blk-iocost.c (ffffffff817edf62)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3e70)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time
```
```
In drivers/md/md.c (ffffffff81e18518)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81f05c26)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81f25ca2)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81fb725b)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81fbbff2)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbb31)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8200e3dd)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff820329f2)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f026)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205ae0b)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c75e)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff82082062)
Location: include/linux/seqlock.h:227
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
