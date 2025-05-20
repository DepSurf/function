# Function: <code>inode_to_bdi</code>

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
In mm/filemap.c (ffffffff8118e0c2)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__generic_file_write_iter
```
```
In mm/page-writeback.c (ffffffff81198b64)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/readahead.c (ffffffff8119bd76)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:force_page_cache_readahead
```
```
In mm/vmscan.c (ffffffff811a09ef)
Location: include/linux/backing-dev.h:175
Inline: True
```
```
In mm/mmap.c (ffffffff811c5cfd)
Location: include/linux/backing-dev.h:175
Inline: True
```
```
In mm/fadvise.c (ffffffff811d1264)
Location: include/linux/backing-dev.h:175
Inline: True
```
```
In mm/migrate.c (ffffffff811f18eb)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff811fd349)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81202809)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81236ea0)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inode
```
```
In fs/ext4/super.c (ffffffff812b7f8f)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff81316fd7)
Location: include/linux/backing-dev.h:175
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/filemap.c (ffffffff811a27e6)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811adc69)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff811b14ef)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff811b6def)
Location: include/linux/backing-dev.h:176
Inline: True
```
```
In mm/mmap.c (ffffffff811e1b1e)
Location: include/linux/backing-dev.h:176
Inline: True
```
```
In mm/fadvise.c (ffffffff811ee404)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/migrate.c (ffffffff81210f41)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81220f09)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81226ec0)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81264125)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
```
```
In fs/ext4/super.c (ffffffff812e6c8f)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff8134ec4b)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff811b2626)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811be2b4)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff811c17e6)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff811c73ef)
Location: include/linux/backing-dev.h:176
Inline: True
```
```
In mm/mmap.c (ffffffff811f1b0d)
Location: include/linux/backing-dev.h:176
Inline: True
```
```
In mm/fadvise.c (ffffffff811fed54)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/swapfile.c (ffffffff81205321)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/migrate.c (ffffffff81223116)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81233659)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81239487)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81277565)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
```
```
In fs/ext4/super.c (ffffffff812fc83f)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff81364559)
Location: include/linux/backing-dev.h:176
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff811b9296)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811c75c5)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff811c9a86)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff811cfc1b)
Location: include/linux/backing-dev.h:151
Inline: True
```
```
In mm/mmap.c (ffffffff811fc814)
Location: include/linux/backing-dev.h:151
Inline: True
```
```
In mm/fadvise.c (ffffffff81209925)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/swapfile.c (ffffffff812109ab)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/migrate.c (ffffffff8122eb39)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff8123ef1f)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81244d4d)
Location: include/linux/backing-dev.h:151
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812848ff)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
```
```
In fs/ext4/super.c (ffffffff8133148f)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff81378d44)
Location: include/linux/backing-dev.h:151
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff811cf716)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811db074)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff811de946)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff811e5094)
Location: include/linux/backing-dev.h:153
Inline: True
```
```
In mm/mmap.c (ffffffff81214d70)
Location: include/linux/backing-dev.h:153
Inline: True
```
```
In mm/fadvise.c (ffffffff81222a38)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
```
```
In mm/swapfile.c (ffffffff81227ea9)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
```
```
In mm/migrate.c (ffffffff8124ac85)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff8125eaae)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81264c3d)
Location: include/linux/backing-dev.h:153
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a743f)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
```
```
In fs/ext4/super.c (ffffffff8135594f)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff8139dbe4)
Location: include/linux/backing-dev.h:153
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff811f0869)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811fc524)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff812000ac)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff812067d4)
Location: include/linux/backing-dev.h:154
Inline: True
```
```
In mm/mmap.c (ffffffff81235bed)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/fadvise.c (ffffffff81244745)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
```
```
In mm/swapfile.c (ffffffff8124d87e)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff8126eabc)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81282d68)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812891b8)
Location: include/linux/backing-dev.h:154
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cdfff)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
```
```
In fs/ext4/super.c (ffffffff81383d1f)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff813ccfea)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff81201059)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff81206053)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/fadvise.c:vfs_fadvise
```
```
In mm/page-writeback.c (ffffffff8120ee14)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8121297c)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff81219396)
Location: include/linux/backing-dev.h:154
Inline: True
```
```
In mm/mmap.c (ffffffff812493fa)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff81261cc8)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff81282782)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81296f08)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8129e108)
Location: include/linux/backing-dev.h:154
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e32ff)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
```
```
In fs/ext4/super.c (ffffffff8139c7ff)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff813e6372)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff81218c63)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff8121d3d1)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/fadvise.c:vfs_fadvise
```
```
In mm/page-writeback.c (ffffffff8121e5c5)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff81222378)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff81228b86)
Location: include/linux/backing-dev.h:155
Inline: True
```
```
In mm/mmap.c (ffffffff8125b70f)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff8127cc1c)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff8129e77a)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812b2b8e)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b92ba)
Location: include/linux/backing-dev.h:155
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813010e1)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffffffff813c6a5f)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff814122c8)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff81226513)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff8122ad7d)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff8122c065)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8122fe28)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff81236a26)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (ffffffff81269def)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff8128c6ee)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff812ae019)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812c4646)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812cb1aa)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813137c1)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffffffff813dfe1f)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff8142c008)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff812514b3)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff81257b3d)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff81259d55)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8125d018)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff81265cd4)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/mmap.c (ffffffff8129a622)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff812bf1ac)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff812e4b65)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812fa53a)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813012d5)
Location: include/linux/backing-dev.h:155
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8134d081)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/file.c (ffffffff813e9a6c)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/super.c (ffffffff8142c6df)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff8147bd76)
Location: include/linux/backing-dev.h:155
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
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
In mm/filemap.c (ffffffff8125cc93)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff812623dd)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff8126566c)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff81267378)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff8127067d)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/mmap.c (ffffffff812a5802)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812ef551)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81306466)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130d33f)
Location: include/linux/backing-dev.h:136
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81359f81)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/file.c (ffffffff813fbb84)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/super.c (ffffffff814454fe)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff81496bdb)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
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
In mm/filemap.c (ffffffff81261913)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff81266e6d)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff8126a169)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8126bfc5)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff81274c1d)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/mmap.c (ffffffff812aaf98)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812f6292)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff8130c94f)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813138d1)
Location: include/linux/backing-dev.h:136
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81360bf1)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/file.c (ffffffff81401e74)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/super.c (ffffffff8144ae20)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff8149bcca)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
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
In mm/filemap.c (ffffffff8129a213)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
```
```
In mm/fadvise.c (ffffffff812a38ad)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff812a6dfc)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff812a8ca5)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff812b1ec3)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/mmap.c (ffffffff812ec668)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff81340878)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81357b4f)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813605f0)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fs-writeback.c (ffffffff813af261)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/file.c (ffffffff814545e4)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/super.c (ffffffff8149ed30)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff814f36c1)
Location: include/linux/backing-dev.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct backing_dev_info *inode_to_bdi(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813233b0)
Location: mm/backing-dev.c:977
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/migrate.c:folio_migrate_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff813233b0-ffffffff81323402: inode_to_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct backing_dev_info *inode_to_bdi(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81397bf0)
Location: mm/backing-dev.c:1100
Inline: True
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/migrate.c:folio_migrate_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81397bf0-ffffffff81397c42: inode_to_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct backing_dev_info *inode_to_bdi(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cab80)
Location: mm/backing-dev.c:1113
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_needs_dirty_tracking
  - mm/migrate.c:folio_migrate_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813cab80-ffffffff813cabcf: inode_to_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct backing_dev_info *inode_to_bdi(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f55f0)
Location: mm/backing-dev.c:1109
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_needs_dirty_tracking
  - mm/migrate.c:folio_migrate_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813f55f0-ffffffff813f563f: inode_to_bdi (STB_GLOBAL)
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
In mm/filemap.c (ffff8000102b383c)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffff8000102b8fdc)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffff8000102badf8)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffff8000102bf6e4)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffff8000102c8748)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (ffff800010301184)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/swapfile.c (ffff800010327e08)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffff80001034ff90)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffff8000103672b4)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffff80001036ed58)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c9290)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffff8000104b8e80)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffff80001050fedc)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (c04e0aa0)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (c04e57d8)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (c04e6db8)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (c04eb168)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (c04f4d2c)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/mmap.c (c051fcc0)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/swapfile.c (c053f0d0)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (c05511a4)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c05589c8)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (c05a6494)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (c067c4bc)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (c06cb6d4)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (c00000000036a4f4)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (c0000000003711c8)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (c000000000373314)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (c00000000037844c)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (c0000000003847d0)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (c0000000003cd560)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/swapfile.c (c0000000003feb94)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (c000000000433524)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c000000000454710)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (c00000000045f7c4)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (c0000000004cb694)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (c0000000005edf54)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (c000000000657704)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffe0001d8eae)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffe0001dcc0c)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffe0001ddbd0)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffe0001e17c6)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffe0001e711a)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (ffffffe00020e678)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/swapfile.c (ffffffe000227b30)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffe00023ec82)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffe000245446)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffe0002877e8)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffffffe0003357b0)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffe00037a73a)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff8121eb63)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff812233cd)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff812246b5)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff81228478)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff8122f076)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (ffffffff8126243f)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff81284cce)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff812a65f9)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812bcc26)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c378a)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130bda1)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffffffff813d83ff)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff814245e8)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff81211d23)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff8121657d)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff81217865)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8121b5b8)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff81222136)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (ffffffff8125485f)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff81276b3e)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff812980a3)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812add7a)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b47ca)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fc9c1)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffffffff813c8e7f)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff81415068)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff8121c903)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff8122116d)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff81222455)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff81226218)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff8122ce16)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (ffffffff812601df)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff81282ade)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff812a4409)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812baa36)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c159a)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81309b91)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffffffff813d588f)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff81420788)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
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
In mm/filemap.c (ffffffff8122b993)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/fadvise.c (ffffffff8123032d)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffff81231a35)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8123551a)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:file_ra_state_init
```
```
In mm/vmscan.c (ffffffff8123c246)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In mm/mmap.c (ffffffff8126fbaf)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/swapfile.c (ffffffff812927c3)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/migrate.c (ffffffff812b3b77)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812cb176)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812d205a)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131bbb1)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
```
In fs/ext4/super.c (ffffffff813eab0f)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/fuse/file.c (ffffffff81437576)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
