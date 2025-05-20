# Function: <code>raw_atomic64_inc</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8213de6a)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096d46)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810f2460)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a56e6)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8123589b)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff8124b0f2)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8128f924)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812ee7a8)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap_open
```
```
In kernel/events/ring_buffer.c (ffffffff8137c493)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/filemap.c (ffffffff8139175e)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/oom_kill.c (ffffffff8139703c)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813b6b09)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813c0106)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813c32f5)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff813e9bc9)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813fea85)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff81406e7c)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff836e6fdf)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff81428dbc)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/zswap.c (ffffffff81436818)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/slub.c (ffffffff8145d1bb)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/kfence/core.c (ffffffff81465cf2)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/khugepaged.c (ffffffff814823c6)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff81490f0d)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff81493761)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8149997c)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff814cdafc)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff814d71cf)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
```
```
In fs/file.c (ffffffff814dd789)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff836ef178)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff81514026)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff8154f825)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff81575713)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff815c99f0)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
```
```
In ipc/shm.c (ffffffff81680450)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/keys/dh.c (ffffffff816925c2)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/landlock/fs.c (ffffffff8172ae44)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8172f32e)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81733179)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In security/integrity/ima/ima_api.c (ffffffff81733757)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/aead.c (ffffffff81741ea2)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff817421a9)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81742ff2)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff8174514d)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
```
```
In crypto/shash.c (ffffffff81746805)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff8174784e)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81747be1)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/dh.c (ffffffff8174896e)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh.c:dh_safe_prime_set_secret
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a801)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff817530dd)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In crypto/rng.c (ffffffff81758463)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff817593c2)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-ioc.c (ffffffff817770d5)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-iocost.c (ffffffff817b0039)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In io_uring/msg_ring.c (ffffffff817d998e)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/rsrc.c (ffffffff817e2799)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In lib/iov_iter.c (ffffffff81811c77)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff81a953cd)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b227a5)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In drivers/base/memory.c (ffffffff81b65dcd)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe232)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81c4a372)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md-bitmap.c (ffffffff81d717e4)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81e22348)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81eacbd3)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/tcp.c (ffffffff81f0aebc)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c162)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv4/icmp.c (ffffffff81f4cf5f)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ipmr.c (ffffffff81f7e734)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff81fabed5)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81faffe5)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81fba140)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81fe364b)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81feb846)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81ff185d)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81ff43cb)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd9ec)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81fffb7b)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff8200d47e)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820272dd)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/handshake/netlink.c (ffffffff82092685)
Location: include/linux/atomic/atomic-arch-fallback.h:3096
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
In arch/x86/kernel/nmi.c (ffffffff8221fe6a)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e2b6)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810fc030)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b51d6)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8124f4e8)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff81264ff2)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff812aae84)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff8130ce25)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap_open
```
```
In kernel/bpf/verifier.c (ffffffff813230af)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/tcx.c (ffffffff8137b7b0)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/bpf/tcx.c:tcx_link_update
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
```
```
In kernel/events/ring_buffer.c (ffffffff813a57ae)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/filemap.c (ffffffff813bb4cc)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/oom_kill.c (ffffffff813c0db0)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813df9c9)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813e7740)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/util.c (ffffffff813ede15)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff81414d37)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8142af23)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff8143352c)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff8391958f)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/slub.c (ffffffff814578bb)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff814625ec)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/zswap.c (ffffffff81470b4b)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/kfence/core.c (ffffffff81494f70)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/khugepaged.c (ffffffff814b176c)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff814c087a)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:reclaim_high
  - mm/memcontrol.c:reclaim_high
```
```
In mm/hugetlb_cgroup.c (ffffffff814c30d3)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814c911d)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff8150043c)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8150954f)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
```
```
In fs/file.c (ffffffff815101d9)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff839221c8)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff815484f6)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/backing-file.c (ffffffff81581864)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
```
```
In fs/coredump.c (ffffffff81585664)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff815ae070)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81602985)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_p2_aligned
```
```
In ipc/shm.c (ffffffff816bc840)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/keys/dh.c (ffffffff816ceb92)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/landlock/fs.c (ffffffff8176c964)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fcbc)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81774177)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/aead.c (ffffffff81782d82)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff81783089)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/lskcipher.c (ffffffff81783d9a)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_decrypt
  - crypto/lskcipher.c:crypto_lskcipher_encrypt
  - crypto/lskcipher.c:crypto_lskcipher_crypt
```
```
In crypto/skcipher.c (ffffffff81785342)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff81787e76)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_update
```
```
In crypto/shash.c (ffffffff817889b1)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff817896be)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81789a51)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/dh.c (ffffffff8178a8be)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh.c:dh_safe_prime_set_secret
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c3c1)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/rng.c (ffffffff8179a363)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff8179b2c2)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-ioc.c (ffffffff817b9305)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-iocost.c (ffffffff817f3e49)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In io_uring/msg_ring.c (ffffffff8181dcae)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In drivers/tty/tty_io.c (ffffffff81ae7dab)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79325)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In drivers/base/memory.c (ffffffff81bb9c4d)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c12982)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cacccb)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
```
```
In drivers/net/netkit.c (ffffffff81ce658f)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/net/netkit.c:netkit_link_update
  - drivers/net/netkit.c:netkit_link_release
  - drivers/net/netkit.c:netkit_prog_detach
  - drivers/net/netkit.c:netkit_prog_attach
```
```
In drivers/net/tun.c (ffffffff81cffcf5)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d06fd7)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
```
```
In drivers/md/md-bitmap.c (ffffffff81e288c3)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/skbuff.c (ffffffff81ed2ee4)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/scm.c (ffffffff81ee0288)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81f6f690)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff510d)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8201306f)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034313)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82044ddf)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/tcp_ao.c (ffffffff820585e5)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_ignore_icmp
```
```
In net/unix/af_unix.c (ffffffff820792f5)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8207d645)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff820875a1)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff820b1555)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b9511)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff820bf45c)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff820c12f7)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc86b)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff820ce971)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff820dc448)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820f67a1)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mm_open
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/handshake/netlink.c (ffffffff82168f97)
Location: include/linux/atomic/atomic-arch-fallback.h:3101
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
