# Function: <code>read_seqretry</code>

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
In kernel/sched/cputime.c (ffffffff810b19ab)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff810fc722)
Location: include/linux/seqlock.h:433
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff810fe733)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81128bc5)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff81216779)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:lookup_fast
```
```
In fs/dcache.c (ffffffff81223022)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_lookup
  - fs/dcache.c:is_subdir
```
```
In fs/namespace.c (ffffffff8122d839)
Location: include/linux/seqlock.h:433
Inline: True
```
```
In drivers/md/md.c (ffffffff8168dc63)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - drivers/md/md.c:md_is_badblock
  - drivers/md/md.c:badblocks_show
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff8172594c)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/ipv4/inetpeer.c (ffffffff81758597)
Location: include/linux/seqlock.h:433
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175d239)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763a23)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817813a1)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8178c570)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff817a18c9)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff817a283a)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5b1c)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b4713)
Location: include/linux/seqlock.h:433
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff817c53da)
Location: include/linux/seqlock.h:433
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
In kernel/sched/cputime.c (ffffffff810b445b)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81103a78)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81105ac0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81130d5d)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff8123eaae)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff8124ec35)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81256029)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In block/badblocks.c (ffffffff81413040)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff816f27d9)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81790743)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817c4877)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817ca006)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d02f1)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee86a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff817f9b7e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f596)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818100a3)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818137af)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818203e4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81831fcf)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810baa64)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff8110b165)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110d20c)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113aacd)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff8125187e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff81261c45)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81269419)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In block/badblocks.c (ffffffff8142e570)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81723ef8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff817bdff3)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817f4397)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f92be)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800131)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f27a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8182aa4e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81840ae6)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818415f3)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844cbc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81851c24)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81863f73)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810b5334)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff8110d055)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110f076)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff8113c0c8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff8125c66e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff8126f505)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81276bb9)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In block/badblocks.c (ffffffff8143b877)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8173c302)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff817dca5c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818147cb)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181969c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8182102a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fe33)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8184bc76)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818623d7)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81862e33)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8186681c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874da3)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff818894bd)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810bc4e4)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff811182d5)
Location: include/linux/seqlock.h:437
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8111a096)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81148e48)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812838b4)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
```
In fs/dcache.c (ffffffff81291e25)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812995f9)
Location: include/linux/seqlock.h:437
Inline: True
```
```
In block/badblocks.c (ffffffff81467887)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff817adeb2)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff8185762c)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818936bc)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897cc7)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fdea)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf1d9)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff818cb916)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818e24cd)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818e2f6b)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e69bc)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f5713)
Location: include/linux/seqlock.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff819099ad)
Location: include/linux/seqlock.h:437
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
In kernel/sched/cputime.c (ffffffff810c3bcc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81124e51)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81126b30)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff8115785f)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812aa852)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
```
In fs/dcache.c (ffffffff812b78cc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812bf455)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff812d3846)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff8149b6f4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff817f3f83)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff818a27ad)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818e77fa)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebfbc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f45bf)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914dc4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81921d61)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819398d4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d4e2)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194bbb1)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81960bd0)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810cce8c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81130551)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81132210)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff8116485f)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812bba22)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812cca2c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812d4665)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff812e91f6)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814b5a04)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8181feb3)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff818c598a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819146aa)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919d76)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922350)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943574)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81950b8a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81969564)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d2b2)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980fca)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81996eea)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810d526e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff8113b0a2)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113cb65)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff81171589)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812d7d40)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812e9625)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f1b75)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff81307a4c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814e3f47)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff818621ac)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff819119f9)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81976cdc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197beec)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984ae0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7b3d)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819b5480)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819d01b9)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6bda)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eada0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81a00cc1)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810df82e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81146cb2)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81148905)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff8117d409)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812e98c0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812fb1c5)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81303725)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff8131aacc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814fd307)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81893ddc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81944069)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819ad66c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b2892)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb550)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819debcd)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819ec1a0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a06d09)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d6ca)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21da0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81a37894)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810e7b80)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff8118f07f)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In fs/namei.c (ffffffff81321b45)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:choose_mountpoint
```
```
In fs/dcache.c (ffffffff81333ea0)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8133d495)
Location: include/linux/seqlock.h:473
Inline: True
```
```
In fs/d_path.c (ffffffff81354695)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff8155c782)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8196647e)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81a140d9)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a975fc)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9b6bc)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5e8c)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbbed)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad9f06)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81af6789)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe60a)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13982)
Location: include/linux/seqlock.h:473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c3ec)
Location: include/linux/seqlock.h:473
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
In kernel/sched/cputime.c (ffffffff810e5885)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff8118c2fa)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In fs/namei.c (ffffffff8132d102)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:choose_mountpoint
```
```
In fs/dcache.c (ffffffff8133f818)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff813493e5)
Location: include/linux/seqlock.h:858
Inline: True
```
```
In fs/d_path.c (ffffffff81360fe8)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff815788d4)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8196cece)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81a144f7)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a2a029)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81aa15c3)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5529)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab04cc)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7bad)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ae6a18)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81b03610)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c689)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21d15)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ae99)
Location: include/linux/seqlock.h:858
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
In kernel/sched/cputime.c (ffffffff810e7855)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff8118e7e4)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff81333d3f)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff81345c98)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8134fdc5)
Location: include/linux/seqlock.h:858
Inline: True
```
```
In fs/d_path.c (ffffffff81367ac7)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff81580624)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8194f9af)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff819fae86)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a11279)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c514)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a905e9)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b6aa)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2d4d)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad1ce9)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81aeee50)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa2f9)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f932)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81b28ac9)
Location: include/linux/seqlock.h:858
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
In kernel/sched/cputime.c (ffffffff810feef5)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff811b75f4)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff81381670)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff813938b5)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8139e165)
Location: include/linux/seqlock.h:858
Inline: True
```
```
In fs/d_path.c (ffffffff813b69d9)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff815e5943)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff819f4e2f)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81aacac6)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81ac77d9)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/inetpeer.c (ffffffff81b47654)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c1c4)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56cda)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b808fe)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81b90939)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81baf220)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbaff9)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2dc2)
Location: include/linux/seqlock.h:858
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81bef1b5)
Location: include/linux/seqlock.h:858
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
In kernel/sched/build_policy.c (ffffffff811397e4)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff811ea358)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff81405806)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff814150a6)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814212a5)
Location: include/linux/seqlock.h:854
Inline: True
```
```
In fs/d_path.c (ffffffff8143bfe2)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff81694a12)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81b5ea3e)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81c25a3c)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c3d319)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81cd485a)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd8da9)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3d67)
Location: include/linux/seqlock.h:854
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10d01)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81d21e1a)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81d4255f)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f11b)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6987a)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81d87059)
Location: include/linux/seqlock.h:854
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
In kernel/sched/build_policy.c (ffffffff81163fa4)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff81230538)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/page_alloc.c (ffffffff813ec254)
Location: include/linux/seqlock.h:854
Inline: True
```
```
In fs/namei.c (ffffffff8148fd2b)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:step_into
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff814a05b9)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814ad895)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
```
```
In fs/d_path.c (ffffffff814ca642)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff81753572)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81cf892c)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81dd7c7c)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81df5149)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81e94b3a)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e996e9)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea67b7)
Location: include/linux/seqlock.h:854
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6a81)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ee926a)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81f0b3ef)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18d1b)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34b8a)
Location: include/linux/seqlock.h:854
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81f54ff9)
Location: include/linux/seqlock.h:854
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
In kernel/sched/build_policy.c (ffffffff81174784)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff8124705b)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/page_alloc.c (ffffffff81421206)
Location: include/linux/seqlock.h:855
Inline: True
```
```
In fs/namei.c (ffffffff814c4f8b)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff814d58e3)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814e2675)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
```
```
In fs/d_path.c (ffffffff81500880)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (ffffffff8178f724)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81d60865)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81e46fbf)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81e66b39)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81ef330a)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef7fe9)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f061e9)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_sk_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35ab7)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81f482eb)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff81f6afcf)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78986)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f947aa)
Location: include/linux/seqlock.h:855
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4a09)
Location: include/linux/seqlock.h:855
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
In kernel/sys.c (ffffffff81123ddd)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_policy.c (ffffffff81182b71)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/auditsc.c (ffffffff81260ed4)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/page_alloc.c (ffffffff8144df7f)
Location: include/linux/seqlock.h:790
Inline: True
```
```
In fs/namei.c (ffffffff814f776b)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
```
```
In fs/dcache.c (ffffffff81507cd7)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81516465)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
```
```
In fs/d_path.c (ffffffff815354a0)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/proc/base.c (ffffffff815a31bb)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff815acb27)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/badblocks.c (ffffffff817d1e84)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:_badblocks_check
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3e83)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time
```
```
In drivers/md/md.c (ffffffff81e185c5)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81f05c7c)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81f25ce9)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81fb729a)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc039)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbb67)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8200e44b)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff82032a15)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f046)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061b9a)
Location: include/linux/seqlock.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff820820a9)
Location: include/linux/seqlock.h:790
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
In kernel/sched/cputime.c (ffff80001013f200)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffff8000101b1ae0)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffff8000101b5220)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffff8000101f2228)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffff800010392d58)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffff8000103aa58c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffff8000103b5cf4)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffff8000103d1c68)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffff8000105fe60c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffff800010ae89f8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffff800010be3ef0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffff800010c5d9c8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffff800010c637d4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6e1a0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91d64)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffff800010ca1c94)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffff800010cc0d9c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc71ec)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde13c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffff800010cfa444)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (c038f2a4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/jiffies.c (c03f282c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/jiffies.c:get_jiffies_64
```
```
In kernel/time/tick-common.c (c03fc2f0)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (c03fe6ac)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (c04326a0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (c05794b0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
```
```
In fs/dcache.c (c058b52c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c0595334)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (c05ac9d8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In block/badblocks.c (c07aa0e8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (c0bc9000)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/sock.c (c0ccc944)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/neighbour.c (c0cfe4ac)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (c0d6cda0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (c0d72c50)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (c0d7b05c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (c0da0a90)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (c0daead8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (c0dcbcd4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2474)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (c0de8338)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (c0dff594)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (c00000000018e3a0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (c000000000216cac)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (c000000000219f90)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (c0000000002669b8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (c00000000048c12c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (c0000000004a5548)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c0000000004b20a0)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (c0000000004d49d8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (c000000000798d30)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (c000000000bd1ac4)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (c000000000cc7460)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (c000000000d5fecc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (c000000000d66bb0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73d34)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (c000000000da23e8)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (c000000000db4f6c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (c000000000ddae18)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3e70)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (c000000000dfeb90)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (c000000000e1f468)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffe0000ed924)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffe00013a32a)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffe00013ae3e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffe000165944)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffe000261e22)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffe00027024a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffe00027987a)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffe00028d294)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffe00043a4b2)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffe0006dc88c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffe00076a9d0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffe0007c628c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cae1e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d28bc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1e0a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffe0007feca0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffe000815ff0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b784)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082de02)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffe000843e04)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810d9a1e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff8113f462)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81140f25)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff81175a29)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812e1ea0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812f37a5)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812fbd05)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff813130ac)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814f58e7)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff81839c5c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff818e4039)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff8194d4dc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952702)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b3c0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ea3d)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8198bfd0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819a6aa9)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad46a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c1430)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff819d6f24)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810c8cd7)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81131f92)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81133cc5)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff81168bc9)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812d2ae0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812e43d5)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812ec925)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff81303cbc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814e5df7)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff818012cc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff8189de79)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81906fcc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c1f2)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914eb0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819384fd)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81945a90)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81960569)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969a9a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e220)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81993ce4)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810d5d5e)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff8113d182)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113edd5)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff811737f9)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812dfcb0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff812f15b5)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f9af5)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff81310e9c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff814f1977)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff8188928c)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81935069)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819b7cac)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bced2)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5b90)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e920d)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819f67e0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a11349)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17d0a)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2beb0)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81a419a4)
Location: include/linux/seqlock.h:436
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
In kernel/sched/cputime.c (ffffffff810e1678)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/tick-common.c (ffffffff81149c72)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8114b945)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff8118103b)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In fs/namei.c (ffffffff812f1370)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/dcache.c (ffffffff81302777)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8130ae15)
Location: include/linux/seqlock.h:436
Inline: True
```
```
In fs/d_path.c (ffffffff81322724)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In block/badblocks.c (ffffffff8150a9d7)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/md/md.c (ffffffff818a69bc)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81956779)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819c1521)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c67e2)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf672)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2f6d)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81a00a07)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a1bcb9)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a227aa)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a37580)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d604)
Location: include/linux/seqlock.h:436
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
</ul>

## Differences
