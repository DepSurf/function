# Function: <code>clear_bits_unlock</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/watchdog.c (c00000000003751c)
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In kernel/bpf/offload.c (c000000000335688)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/zsmalloc.c (c000000000467fa0)
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (c0000000005d5e74)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (c00000000060616c)
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (c000000000613db0)
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f9ac)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcaec)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (c00000000081cea8)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_enable
  - lib/irq_poll.c:irq_poll_softirq
  - lib/irq_poll.c:irq_poll_complete
```
```
In drivers/rtc/dev.c (c000000000b8cf7c)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (c000000000bdf038)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (c000000000cf0e38)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2d14)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d5c8)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda178)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb790)
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e799c0)
Location: arch/powerpc/include/asm/bitops.h:86
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
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (c000000000ecf1f8)
Location: arch/powerpc/include/asm/bitops.h:86
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
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
