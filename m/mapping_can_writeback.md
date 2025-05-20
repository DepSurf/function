# Function: <code>mapping_can_writeback</code>

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
In mm/filemap.c (ffffffff8125d50f)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81263c09)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff812a57ff)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812ef54d)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81306463)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130d33c)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81359f79)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff8126026e)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff812697e9)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff812aaf95)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812f628e)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff8130c94c)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813138ce)
Location: include/linux/backing-dev.h:159
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81360be9)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff8129cc0c)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff812a6449)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff812ec665)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff81340871)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81357b4c)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813605ed)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fs-writeback.c (ffffffff813af259)
Location: include/linux/backing-dev.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff812f3ecd)
Location: include/linux/backing-dev.h:138
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff812fd923)
Location: include/linux/backing-dev.h:138
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/mmap.c (ffffffff8134f55a)
Location: include/linux/backing-dev.h:138
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff813b22b8)
Location: include/linux/backing-dev.h:138
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff813d0891)
Location: include/linux/backing-dev.h:138
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813dbdf7)
Location: include/linux/backing-dev.h:138
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fs-writeback.c (ffffffff81433d48)
Location: include/linux/backing-dev.h:138
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff8135e1ca)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81368143)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/mmap.c (ffffffff813c8b83)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff81431d63)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff81456044)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81462b9d)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fs-writeback.c (ffffffff814c1cd8)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff81390f66)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81399fc3)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/mmap.c (ffffffff813fce12)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_needs_dirty_tracking
```
```
In mm/migrate.c (ffffffff8146797f)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff8148d1d7)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8149896b)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fs-writeback.c (ffffffff814f7068)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff813bacfb)
Location: include/linux/backing-dev.h:147
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813c3c83)
Location: include/linux/backing-dev.h:147
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/mmap.c (ffffffff814297e2)
Location: include/linux/backing-dev.h:147
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_needs_dirty_tracking
```
```
In mm/migrate.c (ffffffff81496c48)
Location: include/linux/backing-dev.h:147
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff814bcb12)
Location: include/linux/backing-dev.h:147
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814c7ebf)
Location: include/linux/backing-dev.h:147
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fs-writeback.c (ffffffff8152b7a8)
Location: include/linux/backing-dev.h:147
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
