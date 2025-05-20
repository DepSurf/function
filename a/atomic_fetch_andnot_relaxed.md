# Function: <code>atomic_fetch_andnot_relaxed</code>

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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d5174)
Location: include/asm-generic/atomic-instrumented.h:505
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
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
In kernel/sched/fair.c (c0399d70)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/bpf/offload.c (c04b98f4)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (c04db25c)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - mm/filemap.c:unlock_page
```
```
In mm/zsmalloc.c (c056194c)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/buffer.c (c05b2d44)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:unlock_buffer
```
```
In fs/ext4/page-io.c (c06653a0)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (c066a590)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_end
```
```
In fs/jbd2/transaction.c (c069033c)
Location: arch/arm/include/asm/atomic.h:236
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
```
```
In fs/jbd2/commit.c (c0690e2c)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/journal.c (c069adac)
Location: arch/arm/include/asm/atomic.h:236
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
In ipc/util.c (c06d9930)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749c7c)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
```
```
In lib/rhashtable.c (c07dc964)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (c0810220)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:__irq_poll_complete
```
```
In drivers/rtc/dev.c (c0b89af0)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_release
```
```
In drivers/md/md.c (c0bd3ae4)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
```
```
In net/core/xdp.c (c0d1f9a4)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d217d8)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5efcc)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcae84)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7ee4)
Location: arch/arm/include/asm/atomic.h:236
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
In net/xfrm/xfrm_policy.c (c0de7aec)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e472ec)
Location: arch/arm/include/asm/atomic.h:236
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
In net/ipv6/seg6_hmac.c (c0e52f94)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (c0e87560)
Location: arch/arm/include/asm/atomic.h:236
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
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
