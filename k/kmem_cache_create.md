# Function: <code>kmem_cache_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2ea0)
Location: mm/slab_common.c:384
Inline: False
Direct callers:
  - kernel/fork.c:fork_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:init_workqueues
  - kernel/pid.c:pidmap_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mb_cache_create
  - fs/proc/inode.c:proc_init_inodecache
  - fs/kernfs/mount.c:kernfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/crypto.c:ext4_init_crypto
  - fs/ext4/crypto.c:ext4_init_crypto
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:__bioset_create
  - block/bio.c:init_bio
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bsg.c:bsg_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/idr.c:idr_init_cache
  - lib/radix-tree.c:radix_tree_init
  - lib/btree.c:btree_module_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/flow.c:flow_cache_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff811b2ea0-ffffffff811b3062: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc910)
Location: mm/slab_common.c:389
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:init_workqueues
  - kernel/pid.c:pidmap_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/proc/inode.c:proc_init_inodecache
  - fs/kernfs/mount.c:kernfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:__bioset_create
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bsg.c:bsg_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/idr.c:idr_init_cache
  - lib/radix-tree.c:radix_tree_init
  - lib/btree.c:btree_module_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/flow.c:flow_cache_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff811cc910-ffffffff811ccac4: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc9e0)
Location: mm/slab_common.c:389
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pidmap_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/proc/inode.c:proc_init_inodecache
  - fs/kernfs/mount.c:kernfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:__bioset_create
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bsg.c:bsg_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/idr.c:idr_init_cache
  - lib/radix-tree.c:radix_tree_init
  - lib/btree.c:btree_module_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/flow.c:flow_cache_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff811dc9e0-ffffffff811dcbbe: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e72e0)
Location: mm/slab_common.c:424
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pidmap_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/proc/inode.c:proc_init_inodecache
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_create
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bsg.c:bsg_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/flow.c:flow_cache_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff811e72e0-ffffffff811e74c9: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, size_t size, size_t align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fd520)
Location: mm/slab_common.c:433
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/proc/inode.c:proc_init_inodecache
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:security_init
  - security/security.c:security_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_create
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bsg.c:bsg_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff811fd520-ffffffff811fd702: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121ea70)
Location: mm/slab_common.c:518
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bsg.c:bsg_init
  - block/cfq-iosched.c:cfq_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff8121ea70-ffffffff8121ea88: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81231a50)
Location: mm/slab_common.c:545
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81231a50-ffffffff81231a68: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81241e90)
Location: mm/slab_common.c:560
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81241e90-ffffffff81241ea8: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81250320)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81250320-ffffffff81250338: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127e960)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_slab_init
  - mm/ksm.c:ksm_slab_init
  - mm/ksm.c:ksm_slab_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init_caches
  - fs/jbd2/journal.c:journal_init_caches
  - fs/jbd2/journal.c:journal_init_caches
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init_kmem_caches
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bio_find_or_create_slab
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - lib/radix-tree.c:radix_tree_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_init_mempool
  - drivers/iommu/intel/iommu.c:iommu_init_mempool
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff8127e960-ffffffff8127e978: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81287ec0)
Location: mm/slab_common.c:407
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_slab_init
  - mm/ksm.c:ksm_slab_init
  - mm/ksm.c:ksm_slab_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/fast_commit.c:ext4_fc_init_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init_caches
  - fs/jbd2/journal.c:journal_init_caches
  - fs/jbd2/journal.c:journal_init_caches
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init_kmem_caches
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bio_find_or_create_slab
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - lib/radix-tree.c:radix_tree_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_init_mempool
  - drivers/iommu/intel/iommu.c:iommu_init_mempool
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81287ec0-ffffffff81287ed8: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128d180)
Location: mm/slab_common.c:419
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/fast_commit.c:ext4_fc_init_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init_caches
  - fs/jbd2/journal.c:journal_init_caches
  - fs/jbd2/journal.c:journal_init_caches
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - lib/radix-tree.c:radix_tree_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff8128d180-ffffffff8128d198: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812ccfa0)
Location: mm/slab_common.c:419
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/fast_commit.c:ext4_fc_init_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - lib/radix-tree.c:radix_tree_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff812ccfa0-ffffffff812ccfb8: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132b800)
Location: mm/slab_common.c:415
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/fast_commit.c:ext4_fc_init_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - io_uring/io_uring.c:io_uring_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - lib/radix-tree.c:radix_tree_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff8132b800-ffffffff8132b82a: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a0cb0)
Location: mm/slab_common.c:392
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/fast_commit.c:ext4_fc_init_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/apparmor/lsm.c:apparmor_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - io_uring/io_uring.c:io_uring_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - lib/maple_tree.c:maple_tree_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff813a0cb0-ffffffff813a0cda: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d3f30)
Location: mm/slab_common.c:392
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_setup
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/fast_commit.c:ext4_fc_init_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/apparmor/lsm.c:apparmor_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - io_uring/io_uring.c:io_uring_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - lib/maple_tree.c:maple_tree_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff813d3f30-ffffffff813d3f5a: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813febd0)
Location: mm/slab_common.c:387
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_setup
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/backing-file.c:backing_aio_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/fast_commit.c:ext4_fc_init_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/tracefs/inode.c:tracefs_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/apparmor/lsm.c:apparmor_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bdev.c:bdev_cache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - block/blk-crypto.c:bio_crypt_ctx_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - io_uring/io_uring.c:io_uring_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - net/mptcp/subflow.c:mptcp_subflow_init
  - lib/maple_tree.c:maple_tree_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff813febd0-ffffffff813febfa: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e7288)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffff8000102e7288-ffff8000102e72ec: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050b448)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/omap-iommu.c:omap_iommu_init
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
c050b448-c050b480: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a8ed0)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - arch/powerpc/mm/init-common.c:pgtable_cache_add
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
  - arch/powerpc/platforms/pseries/setup.c:__machine_initcall_pseries_alloc_dispatch_log_kmem_cache
  - arch/powerpc/perf/hv-24x7.c:hv_24x7_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
c0000000003a8ed0-c0000000003a8ef0: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fcedc)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffe0001fcedc-ffffffe0001fcf2a: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81248970)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81248970-ffffffff81248988: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123b920)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff8123b920-ffffffff8123b938: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246710)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/virtio_scsi.c:init
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81246710-ffffffff81246728: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81255f20)
Location: mm/slab_common.c:561
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:proc_caches_init
  - kernel/user.c:uid_cache_init
  - kernel/signal.c:signals_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:pid_idr_init
  - kernel/nsproxy.c:nsproxy_cache_init
  - kernel/cred.c:cred_init
  - kernel/sched/core.c:sched_init
  - kernel/time/posix-timers.c:init_posix_timers
  - kernel/user_namespace.c:user_namespaces_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_init
  - kernel/audit_tree.c:audit_tree_init
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_init_early
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - mm/shmem.c:shmem_init
  - mm/rmap.c:anon_vma_init
  - mm/rmap.c:anon_vma_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:init_zswap
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_init
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/file_table.c:files_init
  - fs/fcntl.c:fcntl_init
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/seq_file.c:seq_file_init
  - fs/buffer.c:buffer_init
  - fs/block_dev.c:bdev_cache_init
  - fs/direct-io.c:dio_init
  - fs/notify/fsnotify.c:fsnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/eventpoll.c:eventpoll_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/aio.c:aio_setup
  - fs/io_uring.c:io_uring_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/locks.c:filelock_init
  - fs/locks.c:filelock_init
  - fs/mbcache.c:mbcache_init
  - fs/quota/dquot.c:dquot_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/kernfs/mount.c:kernfs_init
  - fs/kernfs/mount.c:kernfs_init
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_init_system_zone
  - fs/ext4/extents_status.c:ext4_init_pending
  - fs/ext4/extents_status.c:ext4_init_es
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/jbd2/transaction.c:jbd2_journal_init_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_record_cache
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_create_slab
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_init
  - fs/fat/inode.c:init_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/keys/key.c:key_init
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/avc.c:avc_init
  - security/selinux/ss/ebitmap.c:ebitmap_cache_init
  - security/selinux/ss/hashtab.c:hashtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/selinux/ss/avtab.c:avtab_cache_init
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_init
  - security/integrity/iint.c:integrity_iintcache_init
  - block/bio.c:init_bio
  - block/bio.c:bioset_init
  - block/elevator.c:elv_register
  - block/blk-core.c:blk_dev_init
  - block/blk-ioc.c:blk_ioc_init
  - block/bio-integrity.c:bio_integrity_init
  - lib/btree.c:btree_module_init
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_create_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_init
  - drivers/md/dm-io.c:dm_io_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
  - net/socket.c:sock_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inetpeer.c:inet_initpeers
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/fib_trie.c:fib_trie_init
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_state.c:xfrm_state_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81255f20-ffffffff81255f38: kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>slab_flags_t flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>size_t size</code> ➡️ <code>unsigned int size</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t align</code> ➡️ <code>unsigned int align</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
