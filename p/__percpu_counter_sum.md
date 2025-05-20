# Function: <code>__percpu_counter_sum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81411ac0)
Location: lib/percpu_counter.c:98
Inline: False
Direct callers:
  - mm/shmem.c:shmem_statfs
  - fs/file_table.c:get_empty_filp
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/cfq-iosched.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_offline
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/ip_fragment.c:ip_frag_mem
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/proc.c:sockstat6_seq_show
```
**Symbols:**

```
ffffffff81411ac0-ffffffff81411b33: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81459830)
Location: lib/percpu_counter.c:98
Inline: False
Direct callers:
  - mm/shmem.c:shmem_statfs
  - fs/file_table.c:get_empty_filp
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/ip_fragment.c:ip_frag_mem
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/proc.c:sockstat6_seq_show
```
**Symbols:**

```
ffffffff81459830-ffffffff814598a3: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814781f0)
Location: lib/percpu_counter.c:98
Inline: False
Direct callers:
  - mm/shmem.c:shmem_statfs
  - fs/file_table.c:get_empty_filp
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/ip_fragment.c:ip_frag_mem
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/proc.c:sockstat6_seq_show
```
**Symbols:**

```
ffffffff814781f0-ffffffff81478268: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81481530)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/shmem.c:shmem_statfs
  - fs/file_table.c:get_empty_filp
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81481530-ffffffff814815a6: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814bd380)
Location: lib/percpu_counter.c:106
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/file_table.c:get_empty_filp
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff814bd380-ffffffff814bd3e9: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814efbe0)
Location: lib/percpu_counter.c:106
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/file_table.c:get_empty_filp
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_read
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff814efbe0-ffffffff814efc49: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81503b00)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_rwstat_read
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81503b00-ffffffff81503b69: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81531c50)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81531c50-ffffffff81531cb2: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81552b00)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81552b00-ffffffff81552b62: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dbee0)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/file_table.c:alloc_empty_file
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
**Symbols:**

```
ffffffff815dbee0-ffffffff815dbf42: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815f9b40)
Location: lib/percpu_counter.c:124
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - mm/util.c:vm_memory_committed
  - fs/file_table.c:alloc_empty_file
  - fs/io_uring.c:tctx_inflight
  - fs/io_uring.c:tctx_inflight
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/inode.c:ext4_print_free_blocks
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
**Symbols:**

```
ffffffff815f9b40-ffffffff815f9ba2: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc730)
Location: lib/percpu_counter.c:124
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - mm/util.c:vm_memory_committed
  - fs/file_table.c:alloc_empty_file
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
**Symbols:**

```
ffffffff815dc730-ffffffff815dc796: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81648040)
Location: lib/percpu_counter.c:124
Inline: False
Direct callers:
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
  - mm/shmem.c:shmem_statfs
  - mm/util.c:vm_memory_committed
  - fs/file_table.c:alloc_empty_file
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
**Symbols:**

```
ffffffff81648040-ffffffff816480da: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8175e460)
Location: lib/percpu_counter.c:124
Inline: False
Direct callers:
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
  - mm/shmem.c:shmem_statfs
  - mm/util.c:vm_memory_committed
  - fs/file_table.c:alloc_empty_file
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - lib/percpu_counter.c:__percpu_counter_compare
  - lib/flex_proportions.c:fprop_new_period
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
**Symbols:**

```
ffffffff8175e460-ffffffff8175e508: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8188bd2b)
Location: lib/percpu_counter.c:141
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
Direct callers:
  - kernel/fork.c:__mmdrop
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
  - mm/shmem.c:shmem_statfs
  - mm/util.c:vm_memory_committed
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
  - fs/file_table.c:alloc_empty_file
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8188bcb0-ffffffff8188bcca: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff818ce1f0)
Location: lib/percpu_counter.c:137
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/bpf/hashtab.c:htab_map_mem_usage
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
  - mm/shmem.c:shmem_statfs
  - mm/util.c:vm_memory_committed
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
  - fs/file_table.c:alloc_empty_file
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - lib/percpu_counter.c:__percpu_counter_compare
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff818ce1f0-ffffffff818ce2a6: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8191fe20)
Location: lib/percpu_counter.c:137
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/bpf/hashtab.c:htab_map_mem_usage
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
  - mm/shmem.c:shmem_statfs
  - mm/util.c:vm_memory_committed
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
  - fs/file_table.c:alloc_empty_file
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_prfill_rwstat
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - lib/percpu_counter.c:__percpu_counter_compare
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8191fe20-ffffffff8191fed6: __percpu_counter_sum (STB_GLOBAL)
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
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffff80001065eda8)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffff80001065eda8-ffff80001065ee8c: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c08083b8)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
c08083b8-c0808434: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c0000000008113b0)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
c0000000008113b0-c000000000811480: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffe00048c3c6)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffe00048c3c6-ffffffe00048c452: __percpu_counter_sum (STB_GLOBAL)
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
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8154b0e0)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8154b0e0-ffffffff8154b142: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8153b3c0)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8153b3c0-ffffffff8153b422: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81546e20)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81546e20-ffffffff81546e82: __percpu_counter_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81560d00)
Location: lib/percpu_counter.c:105
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/shmem.c:shmem_statfs
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_rwstat_field
  - block/blk-cgroup.c:blkg_prfill_rwstat
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81560d00-ffffffff81560d62: __percpu_counter_sum (STB_GLOBAL)
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
