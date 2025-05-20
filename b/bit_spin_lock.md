# Function: <code>bit_spin_lock</code>

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
In mm/swap.c (ffffffff8119d390)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
```
```
In mm/slub.c (ffffffff811e9b7d)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
```
In mm/huge_memory.c (ffffffff811f72f6)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/dcache.c (ffffffff81223480)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/dcache.c:__d_drop
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/buffer.c (ffffffff81243f4f)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/mbcache.c (ffffffff8126cbdc)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/page-io.c (ffffffff8129f71f)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff812e8128)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
```
```
In fs/jbd2/commit.c (ffffffff812e9feb)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff812f2b82)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In mm/slub.c (ffffffff8120c701)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff8122bbbb)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff8124bb63)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/buffer.c (ffffffff8126be40)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff81298a78)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff812ce016)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff81317238)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317af8)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81320a8f)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In mm/slub.c (ffffffff8121e761)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff8123e11b)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff8125eb43)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/buffer.c (ffffffff8127f1b0)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff812ad4f6)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff812e3e06)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff8132d228)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132dae8)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8133693f)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In mm/slub.c (ffffffff8122a2ca)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81249abb)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff8126c513)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_drop
```
```
In fs/buffer.c (ffffffff8128cb50)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff812ba99e)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff8131d9f2)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813423f8)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342c76)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8134b5ef)
Location: include/linux/bit_spinlock.h:15
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In mm/slub.c (ffffffff8124547a)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81269d1b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff8128e6a3)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff812af5f0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff812de27e)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff81342002)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff81366a28)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813672a9)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8136fc1f)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In mm/slub.c (ffffffff812695ad)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff8128e6ab)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff812b4915)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff812d6d37)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8130a4be)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff8136fea2)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff81395118)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395b16)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8139e12f)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8127c685)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffffffff812a321b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff812c9b95)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff812ec4b7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8131fc9e)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff81388332)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813ade88)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813ae862)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813b6e9f)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81278550-ffffffff81278571: bit_spin_lock.part.59.constprop.88 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4e42)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffffffff81298258)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffffffff812be581)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff812e65a5)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff8130dc37)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8134750d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff813b23cd)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813d81fb)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d8d27)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e15a0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8141cf79)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d9b)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d606)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819307a3)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819629cc)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969ca1)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfaa0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db937)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98f8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44111)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f5d6)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81293a80-ffffffff81293a94: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81201e52)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffffffff812a80b8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffffffff812d0471)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff812f8105)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff81320c17)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8135f67d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff813cb471)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813f22db)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f2d17)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813fb5f0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff81436dc9)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c4b)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b456)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81962cac)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963ec4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a0711)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06630)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12867)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2160d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ad01)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86266)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff812a3800-ffffffff812a3814: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81229266)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff812dd2e6)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81306bd1)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff81330e65)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813a5259)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff81448dc5)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814868d3)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf32)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158e9e2)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In net/core/xdp.c (ffffffff81a35fa3)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a791ee)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e93)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01ccb)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b108e9)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b7525b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81403)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff812dfd44-ffffffff812dfd58: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230df6)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff812e60b6)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81312761)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff8133c816)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813b5fb9)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff81465965)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814a3f83)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a142)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab542)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In net/core/xdp.c (ffffffff81a38373)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81ffe)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02d03)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fdab)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ebd9)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83fcb)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90c43)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff81be927c-ffffffff81be9290: bit_spin_lock.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff81234f99)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff812ed846)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81318c81)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff81342c9b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813bd109)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff8146b115)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814a9eb7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a51)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b63a4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81a1f1b7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b0ed)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee607)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afd99d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c864)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72c4d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fe57)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff8126f0c9)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff81335bbd)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81365261)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff813906db)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8140cea7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff814c17c5)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81502367)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebf1)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c8d4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81ad3447)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b2470d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae9b7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfa9d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa54)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a19d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d18d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b6f7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812be012)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff813a736d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:free_partial
```
```
In fs/dcache.c (ffffffff81413192)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81481cf2)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff8154c154)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff815939b2)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d6e4)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea0de)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c50cf2)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cabfe6)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d418c3)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55e00)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6813e)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7efa)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb515)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deae18)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
**Symbols:**

```
ffffffff81e733d2-ffffffff81e7340f: bit_spin_lock.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff813216a4)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d557)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff81429f93)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In fs/dcache.c (ffffffff8149e44c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81514f5b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff815ebf34)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff8163c547)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1199)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da301)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e06397)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69bba)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a6e2)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f20534)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f331d2)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa98f0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae119)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe9fc)
Location: include/linux/bit_spinlock.h:16
Inline: True
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
In kernel/bpf/offload.c (ffffffff81351245)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e4f8)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff8145f432)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In fs/dcache.c (ffffffff814d376c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8154c95b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff81623a14)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81674a00)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0a9)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819682)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78c1a)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5b54)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a212)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80030)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92552)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a270)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e8c4)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f8d2)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/handshake/request.c (ffffffff82092c08)
Location: include/linux/bit_spinlock.h:16
Inline: True
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
In kernel/bpf/offload.c (ffffffff813786a5)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7758)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In mm/slub.c (ffffffff8145a67b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/dcache.c (ffffffff81505eec)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8158278b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/jbd2/journal.c (ffffffff8165cab4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff816b0dc0)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747ba9)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e9d2)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f38aea)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88db4)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff820308c2)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820466b0)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820602c2)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d9211)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd854)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eea02)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In net/handshake/request.c (ffffffff821694b8)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028a204)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffff80001034939c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffff80001037561c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffff8000103a56bc)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffff8000103da5d4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffff8000104252d8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffff8000104a332c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffff8000104cca24)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce194)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffff8000104d8db8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffff80001051d490)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff80001059898c)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffff800010636b54)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c067a8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08630)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4edcc)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf47c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbf3c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd6c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44b58)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51e80)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffff800010344e50-ffff800010344ec0: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (c04b9884)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (c054d54c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (c0588eb8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (c05b2cc8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (c05ede60)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (c06652ec)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (c06902f4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0690e6c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (c069acc0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (c06d987c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749bc8)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (c07dc880)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f934)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d21724)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5eed4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcadf8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7d50)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7a64)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47010)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52f24)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
c0549420-c05494d4: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (c0000000003355c4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (c000000000428584)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (c00000000046888c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (c0000000004a1128)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (c0000000004de258)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (c000000000534554)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (c0000000005d01e4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (c000000000606138)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000606d90)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (c000000000613d6c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (c000000000666600)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f910)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca44)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0d14)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2c74)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d470)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda0f0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb434)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd2c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7965c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa48)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
c000000000421b90-c000000000421be4: bit_spin_lock.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffe0001be2a8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffffffe00023b128)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffe00024e024)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffe00026c288)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffe000291fc2)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffe0002c43e4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffe000324bb2)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffe00034538c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000345d32)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffe00034e720)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffe000384d80)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5304)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffe000464104)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784cca)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe000786478)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007bab16)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815256)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082083c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c10a)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f402)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4b4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fa472)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffffffff812a0698)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffffffff812c8a51)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff812f06e5)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff813191f7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff81357c5d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff813c3a51)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813ea8bb)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb2f7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f3bd0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8142f3a9)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b22b)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523a36)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81902c7c)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e94)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81940581)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63d0)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b2127)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c9d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a391)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258f6)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8129bde0-ffffffff8129bdf4: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ed1c2)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffffffff812921a8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffffffff812b9a91)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff812e1315)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff81309d5a)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8134890d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff813b44d6)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813db33b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dbd77)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e4650)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8141fe29)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc4b)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513d16)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bcaac)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdcc4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa071)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe90)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e757)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da8d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7151)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e26b6)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8128d9a0-ffffffff8128d9b4: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f8242)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffffffff8129e4a8)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffffffff812c6861)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff812ee4f5)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff81316cc7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8135572d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff813c0ee1)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813e7c3b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e8677)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f0f50)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8142b549)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814972cb)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fac6)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81953cac)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954ec4)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81991711)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c70)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9c7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b71d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84e11)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90376)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81299bf0-ffffffff81299c04: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812065a1)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/slub.c (ffffffff812ae205)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/zsmalloc.c (ffffffff812d7fd5)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/dcache.c (ffffffff813004b5)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffff81328cf7)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff81368d21)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffff813d6011)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813fd43b)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fde9a)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81406b10)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff814424db)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af3a3)
Location: include/linux/bit_spinlock.h:16
Inline: True
```
```
In lib/rhashtable.c (ffffffff815393ab)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8197542f)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976e9f)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b4196)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b54d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27983)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d65)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a9178d)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf70)
Location: include/linux/bit_spinlock.h:16
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff812a9a10-ffffffff812a9a4e: bit_spin_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
