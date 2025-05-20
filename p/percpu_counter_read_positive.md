# Function: <code>percpu_counter_read_positive</code>

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
In mm/page-writeback.c (ffffffff81199f3d)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
```
```
In mm/backing-dev.c (ffffffff811ae64d)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/mmap.c (ffffffff811c3ec0)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/mmap.c:vm_memory_committed
  - mm/mmap.c:__vm_enough_memory
```
```
In fs/file_table.c (ffffffff8120e0b7)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff812705f0)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff8128265e)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff8128ee16)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff812930ab)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8129618c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/ext4/extents_status.c (ffffffff812daba7)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:ext4_es_scan
```
```
In lib/flex_proportions.c (ffffffff813e9976)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_single
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
```
```
In net/core/sock.c (ffffffff81702be8)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/core/dst.c (ffffffff817238d0)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff8176a180)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff817d3e5c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fbc7c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_garbage_collect
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
In mm/page-writeback.c (ffffffff811b0501)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
```
```
In mm/util.c (ffffffff811c4f20)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff811c79b0)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81234ae7)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff8129c980)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff812af70e)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff812bc346)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff812c0664)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812c377c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/ext4/extents_status.c (ffffffff8130b055)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In lib/flex_proportions.c (ffffffff8142fe53)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/sock.c (ffffffff81768051)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/core/dst.c (ffffffff8178d330)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff817d6c20)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff8184185c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b54c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_garbage_collect
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
In mm/page-writeback.c (ffffffff811c0bc1)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
```
```
In mm/util.c (ffffffff811d5030)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff811d7acd)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81247697)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff812b2340)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff812c519a)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff812d1996)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff812d5c94)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812d8e2c)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/ext4/extents_status.c (ffffffff81321055)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In lib/flex_proportions.c (ffffffff8144c083)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/sock.c (ffffffff8179503e)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff817bac00)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff81806c40)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff818736dc)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e3ac)
Location: include/linux/percpu_counter.h:77
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_garbage_collect
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
In mm/page-writeback.c (ffffffff811c8d04)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
```
```
In mm/util.c (ffffffff811dde80)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff811e06da)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81252ea7)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff812bf820)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff812d23da)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff812e3006)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff812f0028)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff812f3f15)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff812fd0cc)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff817b36a7)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff817d9c43)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff81827252)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81898124)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4c1b)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_garbage_collect
```
```
In lib/flex_proportions.c (ffffffff818ec833)
Location: include/linux/percpu_counter.h:78
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff811ddb64)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff811f3900)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff811f66ca)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81274fa7)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff812e3250)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff812f6c1a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81307a36)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81314b28)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff81318655)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813219ac)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff8182ba98)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81854273)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff818a6052)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff819194d4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81972803)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff811ff0ac)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff81214c26)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff812179aa)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff8129b867)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff8130fd7d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff81323f91)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81335926)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81342958)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff8134648b)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8134f9fc)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff81875602)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff8189f973)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff818fb0f0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81970fd4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff819cec2a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff81211967)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff81227b02)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff8122a8ba)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff812b0ead)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff81326d0d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff8133b0e1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff8134cba6)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff8135a428)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff8135e781)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81367bec)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff81895ee3)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff818c24b3)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff81929020)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff819a6c14)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81a080ea)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff81220fb1)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff81237829)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff8123a520)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff812cd79d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff8134e89d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff813632a1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813755c6)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81383484)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff81387964)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81390eda)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff818e03f1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff8190ec22)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198bf30)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81a13184)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81a77a43)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff8122ea61)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff81245a79)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff8124882a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff812df1bd)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff81366b8d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff8137b501)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff8138d843)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff8139b964)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff813a0238)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813a989a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff819125b1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81941292)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c2880)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81a49d74)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81aaee33)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff8125bc31)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff812737b8)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff81277035)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81315a55)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff813ae6f5)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff813c4836)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813d8cd5)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813e6d16)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff813ec311)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813f55dd)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In lib/flex_proportions.c (ffffffff815e8b9f)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/sock.c (ffffffff819e44cd)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81a10f31)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff81aade31)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81b40871)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff81266051)
Location: include/linux/percpu_counter.h:80
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
In mm/util.c (ffffffff8127e048)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/backing-dev.c (ffffffff8128191f)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81320f85)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff813bfce5)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/ext4/balloc.c (ffffffff813ea8e5)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813f9021)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff813fe551)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81407d7d)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In lib/flex_proportions.c (ffffffff8160dc54)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/sock.c (ffffffff819e3d54)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81a112e1)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff81ab80c1)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81b4f331)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff8126ab4c)
Location: include/linux/percpu_counter.h:80
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
In mm/util.c (ffffffff812831b8)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/backing-dev.c (ffffffff812867d0)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81327375)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff813c6b95)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/ext4/balloc.c (ffffffff813f0e05)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813ff74c)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff81404946)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8140e0ed)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In lib/flex_proportions.c (ffffffff815f13a4)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/sock.c (ffffffff819c9de4)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff819f8151)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/tcp.c (ffffffff81aa33fe)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81b3d060)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff812a7a92)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
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
In mm/util.c (ffffffff812c1378)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/backing-dev.c (ffffffff812c5b50)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff81374645)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff81416f15)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/ext4/balloc.c (ffffffff81442d55)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81451d5c)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff81457122)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff81460fbd)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/jbd2/journal.c (ffffffff814bda25)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In lib/flex_proportions.c (ffffffff8165e514)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/sock.c (ffffffff81a791e5)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81aa9dc1)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv6/route.c (ffffffff81c038f8)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff813000bc)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
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
In mm/util.c (ffffffff8131e364)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/backing-dev.c (ffffffff81323011)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff813f3a55)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff8148e6a5)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/ext4/balloc.c (ffffffff814beb55)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff814cf01c)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff814d4bec)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff814dfd4d)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/jbd2/journal.c (ffffffff81549145)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In lib/flex_proportions.c (ffffffff81777c84)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In net/core/sock.c (ffffffff81bed6fd)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81c2226d)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv6/route.c (ffffffff81d9d943)
Location: include/linux/percpu_counter.h:80
Inline: True
Inline callers:
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
In kernel/fork.c (ffffffff810e7239)
Location: include/linux/percpu_counter.h:99
Inline: True
```
```
In kernel/exit.c (ffffffff810f1a0e)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff8110e1a6)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff811434fd)
Location: include/linux/percpu_counter.h:99
Inline: True
```
```
In kernel/tsacct.c (ffffffff8124fb93)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff813647c2)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/page-writeback.c (ffffffff8136aa0c)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
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
In mm/vmscan.c (ffffffff813771e6)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
```
```
In mm/util.c (ffffffff81391ddc)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/backing-dev.c (ffffffff81397811)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/memory.c (ffffffff813ba329)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff813c65d4)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff813d9481)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f3080)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/file_table.c (ffffffff8147c875)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/exec.c (ffffffff8148390c)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/quota/dquot.c (ffffffff81521f95)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/task_mmu.c (ffffffff8152d0f2)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff8153ba1f)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/balloc.c (ffffffff81556a35)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff815678cc)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff8156d8bd)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8157900d)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/jbd2/journal.c (ffffffff815e8b45)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In net/core/sock.c (ffffffff81d9dc46)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81dd461d)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/ipv6/route.c (ffffffff81f6c883)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff82020964)
Location: include/linux/percpu_counter.h:99
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/fork.c (ffffffff810f2d49)
Location: include/linux/percpu_counter.h:98
Inline: True
```
```
In kernel/exit.c (ffffffff810fd991)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff8111a26d)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff81152616)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81266f43)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81396c9d)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/page-writeback.c (ffffffff8139cb9c)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
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
In mm/vmscan.c (ffffffff813a9237)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
```
```
In mm/util.c (ffffffff813c47dc)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/backing-dev.c (ffffffff813ca7a1)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/memory.c (ffffffff813eecd3)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
```
```
In mm/mmap.c (ffffffff813facdd)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8140db72)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81426adf)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/file_table.c (ffffffff814b14b5)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/exec.c (ffffffff814b91c7)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/quota/dquot.c (ffffffff81559fd5)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/task_mmu.c (ffffffff81564e2b)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff81573d4a)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/balloc.c (ffffffff8158e7f5)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff8159fa9c)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff815a57a4)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff815b043d)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/jbd2/journal.c (ffffffff816204b5)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In io_uring/io_uring.c (ffffffff817d0fac)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In net/core/sock.c (ffffffff81e0c4c8)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81e453f2)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In lib/flex_proportions.c (ffffffff820a09a4)
Location: include/linux/percpu_counter.h:98
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/fork.c (ffffffff810fb8a9)
Location: include/linux/percpu_counter.h:118
Inline: True
```
```
In kernel/exit.c (ffffffff8110680c)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff81123beb)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff8115e5c6)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81280ed3)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff813c0a0d)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/page-writeback.c (ffffffff813c687c)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
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
In mm/util.c (ffffffff813ef25c)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/backing-dev.c (ffffffff813f5217)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/memory.c (ffffffff8141a783)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
```
```
In mm/mmap.c (ffffffff81426d15)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8143a2cc)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8146071f)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/file_table.c (ffffffff814e2c85)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:alloc_empty_file
  - fs/file_table.c:proc_nr_files
```
```
In fs/exec.c (ffffffff814eb9b7)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/quota/dquot.c (ffffffff81590795)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/task_mmu.c (ffffffff8159b8ea)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff815ac719)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/balloc.c (ffffffff815c7505)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff815d86d3)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff815de614)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff815e922d)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In fs/jbd2/journal.c (ffffffff81659493)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In io_uring/io_uring.c (ffffffff81813ae9)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In net/core/sock.c (ffffffff81ec8e7b)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81f0405e)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In lib/flex_proportions.c (ffffffff82178984)
Location: include/linux/percpu_counter.h:118
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffff8000102bdafc)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffff8000102d910c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffff8000102ddd0c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffff8000103859e0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffff80001042e3c0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffff800010447c98)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffff80001045f7c0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffff80001046e698)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffff80001047375c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffff80001047d594)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffff800010bacc34)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffff800010be0c8c)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c7558c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffff800010d0cf7c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffff800010d885c0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (c04e9e60)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (c0500288)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (c0502f14)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (c056e8a4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (c05f7790)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (c060cb68)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (c061fef4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (c062fc24)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (c0634dd4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (c063f02c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (c0cc8790)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (c0cfb0ac)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (c0d83cc0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (c0e1372c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (c0e833e4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (c000000000376820)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (c000000000398c88)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (c00000000039d108)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (c00000000047bbac)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (c00000000053f880)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (c00000000055e064)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (c00000000057b9d0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (c00000000058e85c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (c000000000594b84)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (c0000000005a1a94)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (c000000000c7fb1c)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (c000000000cc1e98)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7cc38)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (c000000000e38810)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (c000000000ec8c84)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffe0001e06dc)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffe0001f351a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffe0001f5d84)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffe000258680)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffe0002cac48)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffe0002dd8ac)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffe0002eef92)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffe0002fb5dc)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffe0002ff574)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffe000307192)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffe00073d61a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffe000767322)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d8846)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffe0008548bc)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffe0008b2624)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff812270b1)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff8123e0c9)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff81240e7a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff812d779d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff8135f16d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff81373ae1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81385e23)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff81393f44)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff81398818)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813a1e7a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff818b25b1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff818e1262)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819626f0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff819e9404)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81a4dc83)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff8121a221)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff812310c9)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff81233e7a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff812c841d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff8134fe0d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff813645b1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813768b3)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813849d4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff813892a8)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8139290a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff8186c501)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff8189b0a2)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191c1e0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff819a61c4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81a0ad73)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff81224e51)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff8123be69)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff8123ec1a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff812d55ad)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff8135cc3d)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff813715b1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff813838f3)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813918a4)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff81396078)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff8139f6da)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff819035b1)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81932292)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819ccec0)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81a53e84)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81aba073)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In mm/page-writeback.c (ffffffff81234121)
Location: include/linux/percpu_counter.h:79
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
In mm/util.c (ffffffff8124b579)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_memory_committed
```
```
In mm/backing-dev.c (ffffffff8124e347)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In fs/file_table.c (ffffffff812e63fd)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/file_table.c:proc_nr_files
```
```
In fs/quota/dquot.c (ffffffff813704ad)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_count
```
```
In fs/proc/meminfo.c (ffffffff81384f91)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/ext4/balloc.c (ffffffff81397413)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff813a5754)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
```
```
In fs/ext4/ialloc.c (ffffffff813aa2d8)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/inode.c (ffffffff813b3d7a)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_nonda_switch
  - fs/ext4/inode.c:ext4_nonda_switch
```
```
In net/core/sock.c (ffffffff81924591)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/dst.c (ffffffff81953962)
Location: include/linux/percpu_counter.h:79
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d6a50)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_check_oom
```
```
In net/ipv6/route.c (ffffffff81a5fe74)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In lib/flex_proportions.c (ffffffff81ac64c3)
Location: include/linux/percpu_counter.h:79
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
</details>
</li>
</ul>

## Differences
