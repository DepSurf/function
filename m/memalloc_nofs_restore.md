# Function: <code>memalloc_nofs_restore</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81340ba7)
Location: include/linux/sched/mm.h:189
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813651b7)
Location: include/linux/sched/mm.h:198
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81393923)
Location: include/linux/sched/mm.h:234
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ac643)
Location: include/linux/sched/mm.h:234
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d68b1)
Location: include/linux/sched/mm.h:267
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f08f1)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
In mm/readahead.c (ffffffff8125cf37)
Location: include/linux/sched/mm.h:271
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff8143e075)
Location: include/linux/sched/mm.h:271
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
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
In mm/readahead.c (ffffffff81267297)
Location: include/linux/sched/mm.h:257
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff8145a330)
Location: include/linux/sched/mm.h:257
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
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
In mm/readahead.c (ffffffff8126bef3)
Location: include/linux/sched/mm.h:261
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff8145fbda)
Location: include/linux/sched/mm.h:261
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
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
In mm/readahead.c (ffffffff812a8bd6)
Location: include/linux/sched/mm.h:261
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In fs/jbd2/transaction.c (ffffffff814b508a)
Location: include/linux/sched/mm.h:261
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
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
In kernel/audit_tree.c (ffffffff811ece43)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
```
```
In mm/readahead.c (ffffffff8130186a)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff81366d7b)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff814000ed)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff81450445)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff8145081e)
Location: include/linux/sched/mm.h:334
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81450f9f)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451df7)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8145666c)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff8148ebb2)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inline.c (ffffffff814dd9ca)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/move_extent.c (ffffffff814ff054)
Location: include/linux/sched/mm.h:334
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8153e96d)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
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
In kernel/audit_tree.c (ffffffff812333d3)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
```
```
In mm/readahead.c (ffffffff8136bf21)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff813e2c1c)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff8148a13d)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff814dee05)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff814df08e)
Location: include/linux/sched/mm.h:334
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814dfa0f)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0b77)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5666)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff815226f5)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inline.c (ffffffff81576a0f)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/move_extent.c (ffffffff815998c7)
Location: include/linux/sched/mm.h:334
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff815dd2f2)
Location: include/linux/sched/mm.h:334
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
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
In kernel/audit_tree.c (ffffffff8124a080)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
```
```
In mm/readahead.c (ffffffff8139e1b0)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff81417843)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff814bf01a)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff81515645)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff8151590e)
Location: include/linux/sched/mm.h:366
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81516297)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81517427)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c12b)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff8155a7d6)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inode.c (ffffffff815bc327)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/migrate.c (ffffffff815ce9a2)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff815d01d0)
Location: include/linux/sched/mm.h:366
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff81614d92)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
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
In kernel/audit_tree.c (ffffffff81263f90)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
```
```
In mm/readahead.c (ffffffff813c7e50)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/vmalloc.c (ffffffff8144437a)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In fs/namei.c (ffffffff814f16ba)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/notify/mark.c (ffffffff81549a05)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff81549cce)
Location: include/linux/sched/mm.h:366
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8154a5b3)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b807)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550729)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
```
In fs/quota/dquot.c (ffffffff81590f95)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_release
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/ext4/inode.c (ffffffff815f5107)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/migrate.c (ffffffff81607222)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81608a55)
Location: include/linux/sched/mm.h:366
Inline: True
```
```
In fs/ext4/super.c (ffffffff8163afed)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
```
```
In fs/jbd2/transaction.c (ffffffff8164db82)
Location: include/linux/sched/mm.h:366
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:stop_this_handle
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104ca518)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068de88)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c0000000006033d4)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000343760)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e8ed1)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d9951)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e6251)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fb741)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
</ul>

## Differences
