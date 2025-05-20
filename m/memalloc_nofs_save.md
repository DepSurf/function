# Function: <code>memalloc_nofs_save</code>

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
In fs/jbd2/transaction.c (ffffffff8133fdb0)
Location: include/linux/sched/mm.h:182
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81348357)
Location: include/linux/sched/mm.h:182
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813643c0)
Location: include/linux/sched/mm.h:191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8136c995)
Location: include/linux/sched/mm.h:191
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff81392b67)
Location: include/linux/sched/mm.h:219
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8139b090)
Location: include/linux/sched/mm.h:219
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813ab7e4)
Location: include/linux/sched/mm.h:219
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813b3e00)
Location: include/linux/sched/mm.h:219
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813d5a27)
Location: include/linux/sched/mm.h:252
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813de3f9)
Location: include/linux/sched/mm.h:252
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813efa57)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813f8449)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In mm/readahead.c (ffffffff8125ce5d)
Location: include/linux/sched/mm.h:256
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff8143d193)
Location: include/linux/sched/mm.h:256
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81445c99)
Location: include/linux/sched/mm.h:256
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In mm/readahead.c (ffffffff812671b2)
Location: include/linux/sched/mm.h:242
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff81459513)
Location: include/linux/sched/mm.h:242
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81462079)
Location: include/linux/sched/mm.h:242
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In mm/readahead.c (ffffffff8126be00)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff8145edd3)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81467729)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In mm/readahead.c (ffffffff812a8acc)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff814b4141)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff814bd6c9)
Location: include/linux/sched/mm.h:246
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In kernel/audit_tree.c (ffffffff811ecddc)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
```
```
In mm/readahead.c (ffffffff8130178b)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff81366d9a)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff814000b7)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff8145041f)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff814507ee)
Location: include/linux/sched/mm.h:319
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81450f85)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451da1)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8145655f)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff8148eb2c)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inline.c (ffffffff814dd99d)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/move_extent.c (ffffffff814ff01a)
Location: include/linux/sched/mm.h:319
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8153d9b0)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81548d6d)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In kernel/audit_tree.c (ffffffff8123336c)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
```
```
In mm/readahead.c (ffffffff8136be05)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff813e2c39)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff8148a107)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff814deddf)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff814df05e)
Location: include/linux/sched/mm.h:319
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814df9f5)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0b21)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e551f)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff8152265c)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inline.c (ffffffff815769e2)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/move_extent.c (ffffffff8159988d)
Location: include/linux/sched/mm.h:319
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff815dc220)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff815e8929)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In kernel/audit_tree.c (ffffffff8124a01c)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
```
```
In mm/readahead.c (ffffffff8139e086)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff81417860)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff814befe4)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff8151561f)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff815158da)
Location: include/linux/sched/mm.h:351
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8151627d)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff815173d1)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bfe0)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff8155a6fc)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inode.c (ffffffff815bc2e9)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/migrate.c (ffffffff815ce87d)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff815d0180)
Location: include/linux/sched/mm.h:351
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff81613cd2)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff816201d9)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In kernel/audit_tree.c (ffffffff81263f2c)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
```
```
In mm/readahead.c (ffffffff813c7d26)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff81444397)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff814f1684)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff815499df)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff81549c9a)
Location: include/linux/sched/mm.h:351
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8154a63b)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b7b1)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff815505e1)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff81590ebc)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inode.c (ffffffff815f50c9)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/migrate.c (ffffffff816070fd)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81608a06)
Location: include/linux/sched/mm.h:351
Inline: True
```
```
In fs/ext4/super.c (ffffffff8163afc7)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
```
```
In fs/jbd2/transaction.c (ffffffff8164cac2)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff816591a9)
Location: include/linux/sched/mm.h:351
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffff8000104c9794)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffff8000104d64f0)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (c068cd68)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (c0696d08)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (c000000000601e24)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (c00000000060f034)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffe0003428da)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffe00034b122)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813e8037)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813f0a29)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813d8ab7)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813e14a9)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813e53b7)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813edda9)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
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
In fs/jbd2/transaction.c (ffffffff813fa934)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff814038c9)
Location: include/linux/sched/mm.h:254
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
</details>
</li>
</ul>

## Differences
