# Function: <code>read_seqbegin</code>

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
In kernel/sched/cputime.c (ffffffff810b18fe)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff810fc711)
Location: include/linux/seqlock.h:428
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff810fe717)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81128b51)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff81218f7e)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff81222f11)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_lookup
  - fs/dcache.c:is_subdir
```
```
In fs/namespace.c (ffffffff8122d9d3)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In drivers/md/md.c (ffffffff8168dbb6)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - drivers/md/md.c:md_is_badblock
  - drivers/md/md.c:badblocks_show
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81725904)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/ipv4/inetpeer.c (ffffffff81758545)
Location: include/linux/seqlock.h:428
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175d1fa)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763a09)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781363)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8178c538)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1898)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff817a281e)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5b0a)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b46ec)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff817c539c)
Location: include/linux/seqlock.h:428
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffff810b43a3)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81103a6f)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81105aa3)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81130cea)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff8123df0c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff8124ec15)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812561cc)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In block/badblocks.c (ffffffff81412faf)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff816f2760)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81790712)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817c4825)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817c9fc7)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d02ce)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee830)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff817f9b4e)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f566)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81810087)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8181379a)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818203bc)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81831f91)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffff810ba9c3)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff8110b158)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110d1ef)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113aa5a)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff81250cec)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff81261c25)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812695bc)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In block/badblocks.c (ffffffff8142e4df)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81723e7f)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff817bdfc2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817f4345)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f9280)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180010e)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f240)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8182aa1e)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81840ab6)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818415d7)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844caa)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81851bfc)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81863f35)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffff810b5293)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff8110d048)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110f05e)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff8113c095)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff8125c3ca)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff8126f4e5)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81276d4f)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In block/badblocks.c (ffffffff8143b7e2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8173c289)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff817dca22)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81814775)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181965d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8182100d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fdfc)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8184bc2a)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818623a8)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81862e17)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8186680a)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874d7c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff8188947e)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffff810bc443)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff811182c8)
Location: include/linux/seqlock.h:432
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8111a07e)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81148e15)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff8127e82a)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff81291e05)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8129978f)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In block/badblocks.c (ffffffff814677f2)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff817ade39)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff818575f2)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81893684)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81897c88)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fdcd)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf1a7)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff818cb8ca)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2498)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818e2f4f)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e69aa)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f56ec)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff8190996e)
Location: include/linux/seqlock.h:432
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81124e48)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81126afd)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812a7716)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812b7898)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812bf633)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff8149b662)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff817f3ef0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff818a278f)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818e7c95)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f48eb)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914d9a)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81921d43)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819398bd)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d4da)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194bb9c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81130548)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811321dd)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812bc7bc)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812cc9f8)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812d4842)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814b5972)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8181fe20)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff818c596c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81914b45)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819226ae)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194354a)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81950b6c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff8196954d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d2aa)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980fb0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113cb49)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812d929c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812e95f4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f1d51)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814e3eb2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81862115)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff819119bf)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81976ca4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984e14)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7d36)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819b5439)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819d019d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6bc4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ead80)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811488e9)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812eadac)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812fb194)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81303911)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814fd272)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81893d45)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff8194402f)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819ad634)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb887)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819dedc2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819ec159)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a06ced)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d6b4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21d80)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In fs/namei.c (ffffffff81322337)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint
```
```
In fs/dcache.c (ffffffff81333e6f)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8133d6e1)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff8155c6e2)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff819663e7)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81a1409f)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a975c4)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81a9b663)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5f65)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbde4)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad9ebf)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81af676d)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe5f4)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13965)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c393)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In fs/namei.c (ffffffff8132d73e)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint
```
```
In fs/dcache.c (ffffffff8133f7de)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81349641)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff8157882e)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8196ce2a)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81a144c9)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a29fd6)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1584)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81aa54d6)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab05a5)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7da4)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ae6938)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81b035ed)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c658)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21cf5)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ae46)
Location: include/linux/seqlock.h:838
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
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff8118e760)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff813342eb)
Location: include/linux/seqlock.h:838
Inline: True
```
```
In fs/dcache.c (ffffffff81345c5e)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81350021)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81367a20)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff8158057e)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8194f90c)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff819fae58)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a11226)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c4d4)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81a90596)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b783)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2f1e)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad1c09)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81aeee2d)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa2c8)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f915)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81b28a76)
Location: include/linux/seqlock.h:838
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
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff811b7570)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff81381c3b)
Location: include/linux/seqlock.h:838
Inline: True
```
```
In fs/dcache.c (ffffffff8139387b)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8139e3e1)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff813b6283)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff815e589e)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff819f4d8c)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81aaca98)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81ac7780)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/inetpeer.c (ffffffff81b47614)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81b4c16b)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56db3)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80adb)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81b90859)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81baf1fd)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbafc8)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2da5)
Location: include/linux/seqlock.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81bef15c)
Location: include/linux/seqlock.h:838
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
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff811ea2cf)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff814058e5)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
```
```
In fs/dcache.c (ffffffff81415071)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81421586)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff8143b857)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff8169496e)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81b5e99b)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81c25a02)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c3d2d2)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81cd481b)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81cd8d62)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3d45)
Location: include/linux/seqlock.h:834
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10ccb)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81d21d39)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81d4253c)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f0fb)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6985a)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81d87012)
Location: include/linux/seqlock.h:834
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
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff812304af)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/page_alloc.c (ffffffff813ebe40)
Location: include/linux/seqlock.h:834
Inline: True
```
```
In fs/namei.c (ffffffff8148fc97)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
```
```
In fs/dcache.c (ffffffff814a057e)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814adab6)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff814c9e67)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff817534ce)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81cf8889)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81dd7c42)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81df5102)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81e94afb)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81e996a2)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6795)
Location: include/linux/seqlock.h:834
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6a4b)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ee9189)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81f0b3cc)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18cfb)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34b6a)
Location: include/linux/seqlock.h:834
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81f54fb2)
Location: include/linux/seqlock.h:834
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
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff81246fd4)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/page_alloc.c (ffffffff81420e33)
Location: include/linux/seqlock.h:835
Inline: True
```
```
In fs/namei.c (ffffffff814c509f)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
```
```
In fs/dcache.c (ffffffff814d58a8)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814e2896)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff815000a7)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff8178f68e)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81d607b8)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81e46f66)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81e66af2)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81ef32cb)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81ef7fa2)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f061ca)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_sk_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35a81)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81f4827d)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff81f6afac)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78966)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9478a)
Location: include/linux/seqlock.h:835
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81fb49c2)
Location: include/linux/seqlock.h:835
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
In kernel/sys.c (0)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_policy.c (ffffffff81182a7d)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff81260e4c)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/page_alloc.c (ffffffff8144dbfe)
Location: include/linux/seqlock.h:770
Inline: True
```
```
In fs/namei.c (ffffffff814f787f)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
```
```
In fs/dcache.c (ffffffff81507c9c)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81516686)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81534cc7)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/proc/base.c (ffffffff815a30d1)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff815ac3e5)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/badblocks.c (ffffffff817d1dee)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:_badblocks_check
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3e6e)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time
```
```
In drivers/md/md.c (ffffffff81e18518)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81f05c26)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81f25ca2)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81fb725b)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81fbbff2)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbb31)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8200e3dd)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff820329f2)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f026)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061b7a)
Location: include/linux/seqlock.h:770
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff82082062)
Location: include/linux/seqlock.h:770
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffff800010394454)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffff8000103aa568)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffff800010be1b74)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffff800010c5d998)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/jiffies.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/jiffies.c:get_jiffies_64
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (c0578a1c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (c058b504)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (c07aa048)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/sock.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/neighbour.c (c0cfcb70)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (c0d6cd60)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (c0d72bd4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (c00000000048a548)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (c0000000004a5520)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (c000000000d5fe98)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffe0000ed894)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffe00013a31a)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffe00013ae28)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffe0001659e4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffe000262fca)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffe000270220)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffe000279b78)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffe00028d220)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffe00043a452)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffe0006dc832)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffe00076a9ac)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffe0007c625e)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffe0007cade0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d28a2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1dd2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffe0007fec7c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffe000815fd8)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b76a)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dde2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffe000843dc6)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81140f09)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812e338c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812f3774)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812fbef1)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814f5852)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81839bc5)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff818e3fff)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff8194d4a4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b6f7)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ec32)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8198bf89)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819a6a8d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad454)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c1410)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81133ca9)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812d3fcc)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812e43a4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812ecb11)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814e5d62)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81801235)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff8189de3f)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81906f94)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819151e7)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819386f2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81945a49)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff8196054d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969a84)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e200)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113edb9)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812e119c)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff812f1584)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f9ce1)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814f18e2)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff818891f5)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff8193502f)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819b7c74)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5ec7)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9402)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819f6799)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a1132d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17cf4)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2be90)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:431
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8114b929)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812f01d7)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff81302744)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8130b026)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff8150a942)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff818a6925)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff8195673f)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819c14e9)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf9a9)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3162)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81a009c0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a1bc9d)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a22794)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a37560)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:431
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
</ul>

## Differences
