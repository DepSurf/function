# Function: <code>is_journal_aborted</code>

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
In fs/ext4/inode.c (0)
Location: include/linux/jbd2.h:1371
Inline: True
```
```
In fs/ext4/super.c (ffffffff812ac172)
Location: include/linux/jbd2.h:1371
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812cb6c4)
Location: include/linux/jbd2.h:1371
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/jbd2.h:1371
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/jbd2.h:1371
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/jbd2.h:1371
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/jbd2.h:1371
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/jbd2.h:1371
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/jbd2.h:1371
Inline: True
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
In fs/ext4/inode.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/ext4/super.c (ffffffff812e08d2)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812fb6fc)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/indirect.c (ffffffff81308bcc)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813166f9)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8131d0a6)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/inode.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/ext4/super.c (ffffffff812fd9c3)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813116ac)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/indirect.c (ffffffff8131ebdc)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8132ae98)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/jbd2.h:1386
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813330c5)
Location: include/linux/jbd2.h:1386
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff812e65eb)
Location: include/linux/jbd2.h:1388
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/indirect.c (ffffffff812f7723)
Location: include/linux/jbd2.h:1388
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inode.c (0)
Location: include/linux/jbd2.h:1388
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/jbd2.h:1388
Inline: True
```
```
In fs/ext4/super.c (ffffffff81332748)
Location: include/linux/jbd2.h:1388
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813400c6)
Location: include/linux/jbd2.h:1388
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81343af1)
Location: include/linux/jbd2.h:1388
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/jbd2.h:1388
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/jbd2.h:1388
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81347e69)
Location: include/linux/jbd2.h:1388
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff8130a8a7)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/indirect.c (0)
Location: include/linux/jbd2.h:1494
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/jbd2.h:1494
Inline: True
```
```
In fs/ext4/ioctl.c (0)
Location: include/linux/jbd2.h:1494
Inline: True
```
```
In fs/ext4/super.c (ffffffff81356c58)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff81365ef1)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81368144)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/jbd2.h:1494
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/jbd2.h:1494
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8136c4a9)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff81338f4c)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/indirect.c (ffffffff81349c61)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/inode.c (ffffffff8135a8fe)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff8135c8d1)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81384f3c)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff81393140)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813969b8)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/checkpoint.c (ffffffff8139803d)
Location: include/linux/jbd2.h:1494
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff8139936b)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8139d27d)
Location: include/linux/jbd2.h:1494
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff813501fc)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff813585ac)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffff81361e21)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81372bbe)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81374dd5)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8139da2c)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813abe60)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813af721)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813b0dad)
Location: include/linux/jbd2.h:1495
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff813b20db)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813b5fed)
Location: include/linux/jbd2.h:1495
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff81378e99)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff81381aa3)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffff8138b1b2)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff8139c00d)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff8139e4b1)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813c7c80)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813d60b4)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813d9c6f)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813db40e)
Location: include/linux/jbd2.h:1515
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff813dc73b)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813e071d)
Location: include/linux/jbd2.h:1515
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff81391259)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff8139a053)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffff813a3c02)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813b4b1d)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff813b7234)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813e1040)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813f00e4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813f3c4a)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813f545e)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff813f67ff)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813fa75d)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff813dcae9)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff813e3751)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff813efe45)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813fff9d)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81401495)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/super.c (ffffffff8142dc58)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff8143d7c4)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81441072)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814427ee)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff814434e9)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81447c90)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff813ee529)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff813f4f72)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff814025a5)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff8141270d)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81413d31)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/super.c (ffffffff81446925)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff81459b14)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8145d273)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8145e9fe)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff8145f5c9)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81464620)
Location: include/linux/jbd2.h:1645
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff813f4af5)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff813fb2b6)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff814089a5)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81418b6d)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81419fa1)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/super.c (ffffffff8144c0d5)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff8145f3d4)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81462b9c)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8146429e)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff81465475)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81469db0)
Location: include/linux/jbd2.h:1654
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff81446d45)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff8144d69c)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff8145b415)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff8146bd8b)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff8146d18e)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/super.c (ffffffff814a017d)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff814b4884)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff814b8092)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814b98be)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff814badf5)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff814c09b3)
Location: include/linux/jbd2.h:1693
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff814c3050)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff814ca1ed)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff814d91d2)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff814ebd2b)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff814ecc7b)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/super.c (ffffffff81526dcc)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff8153ce74)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81541baa)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/checkpoint.c (ffffffff8154356c)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff81544cc0)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8154b205)
Location: include/linux/jbd2.h:1687
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff8155b3e2)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff81562862)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff81572012)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81585a7b)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81586a2b)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/super.c (ffffffff815c46bc)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff815db644)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff815e07f6)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/checkpoint.c (ffffffff815e249c)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff815e3e00)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff815eae95)
Location: include/linux/jbd2.h:1685
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff81593207)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff8159a570)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff815a9da2)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815bc27d)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815bea0d)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_force_shutdown
```
```
In fs/ext4/super.c (ffffffff815fbdac)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff81613104)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff816180a3)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/checkpoint.c (ffffffff81619e0c)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff8161b5bd)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81622905)
Location: include/linux/jbd2.h:1686
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff815cbef7)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff815d33b3)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
```
```
In fs/ext4/indirect.c (ffffffff815e2b42)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815f505d)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815f77bd)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_force_shutdown
```
```
In fs/ext4/super.c (ffffffff8163494c)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff8164bf04)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81650fd8)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/checkpoint.c (ffffffff81652d6c)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (ffffffff816544dd)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8165b965)
Location: include/linux/jbd2.h:1680
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffff800010463de8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffff80001046ca34)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffff800010477290)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffff800010489290)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffff80001048ccdc)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffff8000104ba3d8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffff8000104c8c5c)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffff8000104cf208)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d0e6c)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (ffff8000104d28d0)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffff8000104d78e4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (c06243bc)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (c062df28)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (c0638df8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (c064b7b8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (c064e428)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c067da90)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (c068c5d4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (c0691ef0)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c06939c8)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (c0694f64)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (c0699908)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (c0000000005810bc)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (c00000000058c500)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (c00000000059946c)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (c0000000005b01b4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (c0000000005b37b4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c0000000005efb60)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (c00000000060140c)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (c000000000607fb0)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c00000000060a050)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_cleanup_journal_tail
```
```
In fs/jbd2/revoke.c (c00000000060c158)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (c000000000612588)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffe0002f2532)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffe0002f9eb2)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffe000302698)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffe000310ad4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffe000312b6a)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffe0003368c8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffe000342ed8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffe000346d06)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffe00034836c)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffe000349868)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffe00034d68e)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff81389839)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff81392633)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffff8139c1e2)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813ad0fd)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff813af814)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d9620)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813e86c4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813ec22a)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813eda3e)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff813eeddf)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813f2d3d)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff8137a2c9)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff813830c3)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffff8138cc72)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff8139db8d)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff813a02a4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813ca0a0)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813d9144)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813dccaa)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813de4be)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff813df85f)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813e37bd)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff81387199)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff8138ff93)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffff81399a42)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813aa95d)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff813ad074)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d6ab0)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813e5a44)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813e95aa)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813eadbe)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff813ec15f)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813f00bd)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/ext4/ext4_jbd2.c (ffffffff8139ae73)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffffffff813a3df8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
```
In fs/ext4/indirect.c (ffffffff813adb32)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813bf2ad)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff813c1a2d)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813ebd50)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffff813fa2b4)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff813feeaf)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8140071e)
Location: include/linux/jbd2.h:1513
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff81401aff)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81405ac8)
Location: include/linux/jbd2.h:1513
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
```
</details>
</li>
</ul>

## Differences
