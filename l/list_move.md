# Function: <code>list_move</code>

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
In arch/x86/kernel/kprobes/opt.c (ffffffff810607a6)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/rt.c (ffffffff810bf06e)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff810d6377)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/audit_tree.c (ffffffff8112ad77)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In mm/page_alloc.c (ffffffff811929af)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff811a2240)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/percpu.c (ffffffff811b0024)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff811b30a3)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff811b8eb5)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff811da29f)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_node
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/ksm.c (ffffffff811e6c0b)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff811ee266)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/hugetlb_cgroup.c (ffffffff81201529)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff81224952)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff8122bfd9)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mark_mounts_for_expiry
```
```
In fs/libfs.c (ffffffff812348ff)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff8123508a)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8123cf1a)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff81250ada)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
```
```
In fs/proc/kcore.c (ffffffff81286e50)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fat/cache.c (ffffffff812f53e3)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff8130b37e)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
```
```
In fs/fuse/dev.c (ffffffff8130fe00)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff8139d9cc)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/deadline-iosched.c (ffffffff813dccda)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff813e10a0)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_merged_requests
```
```
In drivers/base/core.c (ffffffff815481dd)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff81fac9aa)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff81559cfb)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_move_after
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
```
```
In drivers/base/power/clock_ops.c (ffffffff8155d478)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff8156292f)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/scsi/scsi_error.c (ffffffff815ab2c1)
Location: include/linux/list.h:154
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f8c49)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81628cf6)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162ace3)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8162de29)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162f34b)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81647546)
Location: include/linux/list.h:154
Inline: True
```
```
In drivers/md/md.c (ffffffff8169b227)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/ipv4/tcp_cong.c (ffffffff817808c7)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/unix/garbage.c (ffffffff817c2641)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff810605b6)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/rt.c (ffffffff810c2960)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff810db322)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff81133f04)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In mm/page_alloc.c (ffffffff811a8403)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff811b7c73)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff811bfccf)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff811ca884)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffffffff811ccc5b)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff811d3155)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff811f972d)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_node
```
```
In mm/ksm.c (ffffffff81205c1b)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff8120d866)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff81217fd3)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff81225ce9)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff8124cafd)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff81254a82)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff8125d7ba)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81264fe5)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff8127917a)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
```
```
In fs/proc/kcore.c (ffffffff812b4029)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fat/cache.c (ffffffff813290a8)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff8133fb1c)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff8134396c)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff813daa73)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/deadline-iosched.c (ffffffff8142292a)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff814272b1)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_merged_requests
```
```
In drivers/base/core.c (ffffffff81599e0c)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff81fd93b7)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff815ad14f)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff815b178a)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff815b72ff)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/scsi/scsi_error.c (ffffffff8160323a)
Location: include/linux/list.h:154
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81658caa)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a8056)
Location: include/linux/list.h:154
Inline: True
```
```
In drivers/md/md.c (ffffffff816fc330)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/ipv4/tcp_cong.c (ffffffff817edda7)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/unix/garbage.c (ffffffff8182f666)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff8183b2de)
Location: include/linux/list.h:154
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
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
In arch/x86/kernel/kprobes/opt.c (ffffffff81063656)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/rt.c (ffffffff810c89d1)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff810e1df2)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8113dc84)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81196b70)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In mm/page_alloc.c (ffffffff811b87d2)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff811c82c5)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff811d04ff)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff811da9a4)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffffffff811dcd4b)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff811e3015)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff8120a03d)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_node
```
```
In mm/ksm.c (ffffffff81217c2b)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff8121f8bd)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff8122a573)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812382c9)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff8125faed)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff81267fc2)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff81270cda)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8127842a)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff8128cda4)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
```
```
In fs/proc/kcore.c (ffffffff812c98c1)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fat/cache.c (ffffffff8133ede8)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff813558ac)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff81359f72)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff813f23b3)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/deadline-iosched.c (ffffffff8143da4a)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff81443ca3)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_merged_requests
```
```
In drivers/base/core.c (ffffffff815c82e8)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff82017070)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff815dbf0f)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff815e0a6a)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff815e660f)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8162131b)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff81623ff4)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff8163292a)
Location: include/linux/list.h:167
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81686a2d)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d6176)
Location: include/linux/list.h:167
Inline: True
```
```
In drivers/md/md.c (ffffffff8172c954)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e72a)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/unix/garbage.c (ffffffff818610fa)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff8186ccde)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
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
In arch/x86/kernel/kprobes/opt.c (ffffffff810625d5)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/rt.c (ffffffff810c3979)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff810e0f32)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8113f31d)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8119dfb2)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In mm/page_alloc.c (ffffffff811c0bb6)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff811d0d2d)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff811d89a1)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff811e4392)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffffffff811e5fa7)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff811ed4b5)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff812155b6)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8122382b)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff8122b120)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812361c7)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff81243f30)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff8126d407)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff81275ffc)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff8127e499)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8128574a)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff81299fac)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff812a36dd)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff812d68ff)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff812df4c5)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813539a7)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff8136a4a7)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff8136f25a)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff813fe6a4)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/blk-mq.c (ffffffff814318f8)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/deadline-iosched.c (ffffffff8144ceb1)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff81452ec9)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_merged_requests
```
```
In drivers/base/core.c (ffffffff815dd05f)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff820f8ddf)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff815f0a8f)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff815f58ee)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff815fafee)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81635cd0)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff816390c7)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff81647369)
Location: include/linux/list.h:167
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169be28)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816e8116)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/md/md.c (ffffffff81745259)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/ipv4/tcp_cong.c (ffffffff8183eefc)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/unix/garbage.c (ffffffff81885840)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/addrconf.c (ffffffff81891881)
Location: include/linux/list.h:167
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
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
In arch/x86/kernel/kprobes/opt.c (ffffffff81066725)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810c7f7a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810cb13c)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff810e9202)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8114c15d)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811adbc2)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff811bd546)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/page_alloc.c (ffffffff811d51a2)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff811e621d)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff811ef0d1)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff811f978b)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffffffff811fc1e7)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff81203905)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff81230187)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8123ee6b)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff81246820)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff8125500a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff81263d90)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff8128fd27)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff8129866c)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff812a0f79)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812a81ca)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff812bd37c)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff812c6eca)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff812fb14f)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff81303e4b)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813785c7)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff8138f047)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff81393e7a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff81426c64)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/deadline-iosched.c (ffffffff814795b1)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff8147ccf9)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_merged_requests
```
```
In drivers/base/core.c (ffffffff8164405f)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff82702493)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff81657fdf)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff8165d80e)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff816631ae)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169ef48)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816a179a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff816b03aa)
Location: include/linux/list.h:168
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81706e38)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817548f6)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817748fe)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff817b7429)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/unix/garbage.c (ffffffff819069f0)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff810692d5)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810d016f)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810d2873)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff810f154a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8115abcf)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811c5148)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff811dd6e7)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/page_alloc.c (ffffffff811f65d1)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff812077a8)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8120f13a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff8121b9ab)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffffffff8121dbf4)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff812245c5)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff812535a0)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff81262627)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff81269c29)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff81278e6a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812880b9)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff812b5798)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff812bea9c)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff812c7b09)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812ced7f)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff812e5f34)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff812f11db)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff8132870e)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff81332cb7)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813a7071)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff813be023)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff813c36c5)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff81459b54)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/deadline-iosched.c (ffffffff814adefa)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff814b16fa)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_merged_requests
```
```
In drivers/base/core.c (ffffffff8167f423)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff8272c1d8)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff81693ac7)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff8169960e)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff8169eabe)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816db010)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816ddf50)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff816ec9b1)
Location: include/linux/list.h:168
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81745aa6)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c3ae)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81794ee2)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b503e)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff8180169d)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/unix/garbage.c (ffffffff8195d9ed)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff8106f085)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810d9996)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810dc1e3)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff810fcbda)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8116793f)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6d48)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff811edae7)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/page_alloc.c (ffffffff81208942)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff8121a328)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff812222dc)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff8122e98b)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffffffff81230bd4)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff81237615)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff812674e0)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff81276ea7)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff8127e4e9)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff8128d51a)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff8129d001)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff812caab6)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff812d381c)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff812dcd09)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812e40ef)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff812fab14)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff813048f3)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff8133f8d0)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff8134a0ac)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813bfe61)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff813d7663)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff813dcea2)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff814770a4)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff814c7d73)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff8169f896)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff828e4b34)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff816b414c)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff816b9dbe)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff816bf2be)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fcfbd)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff817002aa)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff817104f1)
Location: include/linux/list.h:168
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81769b96)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2910)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bb3a2)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db58e)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff8182d8ae)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/unix/garbage.c (ffffffff8199252d)
Location: include/linux/list.h:168
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff8107314a)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810e0c05)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810e31aa)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff811052cb)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8117457f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb73e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff8120551b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff8122c6d2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8123193f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff8123e092)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff8124100a)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff81248bc5)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffff8126ed99)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81282f59)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8129270c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff8129a2e8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812a7ea8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812b81b2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff812e74d0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff812f1700)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff812fb3d0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81302912)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff8131b347)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81326784)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff81367bc3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff81371a68)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813ea664)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff81401fb3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff814089b3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff814a4dab)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff814f65f9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff816d8065)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff828ff27f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff816edf54)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff816f400f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff816fa41f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81735290)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff8173a093)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff8174bd8a)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a74b8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e1a0f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fad12)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181bfae)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff8186f8d9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff819314a0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffffffff819fdb26)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff8107412a)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810e79ae)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810ed2dd)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/power/wakelock.c (ffffffff81111652)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff811803ef)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff811821f9)
Location: include/linux/list.h:199
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7e9e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff812128ab)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff8123a4d8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8123f9ff)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff8124c4eb)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff8124f4b2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff81257015)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffff8127dbd9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81292a79)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812a248e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff812aa1a8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812b939c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812ca092)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff812f9042)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff813032b0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff8130cef1)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8130d1f0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81315992)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff8132e157)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81339514)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff8137fe43)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff81389ea8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff81404704)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff8141bea3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff814202b9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff814bfa3b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff81514489)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff816fc165)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff82908422)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff81711f34)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff8171840f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff8171e7cf)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81759020)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff8175dde3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff8176ff0a)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817caf28)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818128df)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182bb52)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d36e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff818a16de)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81963690)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffffffff81a34716)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff8107b248)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810f2b3e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810f746a)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff8111c722)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff81192d37)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff81195d09)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b439)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
```
```
In kernel/events/core.c (ffffffff8123e77a)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff8126a163)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8126d91b)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff8127a81b)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff8127d5f1)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/slab_common.c:shutdown_memcg_caches
```
```
In mm/list_lru.c (ffffffff812856f5)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffff812afd13)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff812c7214)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812d6b9c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff812deebf)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812edefb)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812ffe17)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff81331ff7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff8133cd70)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff8134691c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff81349a10)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8134f121)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/notify/mark.c (ffffffff81367ff7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81373fc8)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/io_uring.c (ffffffff81382775)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_overflow_flush
```
```
In fs/proc/kcore.c (ffffffff813ca2d7)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/configfs/dir.c (ffffffff813d506c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/mballoc.c (ffffffff8140adae)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/fat/cache.c (ffffffff814522be)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_lookup
```
```
In fs/ecryptfs/messaging.c (ffffffff8146ab56)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
```
```
In fs/fuse/dev.c (ffffffff8146f007)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff814bfc60)
Location: include/linux/list.h:213
Inline: True
```
```
In crypto/algapi.c (ffffffff8151fe8e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff815752d9)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff817b5a78)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff817cd964)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff817d3e0c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff817daf0e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818175a5)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff8181d5bd)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff818324b3)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893dd6)
Location: include/linux/list.h:213
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e392f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818fdf22)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8191fe0e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff819714c2)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81a36c41)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81a6ecb0)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/unix/garbage.c (ffffffff81b29529)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106641b)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068479)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107b0aa)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810f0d0e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810f566a)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff81117082)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8118fea7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff811929a9)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e3bd)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
```
```
In kernel/events/core.c (ffffffff81248b6f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff81274c11)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8127800f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff81284faa)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_chunk_move
```
```
In mm/list_lru.c (ffffffff8128f9d5)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff812d196c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812e26e0)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff812eac8f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812f956b)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff8130c1b7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff8133da17)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff81348c30)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff81352e0c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8135692a)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8135bfd1)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/notify/mark.c (ffffffff81375367)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81381fc4)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/io_uring.c (ffffffff81391dd2)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/io_uring.c:__io_cqring_overflow_flush
```
```
In fs/proc/kcore.c (ffffffff813dbf97)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/configfs/dir.c (ffffffff813e6d8c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/mballoc.c (ffffffff8141e228)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/fat/cache.c (ffffffff8146e79e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_lookup
```
```
In fs/ecryptfs/messaging.c (ffffffff814855c6)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
```
```
In fs/fuse/dev.c (ffffffff81489767)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff814dd6c0)
Location: include/linux/list.h:213
Inline: True
```
```
In crypto/algapi.c (ffffffff8153ccfe)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff815920b9)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff817caee8)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff817e22e4)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff817e885c)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff817efaae)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818266d5)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff8182c1a9)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff818430c3)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189f771)
Location: include/linux/list.h:213
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ece0f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81906806)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8192751e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81c27793)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81a38ff1)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81a7768e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/unix/garbage.c (ffffffff81b37e59)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066adb)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107c2a0)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810f083e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810f773d)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff811177b2)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff81190dd7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff811938c6)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81222626)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
```
```
In kernel/events/core.c (ffffffff8124cb85)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff81279f11)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8127cd6f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff8128ae0d)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_chunk_move
```
```
In mm/list_lru.c (ffffffff81295035)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff812d67c2)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:enqueue_huge_page
```
```
In mm/ksm.c (ffffffff812e9e70)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff812f2745)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812ffb39)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff813127b7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff81343d16)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff8134f000)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff813599d9)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8135d93a)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81362c82)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff8137bd07)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81389032)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/proc/kcore.c (ffffffff813e2f39)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/configfs/dir.c (ffffffff813ee38b)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/mballoc.c (ffffffff81424a2c)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/fat/cache.c (ffffffff81474063)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff8148b036)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
```
```
In fs/fuse/dev.c (ffffffff8148efe8)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff814e4030)
Location: include/linux/list.h:213
Inline: True
```
```
In crypto/algapi.c (ffffffff815453de)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff81598ef9)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff817ae858)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff817c66c4)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff817ccd75)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff817d416e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81809935)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff8180f4b1)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff818262a6)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882201)
Location: include/linux/list.h:213
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d060f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9e06)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190abde)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81c1996e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81a202a1)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81a5fcad)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/unix/garbage.c (ffffffff81b25af1)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070d9b)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8108a3fa)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff811092ce)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff81111d4b)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff81137b12)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/clockevents.c (ffffffff811781a3)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/audit_tree.c (ffffffff811b9cb7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff811bcad4)
Location: include/linux/list.h:213
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811d9d70)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8125a2d2)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
```
In kernel/events/core.c (ffffffff81289aa5)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff812b7f32)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff812baeba)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff812c5ffc)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff812ca5b7)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/list_lru.c (ffffffff812d5695)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff8131c553)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:enqueue_huge_page
```
```
In mm/ksm.c (ffffffff81331da0)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff8133a177)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/huge_memory.c (ffffffff81349789)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e220)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff81391646)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff8139d0a0)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff813a7e79)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff813ac01a)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/pnode.c (ffffffff813b1482)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff813c8b1a)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff813d6323)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/proc/kcore.c (ffffffff81434a49)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/configfs/dir.c (ffffffff814402ab)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/mballoc.c (ffffffff81478679)
Location: include/linux/list.h:213
Inline: True
```
```
In fs/fat/cache.c (ffffffff814cad0d)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff814e2876)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
```
```
In fs/fuse/dev.c (ffffffff814e6a58)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff8153d450)
Location: include/linux/list.h:213
Inline: True
```
```
In crypto/algapi.c (ffffffff815a5b61)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff816011d9)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/iommu/io-pgfault.c (ffffffff818302ef)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81837a78)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff81850a54)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff81857345)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff8185f4ab)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81893de5)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff81899a3d)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff818b1bc6)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81913ba1)
Location: include/linux/list.h:213
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196ae8f)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819864a6)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab28e)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81d28fa8)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81ad4431)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81b18eda)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/unix/garbage.c (ffffffff81beb21d)
Location: include/linux/list.h:213
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ed68)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081fd3)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a93a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff81124f5e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff8112ebcb)
Location: include/linux/list.h:215
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff8115a15e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/clockevents.c (ffffffff811ad323)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/audit_tree.c (ffffffff811eceba)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff811f0214)
Location: include/linux/list.h:215
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8120f641)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff812a3366)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
```
In kernel/events/core.c (ffffffff812dd2ed)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff81313a8d)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff813171f6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff81323471)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff81327377)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/list_lru.c (ffffffff81334925)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff813876e6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:enqueue_huge_page
```
```
In mm/ksm.c (ffffffff813a2f34)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff813abef1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/huge_memory.c (ffffffff813bfed7)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff813d867a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff814135f2)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff8141ffb0)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff8142aae3)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8142d797)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/pnode.c (ffffffff814363c2)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff81450211)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff8145def6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/proc/kcore.c (ffffffff814aeba0)
Location: include/linux/list.h:215
Inline: True
```
```
In fs/configfs/dir.c (ffffffff814ba9d1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/mballoc.c (ffffffff814fad1a)
Location: include/linux/list.h:215
Inline: True
```
```
In fs/fat/cache.c (ffffffff81556d8a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff81570b3c)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
```
```
In fs/fuse/dev.c (ffffffff815747f1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff815d6337)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In crypto/algapi.c (ffffffff8164ceb1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff816b39f6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/iommu/io-pgfault.c (ffffffff81971583)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81979bc0)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff81996484)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff8199d7e8)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff819a78f9)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819df15c)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/scsi/scsi_error.c (ffffffff819fcc3a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69061)
Location: include/linux/list.h:215
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac51db)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae23c6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b0903e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81ef5081)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81c52985)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81ca05ba)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/ipv4/route.c (ffffffff81cd1036)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/unix/garbage.c (ffffffff81d83605)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/route.c (ffffffff81da95ce)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35893)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810905f8)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810949d3)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b136a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff8114d31e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff8115898b)
Location: include/linux/list.h:215
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff8118c43e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/clockevents.c (ffffffff811ed873)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/audit_tree.c (ffffffff8123344a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff812363c6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81258994)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81300ec6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
```
In kernel/events/core.c (ffffffff8134529d)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff813811bd)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8138c2f6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff81397cc1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff8139bc07)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/list_lru.c (ffffffff813ab635)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/hugetlb.c (ffffffff81405b13)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:enqueue_hugetlb_folio
```
```
In mm/ksm.c (ffffffff81422bb4)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff814295d0)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/huge_memory.c (ffffffff814421c7)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff8145e345)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff8149e9da)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff814ac4e0)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff814b9273)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff814bb117)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/pnode.c (ffffffff814c43e2)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff814debc1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff814ed951)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/proc/kcore.c (ffffffff8154522e)
Location: include/linux/list.h:215
Inline: True
```
```
In fs/configfs/dir.c (ffffffff815522a1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/ext4/mballoc.c (ffffffff815954c6)
Location: include/linux/list.h:215
Inline: True
```
```
In fs/fat/cache.c (ffffffff815f892e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff81615bec)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In fs/fuse/dev.c (ffffffff8161a5f5)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff81684617)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In crypto/algapi.c (ffffffff81705c31)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff81773256)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/iommu/io-pgfault.c (ffffffff81adc6c3)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81ae6911)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff81b07155)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0ef18)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1a969)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5b07c)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7ae1a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfba41)
Location: include/linux/list.h:215
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c4f24b)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6ddc6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c98d3a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81d02e6d)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81e07f35)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81e5c59c)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/ipv4/route.c (ffffffff81e912ad)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/unix/garbage.c (ffffffff81f50cd0)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/route.c (ffffffff81f78d51)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
```
In net/mptcp/pm_userspace.c (ffffffff8200e553)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093508)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097973)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b431a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/workqueue.c (ffffffff8111c152)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_dying
  - kernel/workqueue.c:set_worker_dying
```
```
In kernel/sched/fair.c (ffffffff8115ca6e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff81168d1b)
Location: include/linux/list.h:215
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff8119db5e)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/rcu/tree.c (ffffffff811cbbe9)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/time/clockevents.c (ffffffff81201fa3)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/audit_tree.c (ffffffff8124a103)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff8124d1e6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8126fd64)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8132fa27)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
```
In kernel/events/core.c (ffffffff81376332)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff813b256f)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff813be927)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff813cac41)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff813cebe7)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/list_lru.c (ffffffff813df9d5)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/zswap.c (ffffffff814369ae)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff81439051)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/hugetlb.c:enqueue_hugetlb_folio
```
```
In mm/ksm.c (ffffffff81457bc4)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff8145e94a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff8146af72)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_sync
```
```
In mm/huge_memory.c (ffffffff81477ad7)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff8149402c)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff814d3cfa)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff814e12b0)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff814ecde2)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff814f0235)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/pnode.c (ffffffff814f97d2)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff81515402)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81524961)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/proc/kcore.c (ffffffff8157ce0e)
Location: include/linux/list.h:215
Inline: True
```
```
In fs/configfs/dir.c (ffffffff81589fed)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff816308ae)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff8164dc7c)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In fs/fuse/dev.c (ffffffff816528f1)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff816bc987)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In crypto/algapi.c (ffffffff81740131)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff817b2bfb)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In io_uring/kbuf.c (ffffffff817dffd8)
Location: include/linux/list.h:215
Inline: True
```
```
In drivers/iommu/io-pgfault.c (ffffffff81b2a92f)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81b34d98)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff81b551a5)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5cfc8)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff81b69579)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bae110)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/scsi/scsi_error.c (ffffffff81bceb2a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c60fd1)
Location: include/linux/list.h:215
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb67eb)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd53d6)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d000d0)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81d6bebd)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81e7a855)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81eb912c)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/ipv4/route.c (ffffffff81eefa3a)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/unix/garbage.c (ffffffff81fb0631)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/route.c (ffffffff81fd8f49)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
```
In net/mptcp/pm_userspace.c (ffffffff8208afe3)
Location: include/linux/list.h:215
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a978)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109eee3)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bb77a)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/workqueue.c (ffffffff81125c52)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/workqueue.c:set_worker_dying
  - kernel/workqueue.c:set_worker_dying
```
```
In kernel/sched/fair.c (ffffffff81167ece)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff81175fcb)
Location: include/linux/list.h:296
Inline: True
```
```
In kernel/power/wakelock.c (ffffffff811accce)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/rcu/tree.c (ffffffff811dd8e9)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/time/clockevents.c (ffffffff81218443)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/audit_tree.c (ffffffff81264013)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff812670e6)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8128a214)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81353f47)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
```
```
In kernel/events/core.c (ffffffff8139f632)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff813dbb0e)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff813e95ee)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff813f5c21)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff813f9747)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/list_lru.c (ffffffff8140a0e5)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/slub.c (ffffffff8145d01a)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/hugetlb.c (ffffffff81474798)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_and_add_allocated_folios
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/hugetlb_vmemmap.c (ffffffff8148138e)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore_folios
```
```
In mm/ksm.c (ffffffff81492694)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/migrate.c (ffffffff81499f5a)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_sync
```
```
In mm/huge_memory.c (ffffffff814a7257)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff814c38b5)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/namespace.c (ffffffff81515380)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/fs-writeback.c (ffffffff81524945)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/pnode.c (ffffffff8152e032)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff815497c2)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff8155b451)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/proc/kcore.c (ffffffff815b572e)
Location: include/linux/list.h:296
Inline: True
```
```
In fs/configfs/dir.c (ffffffff815c2cc0)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff81669d5e)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff816871dc)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In fs/fuse/dev.c (ffffffff8168bf01)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/selinux/ss/sidtab.c (ffffffff816f94b7)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
```
```
In crypto/algapi.c (ffffffff81780fb1)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/blk-flush.c (ffffffff817b6f3b)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/mq-deadline.c (ffffffff817f6a2b)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In io_uring/kbuf.c (ffffffff8182447b)
Location: include/linux/list.h:296
Inline: True
```
```
In drivers/iommu/io-pgfault.c (ffffffff81b81b8b)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81b8c7c8)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/power/main.c (ffffffff81bad765)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb0878)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbd239)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c02480)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/scsi/scsi_error.c (ffffffff81c2374a)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d179a1)
Location: include/linux/list.h:296
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6b53b)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8a3b6)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5b87)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81e22f8d)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81f3a9f5)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/sched/cls_api.c (ffffffff81f7c27f)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/ipv4/route.c (ffffffff81fb3b8a)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/unix/garbage.c (ffffffff8207dca0)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/route.c (ffffffff820a68d9)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
```
In net/mptcp/pm_userspace.c (ffffffff82160c37)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
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
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e9eb8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
  - virt/kvm/arm/vgic/vgic-its.c:__vgic_its_check_cache
```
```
In kernel/sched/fair.c (ffff8000101461e4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffff80001014de54)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/power/wakelock.c (ffff800010171af4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffff8000101f57ec)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027cff8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffff80001029cd14)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffff8000102cb450)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffff8000102d1bfc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffff8000102e2b54)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffff8000102e58fc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffff8000102ee9b4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffff80001031553c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffff80001033053c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffff800010341dec)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffff80001034bf1c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffff800010359b64)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffff80001036d9c8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffff8000103a83f0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffff8000103b66dc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffff8000103c1728)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffff8000103c3510)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffff8000103cc3b4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffff8000103ea790)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffff8000103f76d8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffff80001044dab8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffff80001045bb3c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffff8000104e32fc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffff8000104fd464)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffff8000105051a4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffff8000105b8f44)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffff800010618fd4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080b08c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
```
```
In drivers/base/core.c (ffff8000108e6a30)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffff800011496d58)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffff80001090295c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffff80001090b580)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffff8000109134e8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095a734)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffff80001095f490)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffff80001097312c)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a0293c)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4c7e0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6742c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c764)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffff800010af5ebc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffff800010c07bbc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffff800010cf4cf8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/arm/probes/kprobes/opt-arm.c (c0328730)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/opt-arm.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (c0393f10)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (c039c9c4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/power/wakelock.c (c03c448c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (c0434b20)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (c04378e8)
Location: include/linux/list.h:199
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (c04ae9f4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (c04cc330)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (c04f5488)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/percpu.c (c0506dcc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (c0509bb0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (c0512788)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (c052fdec)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/ksm.c (c0547bf0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (c054fd3c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/dcache.c (c0589170)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (c05949c8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (c059ce0c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (c05a0ef0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (c05a7fa0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (c05c1b54)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (c05cbac8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/configfs/dir.c (c061bf64)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (c06a2400)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (c06baa6c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (c06c15c4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (c0767a60)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (c07c3b78)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/dma/ipu/ipu_idmac.c (c0927534)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
```
```
In drivers/base/core.c (c09d50f4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (c1597ba8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (c09eccd8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (c09f4b7c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (c09f89bc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/scsi/scsi_error.c (c0a47ad0)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c0adf80c)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1dbb0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (c0b39c64)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (c0b5f3b0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (c0bd671c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In sound/core/pcm_native.c (c0c96118)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:relink_to_local
```
```
In sound/soc/soc-dapm.c (c0ca8130)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:dapm_seq_run
```
```
In net/core/flow_offload.c (c0d20a9c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (c0dfb960)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/powerpc/kernel/optprobes.c (c000000000057ecc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/powerpc/kernel/optprobes.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (c0000000001972f4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (c0000000001a0998)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/power/wakelock.c (c0000000001ca2dc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (c0000000002699bc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (c00000000026df54)
Location: include/linux/list.h:199
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (c000000000326a78)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (c00000000034d570)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (c000000000388440)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (c0000000003915c0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (c0000000003a3658)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (c0000000003a79cc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (c0000000003b2b98)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (c0000000003e73dc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (c000000000408ff4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (c00000000041f580)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (c00000000042b764)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (c000000000443260)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (c00000000045db3c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (c0000000004a1c48)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (c0000000004b2e38)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (c0000000004beb4c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (c0000000004c1280)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/pnode.c (c0000000004cda80)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (c0000000004f1994)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (c000000000501148)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/proc/kcore.c (c000000000565284)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (c00000000057589c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (c000000000620478)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (c0000000006407dc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (c00000000064a584)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (c00000000073e8c4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (c0000000007b85c8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (c00000000097c9c0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (c0000000013aa324)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (c0000000009a0d9c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/regmap/regmap.c (c0000000009b4188)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0a8dc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (c000000000a11cf8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (c000000000a2c834)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aab290)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b126fc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b386d0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68ef8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (c000000000be2564)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/core/flow_offload.c (c000000000cf310c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (c000000000e1ad6c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In kernel/sched/fair.c (ffffffe0000f11fe)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffe0000f6b18)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/audit_tree.c (ffffffe000168948)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b455c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffe0001cb54c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffe0001ea2c8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/percpu.c (ffffffe0001f9d1e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/slab_common.c (ffffffe0001fc2fc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffe0002029a6)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffe00021becc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffe00022d84c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/ksm.c (ffffffe000236144)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffe00023d2ce)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a65c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffe00026db2a)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffe000279316)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffe000281a64)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffe0002821c0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffe00028992c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffe00029ef1c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffe0002a8158)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffe0002e2322)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffe0002ec010)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffe000356abe)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffe00036bad6)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffe00036fb8e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffe0003ff5c2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffe00044ee08)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffe00057b366)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffe000030960)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/clock_ops.c (ffffffe00059102e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffe000594454)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c9070)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffe0005cd1ae)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc026)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062f0d4)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668852)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000681494)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a15b8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffe0006e8562)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/core/flow_offload.c (ffffffe000785cec)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffffffe0008409ce)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff8107312a)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810e1b5e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810e79da)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff81109c32)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff81178a0f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff8117a819)
Location: include/linux/list.h:199
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811f04be)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff8120aefb)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff81232b28)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8123804f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff81244b3b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff81247b02)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff8124f665)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffff81276229)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff8128b059)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8129aa6e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff812a2788)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812b197c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812c2672)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff812f1622)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff812fb890)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff813054d1)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff813057d0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8130df72)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff81326737)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81331af4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff81378423)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff81382488)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813fcce4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff81414483)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff81418899)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff814b801b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff8150ca69)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff816c1955)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff828efbf3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff816d82b4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff816de73f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff816e4aff)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170d710)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff817124d3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff817245fa)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178fa08)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cacbf)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e3f32)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/md/md.c (ffffffff8184755e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81903660)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffffffff819d3da6)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff810631aa)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810d0c3e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810d65dd)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/power/wakelock.c (ffffffff810fab12)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff8116bbaf)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff8116d9b9)
Location: include/linux/list.h:199
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811e320e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff811fdcd5)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff81225bc8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8122b08f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff8123784b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff8123aaac)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff81242605)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffff81268179)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff8127ce89)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8128c62e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff81294258)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812a2d4c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812b36c2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff812e2252)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff812ec4b0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff812f60f1)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff812f63f0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812feb82)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff813172d7)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff813226c2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff81368ef3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff81372f18)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813ed764)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff81404f03)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff81409319)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff814a8a3b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff814fce99)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff8169cc05)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff828e707f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff816b2914)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff816b8d9f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff816bf13f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e1190)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff816e5f53)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff816fda2a)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817787d8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca8be)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff8180ebbe)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff818bd490)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffffffff81990b66)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff810730da)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810ddede)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810e380d)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/power/wakelock.c (ffffffff81107b22)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff811767df)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff811785e9)
Location: include/linux/list.h:199
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811ee28e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff81208c9b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff812308c8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff81235def)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff812428db)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff812458a2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff8124d405)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffff81273fc9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81288e69)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8129887e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff812a0598)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812af78c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812c0482)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff812ef432)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff812f9680)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff813032c1)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff813035c0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8130bd62)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff81324207)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff8132f5c4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff81375ef3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff8137ff58)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff813fa064)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff81411803)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff81414a39)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff814b40ab)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff81508af9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff816efe25)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff82903745)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff81705bf4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff8170c0cf)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff81711c8f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174c4e0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff817512a3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff817633ca)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bfda8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8180775f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818209d2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff818421ee)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff81896b8e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81954690)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffffffff81a3e826)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/kprobes/opt.c (ffffffff8107513a)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
```
In kernel/sched/fair.c (ffffffff810e99ce)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810f01ea)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/power/wakelock.c (ffffffff81112ed2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/audit_tree.c (ffffffff811840b4)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_remove_tree_rule
```
```
In kernel/kprobes.c (ffffffff81185eb9)
Location: include/linux/list.h:199
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc75e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
```
In kernel/events/core.c (ffffffff81217a22)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/vmscan.c (ffffffff8123fd18)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff812460cb)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff81251dcb)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffff812547a9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff8125cdc5)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate_move
```
```
In mm/page_alloc.c (ffffffff81283ac9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81298c01)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812a8603)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/slub.c (ffffffff812b06d8)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812bfacc)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0f12)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In fs/dcache.c (ffffffff81300742)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/namespace.c (ffffffff8130a9a0)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:umount_tree
```
```
In fs/libfs.c (ffffffff8131434e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff81314930)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8131d592)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/notify/mark.c (ffffffff81335f57)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
```
```
In fs/userfaultfd.c (ffffffff81341713)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/proc/kcore.c (ffffffff813899a3)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/configfs/dir.c (ffffffff81393824)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/cache.c (ffffffff8140fc9c)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/ecryptfs/messaging.c (ffffffff81427473)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_msg_ctx_alloc_to_free
```
```
In fs/fuse/dev.c (ffffffff8142b2a9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In crypto/algapi.c (ffffffff814ccb2b)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
  - crypto/algapi.c:crypto_remove_spawns
```
```
In block/mq-deadline.c (ffffffff815221f9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_merged_requests
```
```
In drivers/base/core.c (ffffffff8170a665)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
```
```
In drivers/base/platform.c (ffffffff82909484)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_driver_register
```
```
In drivers/base/power/main.c (ffffffff8172059f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_pm_move_after
```
```
In drivers/base/power/clock_ops.c (ffffffff81726a5f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
```
```
In drivers/base/regmap/regmap.c (ffffffff8172cdf9)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81767960)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
```
In drivers/nvdimm/label.c (ffffffff8176c723)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff8177ea2a)
Location: include/linux/list.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817da050)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8182186f)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183aae2)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c61e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
```
In drivers/md/md.c (ffffffff818b2b6e)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - drivers/md/md.c:autorun_devices
```
```
In net/core/flow_offload.c (ffffffff81976340)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/unix/garbage.c (ffffffff81a4a3ab)
Location: include/linux/list.h:199
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
</details>
</li>
</ul>

## Differences
