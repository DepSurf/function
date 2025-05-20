# Function: <code>buffer_write_io_error</code>

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
In fs/buffer.c (ffffffff8124279f)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:__remove_assoc_queue
  - fs/buffer.c:drop_buffers
```
```
In fs/ext4/inode.c (ffffffff8129640f)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff812b7fc1)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff812eccfd)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
```
```
In fs/jbd2/journal.c (ffffffff812f1946)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8126c828)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/ext4/inode.c (ffffffff812c3a06)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff812e6deb)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff8131ad2e)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8131f169)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8127f888)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/ext4/inode.c (ffffffff812d90b6)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff812fc99b)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff81330d1e)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813351eb)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff812ff781)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813315f1)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff81345c7e)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81349f89)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff81323f31)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff81355aa2)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff8136a311)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8136e5d9)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff813508f7)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff81383e7d)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff81398a01)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8139cc3a)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff81369d87)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff8139c958)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff813b1771)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813b59aa)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff813931dd)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/super.c (ffffffff813c6bb0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff813dbd9f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e0094)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff813abb6b)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff813dff70)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff813f5e0f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813fa0d4)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff813f7ea8)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff8142c822)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffffffff8143e32e)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff814431af)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81447694)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff81409d27)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff8144553c)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/transaction.c (ffffffff8145a5ce)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff8145f30f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81464023)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff8140feea)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff8144ae57)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/jbd2/transaction.c (ffffffff8145fe6e)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff81464b7f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814696d3)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff81462de4)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff8149ed67)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/jbd2/checkpoint.c (ffffffff814b9af5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814bfb73)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff814e28ea)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/ioctl.c (ffffffff814ed4be)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff815254f5)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8152eace)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/checkpoint.c (ffffffff81543824)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8154a301)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff8157bd0f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/ioctl.c (ffffffff8158731e)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff815c2b55)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff815ccc2e)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/checkpoint.c (ffffffff815e2784)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815e9c62)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff815b310f)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/ioctl.c (ffffffff815bd9de)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff815fa2b5)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8160471e)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a0f4)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81621a52)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff815ebf10)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/ioctl.c (ffffffff815f679e)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff81632eb5)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8163d3d0)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/journal.c (ffffffff8165a0c0)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffff8000104803c0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffff8000104b8f9c)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffff8000104d1b04)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d6f44)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (c06417c8)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (c067c638)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (c0694524)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c069907c)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (c0000000005a4a08)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (c0000000005ee0d0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (c00000000060b0cc)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c000000000611a90)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffe00030911a)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffe0003358b6)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffe000348e08)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffe00034cefa)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff813a414b)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff813d8550)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff813ee3ef)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f26b4)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff81394bdb)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff813c8fd0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff813dee6f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e3134)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff813a19ab)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff813d59e0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff813eb76f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813efa34)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ext4/inode.c (ffffffff813b65be)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/super.c (ffffffff813eac60)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/checkpoint.c (ffffffff8140111f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81405444)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
</details>
</li>
</ul>

## Differences
