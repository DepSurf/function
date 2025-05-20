# Function: <code>clear_bit_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8118d86c)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/filemap.c:unlock_page
```
```
In mm/swap.c (ffffffff8119d3ae)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
```
```
In mm/huge_memory.c (ffffffff811f747b)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/zsmalloc.c (ffffffff81206057)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff81242639)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/buffer.c:unlock_buffer
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8129f7a9)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff812c0f80)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff812e7600)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812e987e)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff812f2bef)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
```
In block/blk-tag.c (ffffffff813bbdde)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-iopoll.c (ffffffff813c2302)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - block/blk-iopoll.c:blk_iopoll_complete
  - block/blk-iopoll.c:blk_iopoll_softirq
```
```
In drivers/rtc/interface.c (ffffffff81673c99)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff816753b2)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
  - drivers/rtc/rtc-dev.c:rtc_dev_release
```
**Symbols:**

```
ffffffff812e7600-ffffffff812e760b: clear_bit_unlock.constprop.14 (STB_LOCAL)
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
In mm/filemap.c (ffffffff811a049a)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/filemap.c:unlock_page
```
```
In mm/zsmalloc.c (ffffffff8122c219)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8126be7e)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff812ce078)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff812f0980)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff81317256)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317b1b)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81320aaf)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-tag.c (ffffffff813ffbf3)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In lib/nmi_backtrace.c (ffffffff81433e46)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In lib/irq_poll.c (ffffffff81461fc0)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/interface.c (ffffffff816d448c)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff816d61eb)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_open
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
In mm/zsmalloc.c (ffffffff8123e769)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8127f1ee)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff812e3e68)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff81306950)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff8132d246)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132db0b)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8133695f)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-tag.c (ffffffff8141949f)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In lib/nmi_backtrace.c (ffffffff814500dd)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/irq_poll.c (ffffffff81480b70)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/scsi/sd_zbc.c (ffffffff816485a5)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_unlock_zone
```
```
In drivers/rtc/interface.c (ffffffff8170416c)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff81705ecb)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_open
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
In mm/zsmalloc.c (ffffffff8124a13b)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8128cb8e)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff8131da57)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff81321440)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff81342416)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342c9a)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8134b60f)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-tag.c (ffffffff814273d0)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-mq.c (ffffffff81430344)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In lib/irq_poll.c (ffffffff81489d6a)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d2a2)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_write_unlock_zone
```
```
In drivers/rtc/interface.c (ffffffff81719c09)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff8171bb7b)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
```
In lib/nmi_backtrace.c (ffffffff818efe85)
Location: arch/x86/include/asm/bitops.h:131
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In mm/zsmalloc.c (ffffffff8126a350)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff812af62e)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff81342067)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff81345b80)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff81366a46)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813672cd)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8136fc3f)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-tag.c (ffffffff814529d0)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In lib/irq_poll.c (ffffffff814c6010)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6902)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_write_unlock_zone
```
```
In drivers/rtc/interface.c (ffffffff8178ae79)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff8178cde6)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff817ad002)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff819762c5)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In mm/zsmalloc.c (ffffffff8128ec67)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff812d6d75)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff8136ff07)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813739dd)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff81395137)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395b3a)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8139e14e)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-tag.c (ffffffff81485dbe)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In lib/irq_poll.c (ffffffff814f6dde)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/sbitmap.c (ffffffff814f874c)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/rtc/interface.c (ffffffff817cc07a)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff817cf3d6)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff817f3122)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff819d2a3a)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In mm/zsmalloc.c (ffffffff812a2e07)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff812ec4f5)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff81388397)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff8138be0d)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813adea7)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813ae886)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813b6ebe)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In lib/irq_poll.c (ffffffff8150b34e)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff817f6544)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81829ab6)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In lib/nmi_backtrace.c (ffffffff81a0c0ba)
Location: arch/x86/include/asm/bitops.h:132
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffffffff811f4e98)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812be179)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8130dc74)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff813b2466)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b694d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813d821b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d8d4b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813e1654)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8141cfe6)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488e0b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d6af)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81539a5c)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81837264)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8186bf13)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff819307f0)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81962a43)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969cfb)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfb1d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819dbbc1)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e994e)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a443d7)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f628)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a7ba17)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffffffff81201ea8)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812d0069)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff81320c58)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff813cb50a)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813cf86d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813f22fb)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f2d3b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813fb6a4)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff81436e36)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2cbb)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b4ff)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8155a87c)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81868bd4)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8189dd32)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81962d03)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963f3f)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a076b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a066ad)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12af1)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21676)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7afc7)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a862b8)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81ab2d77)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffffffff8122936e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8130706e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8135d8d7)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/io_uring.c (ffffffff81380c8e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/io_uring.c:__io_free_req
```
```
In fs/ext4/resize.c (ffffffff8141c4bd)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff8143fa73)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81448de7)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814869ee)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcfa3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158ea87)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff815e41f2)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff815ed613)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff8193c7c4)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8196dfed)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81a360be)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a792e0)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5fae)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01d9a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10957)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b7532a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8151e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff81230efe)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81312dae)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8136b4c7)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/io_uring.c (ffffffff8139033a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/io_uring.c:__io_free_req
```
```
In fs/ext4/resize.c (ffffffff8143026d)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff8145bb43)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81465987)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814a409e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a1b3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab5e7)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff81608722)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff81611dd3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff819427b4)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81975186)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81a3848e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a820f0)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e1e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fe7a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ec47)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b8409a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90d5e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/watchdog.c (ffffffff811a25d3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff81235094)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/filemap.c (ffffffff8125ddcc)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/filemap.c:end_page_private_2
```
```
In mm/zsmalloc.c (ffffffff813180fd)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff81371d67)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/resize.c (ffffffff81436e6d)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff81461483)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8146b137)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814a9fc5)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520ac1)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b644a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815eb332)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff815f54b3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff81925fe4)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff819591c5)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81a1f2c5)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b1d8)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee715)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afda6a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c8d2)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72d1a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7ff65)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/watchdog.c (ffffffff811cbdb3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff8126f1c4)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/filemap.c (ffffffff8129a4ec)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/filemap.c:end_page_private_2
```
```
In mm/zsmalloc.c (ffffffff81364605)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff813c0d87)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/io-wq.c (ffffffff813f1dea)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_worker_cancel_cb
```
```
In fs/ext4/resize.c (ffffffff8148aadd)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff814b6973)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff814c184c)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81502475)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec61)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c98d)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff816576d8)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff81662923)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff819c8f54)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff819fe965)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81a06220)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81ad3555)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b247f8)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeac5)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfb6a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfac2)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a200)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d25a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b805)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/watchdog.c (ffffffff811ffb5e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff812be089)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/filemap.c (ffffffff812f0175)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In fs/buffer.c (ffffffff814447f0)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/ioctl.c (ffffffff814ed9ba)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff8150d27d)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff815402ce)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8154c1de)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81593a22)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d754)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In io_uring/io-wq.c (ffffffff816da56a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff816ea19c)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8176f0d8)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff8177c792)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff81b2a144)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81b65f08)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81b6de92)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81c50e9e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cac111)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4194c)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55f3e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d682e1)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7f67)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb683)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deae6f)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
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
In kernel/watchdog.c (ffffffff8124758d)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff81321807)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d60f)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/filemap.c (ffffffff8135b505)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In fs/buffer.c (ffffffff814d3418)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/ioctl.c (ffffffff81587810)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff815a7fc2)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff815dee35)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff815ebfbe)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff8163c6ac)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1209)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a664a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff817da3ba)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8189eaa8)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81cbdda4)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81d010ff)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81d0a3b0)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81e064fc)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69ce6)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a76f)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2066c)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33335)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa995e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae27f)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbea52)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff8203925e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/watchdog.c (ffffffff8125e64f)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff813512b9)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e609)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/filemap.c (ffffffff8138d365)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In fs/buffer.c (ffffffff8150a6a8)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/ioctl.c (ffffffff815bded0)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff815de842)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff81616895)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81623a9e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81674a71)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a119)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e75ac)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff818196c6)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff818e1078)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81d256b4)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81d6a45c)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81d734ea)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81e78d2d)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5c91)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a29f)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80143)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92663)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a2e0)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e9d7)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f9e5)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/handshake/request.c (ffffffff82092d19)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff820b757a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/watchdog.c (ffffffff812785db)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/bpf/offload.c (ffffffff81378719)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7869)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In mm/filemap.c (ffffffff813b6bf5)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In mm/slub.c (ffffffff8145a694)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8153f658)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/ioctl.c (ffffffff815f6c90)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff816172f2)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff8164f6b5)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8165cb3e)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff816b0e31)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747c19)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In io_uring/io-wq.c (ffffffff8182d38c)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff8185ea16)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81927be8)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca137b)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_remove_node
```
```
In drivers/rtc/dev.c (ffffffff81ddb424)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/dm-zone.c (ffffffff81e2a5f0)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81f38bfd)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88ef1)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8203094f)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820467c3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820603d3)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d9281)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd967)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb15)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In net/handshake/request.c (ffffffff821695c9)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff8219172a)
Location: include/asm-generic/bitops/instrumented-lock.h:23
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffff80001028a258)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffff800010374bd8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffff8000103da648)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffff8000104a33c0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffff8000104a8228)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffff8000104cca74)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce1c0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffff8000104d8e68)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffff80001051d51c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff800010598a2c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
```
```
In lib/rhashtable.c (ffff800010636be0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffff800010667de8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffff800010aab3f8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffff800010ae9ea8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
```
```
In net/core/xdp.c (ffff800010c067fc)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c0871c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4ee20)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf4e0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc238)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcdc0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44e84)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51ed4)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (c04b98f0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (c0561948)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (c05b2d40)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (c066539c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (c066a58c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (c0690338)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c0690e28)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (c069ada8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (c06d992c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749c78)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
```
```
In lib/rhashtable.c (c07dc960)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (c081021c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - lib/irq_poll.c:__irq_poll_complete
```
```
In drivers/rtc/dev.c (c0b89aec)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (c0bd3ae0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (c0d1f9a0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d217d4)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5efc8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcae80)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7ee0)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7ae8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e472e8)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52f90)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (c0e8755c)
Location: include/asm-generic/bitops/lock.h:40
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
c068c9a4-c068c9d0: clear_bit_unlock.constprop.0 (STB_LOCAL)
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
In arch/powerpc/kernel/watchdog.c (c00000000003751c)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c000000000092b20)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_updatepp
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_remove
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_insert
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7ec8)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In kernel/bpf/offload.c (c000000000335688)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (c000000000467fa0)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (c0000000004de2d8)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (c0000000005d0284)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (c0000000005d5e74)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (c00000000060616c)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000606dc0)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (c000000000613db0)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (c0000000006666b0)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f9ac)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcaec)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (c00000000081cea8)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (c000000000b8cf7c)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (c000000000bdf038)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (c000000000cf0e38)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2d14)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d5c8)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda178)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb790)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd94)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e799c0)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8ab28)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (c000000000ecf1f8)
Location: arch/powerpc/include/asm/bitops.h:99
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffffffe0001be2aa)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffe0001d497e)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - mm/filemap.c:unlock_page
```
```
In mm/slub.c (ffffffe00023b14c)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffe00024dadc)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/dcache.c (ffffffe00026c2c8)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/buffer.c (ffffffe000294408)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/mbcache.c (ffffffe0002c44b0)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/page-io.c (ffffffe000324c14)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffe0003288da)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffe0003453b2)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000345d2e)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffe00034e742)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffe000384ddc)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5354)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
```
```
In lib/rhashtable.c (ffffffe00046416c)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffe000493132)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffe0006b5dd6)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffe0006db9fe)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
```
```
In net/core/xdp.c (ffffffe000784ccc)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe0007864d0)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007bab18)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe0008152a0)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe000820be2)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c150)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f86a)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4b6)
Location: arch/riscv/include/asm/bitops.h:168
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811fa4c8)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812c8649)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff81319238)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff813c3aea)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c7e4d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813ea8db)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb31b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813f3c84)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8142f416)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b29b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523adf)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81552e5c)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/nvme/host/core.c (ffffffff81744b3d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/rtc/dev.c (ffffffff8181b884)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81843bb2)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81902cd3)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903f0f)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819405db)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a644d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b23b1)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0d06)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a657)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25948)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a51bc7)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffffffff811ed218)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812b9689)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff81309d97)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff813b4570)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b88cd)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813db35b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dbd9b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813e4704)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8141fe96)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bcbb)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513dbf)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81543085)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/nvme/host/core.c (ffffffff817267cd)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/rtc/dev.c (ffffffff817e2f74)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8180b212)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff818bcb03)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdd3f)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa0cb)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195ff0d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e9e1)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197daf6)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7417)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2708)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a0ecc7)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffffffff811f8298)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812c6459)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff81316d08)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff813c0f7a)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c52dd)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813e7c5b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e869b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813f1004)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8142b5b6)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149733b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fb6f)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8154eb9c)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff8185cd64)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff818931e2)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81953d03)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954f3f)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199176b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10ced)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1cc51)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b786)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a850d7)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a903c8)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81abdfb7)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In kernel/bpf/offload.c (ffffffff812065fe)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812d6625)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - mm/zsmalloc.c:unpin_tag
```
```
In fs/buffer.c (ffffffff81328d3f)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (ffffffff813d60b1)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813da50d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813fd462)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fdec5)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81406bcf)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8144254d)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af41a)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
```
```
In lib/rhashtable.c (ffffffff8153945b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815689ec)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81877fe4)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff818aede0)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff8197548a)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976f1f)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b41f3)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b5d0)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27b9c)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36dd9)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a919e5)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cfce)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81aca44b)
Location: include/asm-generic/bitops-instrumented.h:82
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
</li>
</ul>

## Differences
