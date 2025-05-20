# Function: <code>buffer_dirty</code>

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
In fs/buffer.c (ffffffff81242a11)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff8124d836)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff81294cfa)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81295c9b)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bh_delay_or_unwritten
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/page-io.c (ffffffff8129febc)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff812e8212)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812eaec5)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff812ec912)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
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
In fs/buffer.c (ffffffff8126d2b1)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff81275f98)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff812c22df)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812c3f60)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff812ce7b8)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8131600a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81318830)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8131a382)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff81280503)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff81289c82)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff812d792a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812d9610)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff812e4598)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8132bffa)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132e826)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81330372)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8128dcc1)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff81296967)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff812f5b6c)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812fd52d)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff8131e255)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813411fa)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81343972)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81345292)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff812b08b1)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff812b9bc7)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff81318506)
Location: include/linux/buffer_head.h:118
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81321d6d)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff81342875)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81365820)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81367fc5)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81369932)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff812d86c0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff812e273b)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff81346932)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8134fd9c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff813706f5)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81393fbd)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813968cd)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813980d2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff812edb90)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff812f73a7)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff8135e627)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81367f8d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff81388b86)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813accef)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813af636)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813b0e42)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8130f36e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff813179d6)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff8138780a)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8139151d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff813b2c76)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813d6f53)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d9b84)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813db4a5)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff813222ce)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff8132a856)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff813a06fa)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a9eaf)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff813cbce4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813f0fb0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f3b5f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813f54f5)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8135c516)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8136450a)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff813ec01f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:recently_deleted
```
```
In fs/ext4/inode.c (ffffffff813f5785)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff81417e8f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8143e53b)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81440ff2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/checkpoint.c (ffffffff81442885)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8136a98c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8137150c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff813fe1cf)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:recently_deleted
```
```
In fs/ext4/inode.c (ffffffff81407f35)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff8142b994)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff8143d0d1)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff8145a7db)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8145d1f3)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/checkpoint.c (ffffffff8145ea95)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff813700a0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff813787dc)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff81404721)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/inode.c (ffffffff8140e30c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff814325b3)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff81442f1e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff81460067)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81462b1c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/checkpoint.c (ffffffff81464325)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff813bec2e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
```
```
In fs/mpage.c (ffffffff813c50ef)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff81456ed1)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/inode.c (ffffffff814614b9)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff81485e73)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff81496bbe)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff814b54e7)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b8012)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/checkpoint.c (ffffffff814b9945)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff814473b2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8144c064)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff814d49b5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/inode.c (ffffffff814e0229)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff815093f9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff81521aee)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff8153ee41)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81541ae8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/checkpoint.c (ffffffff81543605)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff814d5fea)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff814da4f1)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff8156d667)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/inode.c (ffffffff8157b514)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_bh_delay_or_unwritten
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff815a3fb7)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff815bedfe)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff815dd827)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff815e0734)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/checkpoint.c (ffffffff815e2545)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8150b449)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8150ea16)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff815a5557)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/inode.c (ffffffff815b12c9)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff815daa1a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/super.c (ffffffff815f5b96)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff81615263)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81617fe1)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81619eb5)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8154026e)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8154332a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff815de3c7)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/inode.c (ffffffff815ea0f9)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff8161321f)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/super.c (ffffffff8162e4a6)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff8164e053)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81650f17)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81652e15)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffff8000103db050)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffff8000103e602c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffff800010473b8c)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffff80001047d8e8)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffff8000104a3e90)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffff8000104cae58)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104cf0fc)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d0f10)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (c05b4454)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
```
```
In fs/mpage.c (c05bdb98)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (c0634c28)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/inode.c (c0640764)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (c0665d74)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c068e7c8)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0691d78)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c0693a70)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (c0000000004e0324)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (c0000000004ec1b4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (c000000000595118)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a1390)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (c0000000005d0f90)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c000000000603dec)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000607e80)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c00000000060a16c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffe000293ad0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffe00029b410)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffe0002ff8e2)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffe0003076a8)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffe0003253da)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffe000343e64)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000346b64)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffe0003483f4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8131a8ae)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff81322e36)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff81398cda)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a248f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff813c42c4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813e9590)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813ec13f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813edad5)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8130b44e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff813139d6)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff8138976a)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81392f1f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff813b4d44)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813da010)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dcbbf)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813de555)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff8131837e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff81320906)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff8139653a)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8139fcef)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff813c1754)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813e6910)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_write_access_granted
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e94bf)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813eae55)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
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
In fs/buffer.c (ffffffff81329f9e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/mpage.c (ffffffff81332626)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/ialloc.c (ffffffff813aa79a)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b49cf)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/page-io.c (ffffffff813d68b4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813fbea0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fedbc)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814007b5)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
</details>
</li>
</ul>

## Differences
