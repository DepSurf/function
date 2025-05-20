# Function: <code>arch_clear_bit_unlock</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4e98)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812be179)
Location: arch/x86/include/asm/bitops.h:86
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
Location: arch/x86/include/asm/bitops.h:86
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
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b694d)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813d821b)
Location: arch/x86/include/asm/bitops.h:86
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
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813e1654)
Location: arch/x86/include/asm/bitops.h:86
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
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488e0b)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d6af)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81539a5c)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81837264)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8186bf13)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff819307f0)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81962a43)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969cfb)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfb1d)
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819dbbc1)
Location: arch/x86/include/asm/bitops.h:86
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
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a443d7)
Location: arch/x86/include/asm/bitops.h:86
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
Location: arch/x86/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a7ba17)
Location: arch/x86/include/asm/bitops.h:86
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812d0069)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813cf86d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813f22fb)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813fb6a4)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2cbb)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b4ff)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8155a87c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81868bd4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8189dd32)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81962d03)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963f3f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a076b)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a066ad)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12af1)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7afc7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81ab2d77)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8130706e)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8135d8d7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:__io_free_req
```
```
In fs/ext4/resize.c (ffffffff8141c4bd)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff8143fa73)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81448de7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcfa3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158ea87)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff815e41f2)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff815ed613)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff8193c7c4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8196dfed)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81a360be)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a792e0)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5fae)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01d9a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10957)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b7532a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8151e)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81312dae)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (ffffffff8136b4c7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:__io_free_req
```
```
In fs/ext4/resize.c (ffffffff8143026d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff8145bb43)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81465987)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a1b3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab5e7)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff81608722)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff81611dd3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff819427b4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81975186)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81a3848e)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a820f0)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e1e)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fe7a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ec47)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b8409a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90d5e)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff81235094)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/filemap.c (ffffffff8125ddcc)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/filemap.c:end_page_private_2
```
```
In mm/zsmalloc.c (ffffffff813180fd)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff81461483)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8146b137)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520ac1)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b644a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815eb332)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff815f54b3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff81925fe4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff819591c5)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81a1f2c5)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b1d8)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee715)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afda6a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c8d2)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72d1a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7ff65)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff8126f1c4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/filemap.c (ffffffff8129a4ec)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/filemap.c:end_page_private_2
```
```
In mm/zsmalloc.c (ffffffff81364605)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_worker_cancel_cb
```
```
In fs/ext4/resize.c (ffffffff8148aadd)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff814b6973)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff814c184c)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec61)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c98d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff816576d8)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff81662923)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff819c8f54)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff819fe965)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81a06220)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81ad3555)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b247f8)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeac5)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfb6a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfac2)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a200)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b805)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff812be089)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/filemap.c (ffffffff812f0175)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In fs/buffer.c (ffffffff814447f0)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff8150d27d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff815402ce)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8154c1de)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d754)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In io_uring/io-wq.c (ffffffff816da56a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff816ea19c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8176f0d8)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In lib/nmi_backtrace.c (ffffffff8177c792)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/rtc/dev.c (ffffffff81b2a144)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81b65f08)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81b6de92)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81c50e9e)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cac111)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4194c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55f3e)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d682e1)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7f67)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb683)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deae6f)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff81321807)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d60f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/filemap.c (ffffffff8135b505)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In fs/buffer.c (ffffffff814d3418)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff815a7fc2)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff815dee35)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff815ebfbe)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1209)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a664a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff817da3ba)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8189eaa8)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81cbdda4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81d010ff)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81d0a3b0)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81e064fc)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69ce6)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a76f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2066c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33335)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa995e)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae27f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbea52)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff8203925e)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff813512b9)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e609)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/filemap.c (ffffffff8138d365)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In fs/buffer.c (ffffffff8150a6a8)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff815de842)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff81616895)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81623a9e)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a119)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e75ac)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff818196c6)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff818e1078)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81d256b4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81d6a45c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In drivers/md/dm-zone.c (ffffffff81d734ea)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81e78d2d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5c91)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a29f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80143)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92663)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a2e0)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e9d7)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f9e5)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/handshake/request.c (ffffffff82092d19)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff820b757a)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/bpf/offload.c (ffffffff81378719)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7869)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In mm/filemap.c (ffffffff813b6bf5)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_private_2
```
```
In mm/slub.c (ffffffff8145a694)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8153f658)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
```
In fs/ext4/resize.c (ffffffff816172f2)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/commit.c (ffffffff8164f6b5)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff8165cb3e)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747c19)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In io_uring/io-wq.c (ffffffff8182d38c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/rhashtable.c (ffffffff8185ea16)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81927be8)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca137b)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_remove_node
```
```
In drivers/rtc/dev.c (ffffffff81ddb424)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/dm-zone.c (ffffffff81e2a5f0)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In net/core/xdp.c (ffffffff81f38bfd)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88ef1)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8203094f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820467c3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820603d3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d9281)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd967)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb15)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In net/handshake/request.c (ffffffff821695c9)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff8219172a)
Location: arch/x86/include/asm/bitops.h:85
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fa4c8)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812c8649)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c7e4d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813ea8db)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813f3c84)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b29b)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523adf)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81552e5c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/nvme/host/core.c (ffffffff81744b3d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/rtc/dev.c (ffffffff8181b884)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff81843bb2)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81902cd3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903f0f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819405db)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a644d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b23b1)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a657)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a51bc7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812b9689)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b88cd)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813db35b)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813e4704)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bcbb)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513dbf)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81543085)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/nvme/host/core.c (ffffffff817267cd)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/rtc/dev.c (ffffffff817e2f74)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff8180b212)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff818bcb03)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdd3f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa0cb)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195ff0d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e9e1)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7417)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a0ecc7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812c6459)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c52dd)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813e7c5b)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff813f1004)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149733b)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fb6f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8154eb9c)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff8185cd64)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff818931e2)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff81953d03)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954f3f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199176b)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10ced)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1cc51)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a850d7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81abdfb7)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (ffffffff812d6625)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - mm/zsmalloc.c:unpin_tag
```
```
In fs/buffer.c (ffffffff81328d3f)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813da50d)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (ffffffff813fd462)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (ffffffff81406bcf)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af41a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
```
```
In lib/rhashtable.c (ffffffff8153945b)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815689ec)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (ffffffff81877fe4)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (ffffffff818aede0)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (ffffffff8197548a)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976f1f)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b41f3)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b5d0)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27b9c)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a919e5)
Location: arch/x86/include/asm/bitops.h:85
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
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81aca44b)
Location: arch/x86/include/asm/bitops.h:85
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
</li>
</ul>

## Differences
