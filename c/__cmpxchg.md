# Function: <code>__cmpxchg</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (ffff8000100ad264)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:ptep_set_access_flags
```
```
In arch/arm64/mm/context.c (ffff8000100afc24)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b16fc)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca3d0)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_wp_range
```
```
In kernel/fork.c (ffff8000100f1950)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
```
```
In kernel/sched/core.c (ffff800010137dd4)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_q_add_safe
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/locking/qspinlock.c (ffff80001016abfc)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffff80001016b058)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
```
```
In kernel/locking/qrwlock.c (ffff80001016c92c)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/futex.c (ffff8000101b7d80)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/vmstat.c (ffff8000102db42c)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
```
```
In mm/memory.c (ffff8000102f667c)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/pgtable-generic.c (ffff8000103080c4)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff800010309d38)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/slub.c (ffff8000103470a4)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - mm/slub.c:put_cpu_partial
```
```
In mm/huge_memory.c (ffff800010356f14)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/page_idle.c (ffff8000103795e4)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (ffff80001043aa1c)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/lockref.c (ffff80001062901c)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/refcount.c (ffff800010637adc)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb2d4)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_install_table
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d5034)
Location: arch/arm64/include/asm/cmpxchg.h:172
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
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
In kernel/exit.c (c0358d80)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/task_work.c (c0377e0c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/core.c (c0386824)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_q_add_safe
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/psi.c (c03b3524)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
```
In kernel/locking/osq_lock.c (c03b665c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex.c (c0e9d6e0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
```
In kernel/rcu/tree.c (c03decc4)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/acct.c (c040ed20)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/debug/kdb/kdb_io.c (c043cdf8)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/trace/ring_buffer.c (c04587e8)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/trace_functions.c (c046bdbc)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
```
```
In kernel/trace/blktrace.c (c047223c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/irq_work.c (c048e1b0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_claim
```
```
In kernel/bpf/devmap.c (c04b72a0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In mm/oom_kill.c (c04e37d0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page_alloc.c (c052f854)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/frontswap.c (c0540e34)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/memcontrol.c (c0555b34)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/cleancache.c (c055e4e0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - mm/cleancache.c:cleancache_register_ops
```
```
In fs/exec.c (c0576238)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/exec.c:set_dumpable
```
```
In fs/dcache.c (c058a20c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
```
```
In fs/inode.c (c058dbe0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/inode.c:inode_set_flags
```
```
In fs/fs-writeback.c (c05a4e00)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c05b2ba4)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
```
```
In fs/direct-io.c (c05bbbe8)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/direct-io.c:sb_init_dio_done_wq
```
```
In fs/notify/mark.c (c05c1040)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (c05c82d8)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/crypto/hooks.c (c05d9a1c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/crypto/keysetup.c (c05dbc90)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/verity/hash_algs.c (c05de294)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/verity/open.c (c05df254)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
```
```
In fs/locks.c (c05e27c8)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/locks.c:locks_get_lock_context
```
```
In fs/posix_acl.c (c05ef8d0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
```
```
In fs/iomap/direct-io.c (c05f642c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/ext4/inode.c (c063fdc0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_update_bh_state
```
```
In fs/fuse/dir.c (c06c2810)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_invalidate_attr_mask
```
```
In fs/debugfs/file.c (c06d2dd8)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In block/bio.c (c078ac84)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - block/bio.c:update_io_ticks
```
```
In lib/llist.c (c07d9c7c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - lib/llist.c:llist_del_first
  - lib/llist.c:llist_add_batch
```
```
In lib/rhashtable.c (c07dcc98)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
```
In lib/errseq.c (c07ddb00)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_set
```
```
In lib/generic-radix-tree.c (c07ddfc0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
```
```
In lib/genalloc.c (c07eaa78)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - lib/genalloc.c:clear_bits_ll
  - lib/genalloc.c:set_bits_ll
```
```
In lib/sbitmap.c (c0812c14)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
```
```
In drivers/tty/tty_audit.c (c09694d0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
```
In drivers/char/random.c (c09aaa80)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e484)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3e96c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
```
```
In drivers/md/md.c (c0bcc4b4)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (c0bde818)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:__dm_get_module_param
```
```
In net/core/sock.c (c0ccc7d8)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/dev.c (c0cefb80)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_schedule_prep
```
```
In net/core/dst.c (c0cfb268)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/core/dst.c:__dst_destroy_metrics_generic
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/filter.c (c0d14ddc)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_skb_set_tunnel_proto
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/netpoll.c (c0d28ea0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwtunnel.c (c0d35e38)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/core/lwtunnel.c:lwtunnel_encap_add_ops
```
```
In net/core/bpf_sk_storage.c (c0d48714)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
```
```
In net/ipv4/route.c (c0d699b0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/protocol.c (c0d6d274)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_add_offload
  - net/ipv4/protocol.c:inet_add_protocol
```
```
In net/ipv4/tcp.c (c0d7e91c)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d913c4)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv6/route.c (c0e1a574)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_icmp.c (c0e543d0)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_register_icmp_sender
```
```
In net/ipv6/protocol.c (c0e54a14)
Location: arch/arm/include/asm/cmpxchg.h:156
Inline: True
Inline callers:
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_add_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_add_protocol
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
In arch/powerpc/kernel/fadump.c (c00000000004d200)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:crash_fadump
```
```
In arch/powerpc/kernel/smp.c (c000000000054140)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock
  - arch/powerpc/kernel/smp.c:nmi_ipi_lock_start
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a06bc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_put
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c75f8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000db110)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_tce
```
```
In arch/powerpc/xmon/xmon.c (c000000000109720)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:get_output_lock
  - arch/powerpc/xmon/xmon.c:get_output_lock
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c0000000001218ec)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_commence_exit
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_commence_exit
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_commence_exit
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123eb0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:kvmppc_deliver_irq_passthru
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_eoi
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_cppr
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_xirr
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_deliver_irq
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_set_vcpu_irq
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_set_vcpu_irq
```
```
In kernel/panic.c (c00000000013c83c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/exit.c (c0000000001422cc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/task_work.c (c00000000016ed14)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/task_work.c:task_work_add
```
```
In kernel/smpboot.c (c000000000179390)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (c0000000001798e8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (c0000000001840e4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:set_nr_if_polling
```
```
In kernel/sched/fair.c (c000000000192880)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/sched/psi.c (c0000000001bec44)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
```
In kernel/locking/rwsem.c (c000000000ee7b68)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/osq_lock.c (c0000000001c2328)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (c0000000001d0454)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (c0000000001ec35c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/time/posix-cpu-timers.c (c0000000002110f0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/acct.c (c000000000230274)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/kexec_core.c (c000000000232414)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/debug/kdb/kdb_io.c (c00000000027548c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/trace/ring_buffer.c (c00000000029e930)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/tracing_map.c (c0000000002b750c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In kernel/trace/trace_functions.c (c0000000002ba00c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In kernel/trace/blktrace.c (c0000000002c1c38)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/irq_work.c (c0000000002feb1c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_claim
```
```
In kernel/bpf/devmap.c (c000000000331528)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In kernel/events/core.c (c00000000034c204)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In kernel/jump_label.c (c00000000035f664)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/oom_kill.c (c00000000036e1b4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/vmscan.c (c0000000003877fc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmzone.c (c00000000039921c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/mmap.c (c0000000003d030c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/page_alloc.c (c0000000003e6c3c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/frontswap.c (c0000000004019f8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/ksm.c (c00000000041fd60)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (c000000000439ac0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c000000000442d70)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (c000000000448ac0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c00000000044cd80)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/cleancache.c (c0000000004627d0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/cleancache.c:cleancache_register_ops
```
```
In mm/memfd.c (c0000000004717dc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c000000000472a2c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (c000000000486d3c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/exec.c:set_dumpable
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (c0000000004921d8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/dcache.c (c0000000004a3748)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
```
```
In fs/inode.c (c0000000004a6660)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/inode.c:inode_set_flags
  - fs/inode.c:generic_update_time
```
```
In fs/fs-writeback.c (c0000000004c98c8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (c0000000004d72f0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In fs/buffer.c (c0000000004de654)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
```
```
In fs/direct-io.c (c0000000004e9dcc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/direct-io.c:sb_init_dio_done_wq
```
```
In fs/notify/mark.c (c0000000004f0a98)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (c0000000004fa9e4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/aio.c (c000000000502c9c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/io_uring.c (c000000000509518)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In fs/crypto/keysetup.c (c00000000051c10c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/verity/enable.c (c00000000051f600)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/hash_algs.c (c00000000051f8ac)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/verity/open.c (c000000000520bb8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In fs/locks.c (c000000000523a1c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/locks.c:locks_get_lock_context
```
```
In fs/posix_acl.c (c0000000005361dc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053d994)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/proc/inode.c (c00000000054f498)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (c00000000056c370)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In fs/ext4/dir.c (c00000000057fb90)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c00000000059f138)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (c0000000005a9388)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_update_bh_state
```
```
In fs/ext4/namei.c (c0000000005ccb44)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c000000000621138)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c00000000062c578)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c00000000062dff8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In fs/fat/namei_vfat.c (c000000000630d84)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (c00000000064f2bc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (c00000000065dc90)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In fs/debugfs/file.c (c00000000065ffe8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/integrity/ima/ima_api.c (c000000000730768)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (c00000000076f170)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - block/bio.c:update_io_ticks
```
```
In block/blk-mq.c (c00000000078702c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c00000000078bdf8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (c0000000007a3be8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-cgroup.c (c0000000007a7b64)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (c0000000007b2370)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/llist.c (c0000000007d8ce4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - lib/llist.c:llist_del_first
  - lib/llist.c:llist_add_batch
```
```
In lib/rhashtable.c (c0000000007dce94)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/errseq.c (c0000000007de3f0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_set
```
```
In lib/genalloc.c (c0000000007ef3bc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - lib/genalloc.c:clear_bits_ll
  - lib/genalloc.c:set_bits_ll
```
```
In lib/sbitmap.c (c00000000081eb38)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
```
```
In drivers/rapidio/rio.c (c0000000008941dc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/tty/tty_ldsem.c (c0000000008fec20)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_audit.c (c0000000009026d8)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
```
In drivers/char/random.c (c000000000949940)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f9e4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a201e4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In drivers/vfio/vfio.c (c000000000aaeb7c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (c000000000bbb774)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/md.c (c000000000bcda88)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (c000000000bf0848)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/sock.c (c000000000c84368)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (c000000000c89c08)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In net/core/dev.c (c000000000cb33a4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_schedule_prep
```
```
In net/core/dst.c (c000000000cc14d0)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/dst.c:__dst_destroy_metrics_generic
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/filter.c (c000000000cde658)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_skb_set_tunnel_proto
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/sock_diag.c (c000000000ced668)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/core/netpoll.c (c000000000cfd4e4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwtunnel.c (c000000000d0edcc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/core/lwtunnel.c:lwtunnel_encap_add_ops
```
```
In net/core/bpf_sk_storage.c (c000000000d2ab38)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/ipv4/route.c (c000000000d5be7c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/protocol.c (c000000000d6053c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_add_offload
  - net/ipv4/protocol.c:inet_add_protocol
```
```
In net/ipv4/tcp.c (c000000000d7564c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8d360)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv6/route.c (c000000000e41680)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_fib.c (c000000000e463f4)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/ip6_icmp.c (c000000000e8c48c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_register_icmp_sender
```
```
In net/ipv6/protocol.c (c000000000e8cd7c)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_add_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_add_protocol
```
```
In net/xdp/xdp_umem.c (c000000000ec1320)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (c000000000ec3dbc)
Location: arch/powerpc/include/asm/cmpxchg.h:403
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
