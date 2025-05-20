# Function: <code>percpu_counter_sum_positive</code>

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
In mm/page-writeback.c (ffffffff8119a172)
Location: include/linux/percpu_counter.h:56
Inline: True
```
```
In fs/file_table.c (ffffffff8120e19c)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff81270d73)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff8128ef50)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/super.c (ffffffff812ac3ad)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/extents_status.c (ffffffff812dc2c2)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In block/blk-cgroup.c (ffffffff813d7178)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/cfq-iosched.c (ffffffff813de125)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - block/cfq-iosched.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_offline
```
```
In net/ipv4/route.c (ffffffff8175415e)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a68c)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/tcp.c (ffffffff8176a203)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff817a5f8b)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af42a)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff817d3ed7)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_stats_seq_show
```
```
In net/ipv6/proc.c (ffffffff817feaf0)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
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
In mm/page-writeback.c (ffffffff811aea7a)
Location: include/linux/percpu_counter.h:56
Inline: True
```
```
In fs/file_table.c (ffffffff81234bcc)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff8129d273)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff812bc47f)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/super.c (ffffffff812e1153)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/extents_status.c (ffffffff8130bbf2)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In block/blk-cgroup.c (ffffffff8141df2f)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff81428e9a)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In net/ipv4/route.c (ffffffff817c020e)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6a4c)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/tcp.c (ffffffff817d6c80)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81813c2b)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c32a)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff81842e9d)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/proc.c (ffffffff8186e47a)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
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
In mm/page-writeback.c (ffffffff811bf134)
Location: include/linux/percpu_counter.h:56
Inline: True
```
```
In fs/file_table.c (ffffffff8124777c)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812b2bb3)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff812d1acf)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/super.c (ffffffff812f6c83)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/extents_status.c (ffffffff81321bef)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In block/blk-cgroup.c (ffffffff814394ef)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff81440e9a)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In net/ipv4/route.c (ffffffff817ef5be)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817f654c)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/tcp.c (ffffffff81806ca0)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81845128)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184dbea)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff81874c1a)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/proc.c (ffffffff818a1347)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
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
In mm/page-writeback.c (ffffffff811c6f76)
Location: include/linux/percpu_counter.h:57
Inline: True
```
```
In fs/file_table.c (ffffffff81252f7f)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812c0063)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff812e314a)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff812f0b40)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8132b563)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff81446c7c)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff81450178)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In net/ipv4/route.c (ffffffff8180f47b)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff818272b6)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81866c9d)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8187164b)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/ipv6/route.c (ffffffff81898577)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff811dbd9e)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff8127507f)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812e39e3)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff81307b78)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81315670)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8134f9c3)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff8147385c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff8147eb38)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In net/ipv4/route.c (ffffffff8188eadb)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff818a60b6)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff818e6e3d)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81919977)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff811fd690)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff8129b93f)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff81310334)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff81335a75)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff8134347a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813833fc)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff814a7896)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff814b2b15)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In net/ipv4/route.c (ffffffff818e2774)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff818fb152)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff8193d91d)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81971457)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff812101ad)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff812b0ba7)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/quota/dquot.c (ffffffff813272c4)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff8134ccf5)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff8135b09a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8139be1c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff814c1a23)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In net/ipv4/route.c (ffffffff8190f614)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff8192908c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff8196d7bd)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff819a6d77)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff8121f7d2)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff812cd522)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/quota/dquot.c (ffffffff8134ee65)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:do_proc_dqstats
```
```
In fs/ext4/balloc.c (ffffffff81375715)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813840ba)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813c4967)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff814f005f)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffffffff8197181b)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff8198bf97)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff819d709d)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81a132e7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff8122d27a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff812def42)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8138d95c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff8139cc0a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813ddce7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff8150950f)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffffffff819a821b)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff819c28e7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81a0db8d)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81a49ed7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff8125ae2e)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff81315ac2)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff813d8e0c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813e834a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff81427647)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff8156c41f)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81a90ffb)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff81aade92)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81afebad)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81b40a37)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff81264fc4)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/util.c (ffffffff8127d615)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/util.c:vm_memory_committed
```
```
In fs/file_table.c (ffffffff81320ff2)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff813eaa2c)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813fa5fa)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8143f43a)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff815871eb)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81a9ae5b)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff81ab8122)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81b0cc1d)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81b4f4e7)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff812691fa)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/util.c (ffffffff812827a5)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/util.c:vm_memory_committed
```
```
In fs/file_table.c (ffffffff813273e0)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff813f0f47)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff814009ba)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8144a4a7)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff8158e031)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81a861ba)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff81aa345b)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81afa75d)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81b3d217)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff812a787f)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/util.c (ffffffff812c08c5)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/util.c:vm_memory_committed
```
```
In fs/file_table.c (ffffffff813746b0)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff81442ea0)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81452fca)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8149df61)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff815f3bc4)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81b409fa)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/proc.c (ffffffff81bbb58c)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81c03ad7)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff812ffed1)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/util.c (ffffffff8131d4a5)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - mm/util.c:vm_memory_committed
```
```
In fs/file_table.c (ffffffff813f3ac6)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff814becca)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff814d04f8)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff81522561)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff816a52dc)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81ccd473)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/proc.c (ffffffff81d4f66c)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81d9db69)
Location: include/linux/percpu_counter.h:59
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff8136a7d1)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/util.c (ffffffff81390e75)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - mm/util.c:vm_memory_committed
```
```
In mm/slab_common.c (ffffffff813a0024)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
```
In fs/file_table.c (ffffffff8147c8e6)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff81556baa)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81568e68)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff815bf381)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff81764168)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81e8d5a3)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/proc.c (ffffffff81f192ac)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81f6cb09)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff8139c961)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/util.c (ffffffff813c3785)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/util.c:vm_memory_committed
```
```
In mm/slab_common.c (ffffffff813d32e4)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
```
In fs/file_table.c (ffffffff814b154d)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff8158e96a)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff815a0b14)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff815f6541)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff817a3250)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81eebcc3)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/proc.c (ffffffff81f78f5c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81fccb99)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff813c6641)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/util.c (ffffffff813ee345)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - mm/util.c:vm_memory_committed
```
```
In mm/slab_common.c (ffffffff813fdce4)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
```
In fs/file_table.c (ffffffff814e2d1d)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/ext4/balloc.c (ffffffff815c767a)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff815d9824)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8162ee41)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
```
```
In block/blk-cgroup-rwstat.c (ffffffff817e6da0)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
```
```
In net/ipv4/route.c (ffffffff81fafd13)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/proc.c (ffffffff8203f61c)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff8209a379)
Location: include/linux/percpu_counter.h:97
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffff8000102bbbc0)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffff8000103853b0)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (ffff80001045f8c8)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffff80001046fc78)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffff8000104b8350)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffff80001060c1ec)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffff800010c57a08)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffff800010c7560c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffff800010cc778c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffff800010d0d100)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (c04e8710)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (c056e4e4)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (c06200ec)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (c06311d8)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (c06758ac)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (c07b73c0)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (c0d676c0)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (c0d83d48)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (c0dd2cc4)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (c0e138d4)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (c000000000374540)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (c00000000047b7b0)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (c00000000057bb60)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (c0000000005901a8)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (c0000000005e562c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (c0000000007a912c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (c000000000d59294)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (c000000000d7cd0c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (c000000000de45e0)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (c000000000e38a70)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffe0001deec8)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffe000258404)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (ffffffe0002ef06a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffe0002fc5e6)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffe0003315da)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffe0004451b4)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffffffe0007c1c6a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffe0007d88b2)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffe00081bcb2)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffe000854a1c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff812258ca)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff812d7522)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81385f3c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813951ea)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813d62c7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff81501aef)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffffffff8194808b)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff81962757)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff819ad92d)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff819e9567)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff81218a6a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff812c81a2)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813769cc)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81385c7a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813c6d47)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff814f1fff)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffffffff81901b7b)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff8191c247)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81969f5d)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff819a6327)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff8122366a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff812d5332)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81383a0c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81392b4a)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813d3757)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff814fdb7f)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffffffff819b285b)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff819ccf27)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81a181cd)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81a53fe7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
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
In mm/page-writeback.c (ffffffff81232864)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/file_table.c (ffffffff812e6182)
Location: include/linux/percpu_counter.h:58
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8139752c)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813a6b25)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813e4757)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In block/blk-cgroup.c (ffffffff81517145)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/route.c (ffffffff819bbf1b)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/tcp.c (ffffffff819d6ab7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv4/proc.c (ffffffff81a22c4d)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/route.c (ffffffff81a5ffd7)
Location: include/linux/percpu_counter.h:58
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
```
</details>
</li>
</ul>

## Differences
