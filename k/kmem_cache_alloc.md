# Function: <code>kmem_cache_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eafb0)
Location: mm/slub.c:2575
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slab_common.c:create_kmalloc_cache
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_prepare
  - mm/rmap.c:anon_vma_prepare
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_enter
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/huge_memory.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:get_empty_filp
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:SyS_getcwd
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:do_io_submit
  - fs/locks.c:locks_alloc_lock
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_alloc_inode
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/dcookies.c:get_dcookie
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/crypto.c:ext4_get_crypto_ctx
  - fs/ext4/crypto.c:ext4_init_crypto
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/smack/smack_lsm.c:new_inode_smack
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/bsg.c:bsg_write
  - lib/idr.c:idr_preload
  - lib/radix-tree.c:__radix_tree_preload
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/xfrm/xfrm_input.c:secpath_dup
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff811eafb0-ffffffff811eb192: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120a850)
Location: mm/slub.c:2704
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_prepare
  - mm/rmap.c:anon_vma_prepare
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:get_empty_filp
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_setup
  - fs/crypto/crypto.c:fscrypt_get_ctx
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_alloc_inode
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/dcookies.c:get_dcookie
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/smack/smack_lsm.c:new_inode_smack
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/bsg.c:bsg_write
  - lib/idr.c:idr_preload
  - lib/radix-tree.c:__radix_tree_preload
  - lib/radix-tree.c:radix_tree_node_alloc
  - lib/radix-tree.c:radix_tree_node_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_input.c:secpath_dup
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
**Symbols:**

```
ffffffff8120a850-ffffffff8120a9e1: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121c8a0)
Location: mm/slub.c:2726
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:get_empty_filp
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/aio.c:do_io_submit
  - fs/aio.c:ioctx_alloc
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/crypto.c:fscrypt_get_ctx
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_alloc_inode
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/dcookies.c:get_dcookie
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/smack/smack_lsm.c:new_inode_smack
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/bsg.c:bsg_write
  - lib/idr.c:idr_preload
  - lib/radix-tree.c:__radix_tree_preload
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi.c:scsi_host_alloc_command
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_input.c:secpath_dup
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
**Symbols:**

```
ffffffff8121c8a0-ffffffff8121ca31: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81228100)
Location: mm/slub.c:2723
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:get_empty_filp
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:do_io_submit
  - fs/aio.c:ioctx_alloc
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_alloc_inode
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/bsg.c:bsg_write
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/scsi/scsi_lib.c:scsi_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/flow.c:flow_cache_lookup
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_input.c:secpath_dup
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
```
**Symbols:**

```
ffffffff81228100-ffffffff8122829e: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81243ee0)
Location: mm/slub.c:2736
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:get_empty_filp
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:do_io_submit
  - fs/aio.c:ioctx_alloc
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_alloc_inode
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/security.c:lsm_early_inode
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/bsg.c:bsg_write
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_input.c:secpath_dup
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
```
**Symbols:**

```
ffffffff81243ee0-ffffffff8124408f: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81266600)
Location: mm/slub.c:2719
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:get_empty_filp
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:new_inode_smack
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/bsg.c:bsg_write
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_input.c:secpath_dup
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
```
**Symbols:**

```
ffffffff81266600-ffffffff812667d5: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127b330)
Location: mm/slub.c:2769
Inline: False
Direct callers:
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
```
**Symbols:**

```
ffffffff8127b330-ffffffff8127b4f3: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81296cd0)
Location: mm/slub.c:2781
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffffffff81296cd0-ffffffff81296eea: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a6ad0)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffffffff812a6ad0-ffffffff812a6cea: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812db960)
Location: mm/slub.c:2835
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_tgid_alloc
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:__alloc_file
  - fs/exec.c:unshare_sighand
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd/iommu.c:__alloc_irq_table
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_node
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
**Symbols:**

```
ffffffff812db960-ffffffff812dbb83: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e7e70)
Location: mm/slub.c:2903
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_tgid_alloc
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/events/core.c:find_get_context
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:vmap_init_free_space
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:__alloc_file
  - fs/exec.c:unshare_sighand
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/amd/iommu.c:__alloc_irq_table
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:alloc_domain
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_node
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
**Symbols:**

```
ffffffff812e7e70-ffffffff812e8061: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f11c0)
Location: mm/slub.c:2925
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_tgid_alloc
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_define_field
  - kernel/events/core.c:find_get_context
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:__alloc_file
  - fs/exec.c:begin_new_exec
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_submit_sqes
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:alloc_domain
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_path_uevent
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/xdp.c:xdp_build_skb_from_frame
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
**Symbols:**

```
ffffffff812f11c0-ffffffff812f13f8: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81337b20)
Location: mm/slub.c:3224
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_tgid_alloc
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_define_field
  - kernel/events/core.c:find_get_context
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:__alloc_file
  - fs/exec.c:begin_new_exec
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_submit_sqes
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bdev.c:bdev_alloc_inode
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:alloc_domain
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_path_uevent
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/xdp.c:xdp_build_skb_from_frame
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
**Symbols:**

```
ffffffff81337b20-ffffffff81337dff: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ab660)
Location: mm/slub.c:3266
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_log_start
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_define_field
  - kernel/events/core.c:find_get_context
  - mm/mempool.c:mempool_alloc_slab
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:__alloc_file
  - fs/exec.c:begin_new_exec
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/inode.c:ext4_inode_attach_jinode
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - io_uring/io_uring.c:io_submit_sqes
  - lib/btree.c:btree_alloc
  - lib/radix-tree.c:__radix_tree_preload
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_path_uevent
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/xdp.c:xdp_build_skb_from_frame
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
**Symbols:**

```
ffffffff813ab660-ffffffff813ab970: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142a650)
Location: mm/slub.c:3474
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_log_start
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_define_field
  - kernel/events/core.c:find_get_pmu_context
  - mm/mempool.c:mempool_alloc_slab
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:__alloc_file
  - fs/exec.c:unshare_sighand
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/inode.c:ext4_inode_attach_jinode
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_request_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - io_uring/io_uring.c:__io_alloc_req_refill
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_path_uevent
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:slab_build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/xdp.c:xdp_build_skb_from_frame
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/maple_tree.c:mas_alloc_nodes
  - lib/maple_tree.c:mas_alloc_nodes
  - lib/radix-tree.c:__radix_tree_preload
```
**Symbols:**

```
ffffffff8142a650-ffffffff8142a9b0: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fad0)
Location: mm/slub.c:3492
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_log_start
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:event_define_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_field
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/events/core.c:find_get_pmu_context
  - mm/mempool.c:mempool_alloc_slab
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:new_kmalloc_cache
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
  - fs/exec.c:unshare_sighand
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/inode.c:ext4_inode_attach_jinode
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_request_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - io_uring/io_uring.c:__io_alloc_req_refill
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/amd/iommu.c:__alloc_irq_table
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_path_uevent
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:slab_build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/xdp.c:xdp_build_skb_from_frame
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/maple_tree.c:mas_alloc_nodes
  - lib/maple_tree.c:mas_alloc_nodes
  - lib/radix-tree.c:__radix_tree_preload
```
**Symbols:**

```
ffffffff8145fad0-ffffffff8145fe55: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145c650)
Location: mm/slub.c:3865
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/audit.c:audit_log_start
  - kernel/audit_tree.c:create_chunk
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:event_define_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_generic_fields
  - kernel/trace/trace_events.c:trace_define_field
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/events/core.c:find_get_pmu_context
  - mm/mempool.c:mempool_alloc_slab
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:new_kmalloc_cache
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_alloc
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:alloc_stable_node_chain
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:alloc_zspage
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
  - fs/exec.c:unshare_sighand
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__do_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/inode.c:ext4_inode_attach_jinode
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/page-io.c:ext4_alloc_io_end_vec
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_dir_open
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:parse_tag_3_packet
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/tracefs/inode.c:tracefs_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_populate
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_duplicate
  - security/selinux/ss/hashtab.c:__hashtab_insert
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/selinux/ss/avtab.c:avtab_insert_node
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/kbuf.c:io_refill_buffer_cache
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/amd/iommu.c:__alloc_irq_table
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/md/dm-uevent.c:dm_path_uevent
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:slab_build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dst.c:dst_alloc
  - net/core/xdp.c:xdp_build_skb_from_frame
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/maple_tree.c:mas_alloc_nodes
  - lib/maple_tree.c:mas_alloc_nodes
  - lib/radix-tree.c:__radix_tree_preload
```
**Symbols:**

```
ffffffff8145c650-ffffffff8145c98a: kmem_cache_alloc (STB_GLOBAL)
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
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010347df8)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_create
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffff800010347df8-ffff80001034805c: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054cf84)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:kmem_cache_open
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__se_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_setup
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/inode.c:__kernfs_iattrs
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - lib/btree.c:btree_alloc
  - drivers/iommu/omap-iommu.c:iopte_alloc
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:node_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/xarray.c:xas_alloc
```
**Symbols:**

```
c054cf84-c054d2bc: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004261b0)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
  - arch/powerpc/sysdev/xive/native.c:xive_native_alloc_vp_block
  - arch/powerpc/platforms/pseries/lpar.c:alloc_dtl_buffers
  - arch/powerpc/perf/hv-24x7.c:catalog_len_show
  - arch/powerpc/perf/hv-24x7.c:catalog_version_show
  - arch/powerpc/perf/hv-24x7.c:catalog_read
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:mm_init
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/memory.c:__pud_alloc
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__se_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:jbd2__journal_start
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:node_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
c0000000004261b0-c000000000426508: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023ac60)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:kmem_cache_open
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__se_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:__se_sys_io_setup
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:create_task_io_context
  - lib/btree.c:btree_alloc
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6_fib.c:node_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffffffe00023ac60-ffffffe00023aee4: kmem_cache_alloc (STB_GLOBAL)
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
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129f0b0)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffffffff8129f0b0-ffffffff8129f2ca: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81290bd0)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffffffff81290bd0-ffffffff81290dea: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129cec0)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_alloc
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffffffff8129cec0-ffffffff8129d0da: kmem_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kmem_cache_alloc(struct kmem_cache *s, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812adc60)
Location: mm/slub.c:2777
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/user.c:alloc_uid
  - kernel/signal.c:__sigqueue_alloc
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/sched/core.c:sched_create_group
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit_tree.c:tag_mount
  - kernel/delayacct.c:delayacct_init
  - kernel/taskstats.c:taskstats_exit
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:__trace_define_field
  - mm/mempool.c:mempool_alloc_slab
  - mm/shmem.c:shmem_alloc_inode
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/vmalloc.c:vmalloc_init
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:alloc_stable_node_chain
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/khugepaged.c:__khugepaged_enter
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - fs/file_table.c:__alloc_file
  - fs/exec.c:de_thread
  - fs/namei.c:getname_kernel
  - fs/fcntl.c:fasync_helper
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_vfsmnt
  - fs/seq_file.c:seq_open
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/fs_struct.c:copy_fs_struct
  - fs/buffer.c:alloc_buffer_head
  - fs/block_dev.c:bdev_alloc_inode
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
  - fs/crypto/crypto.c:fscrypt_initialize
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/verity/open.c:fsverity_create_info
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_get_lock_context
  - fs/mbcache.c:mb_cache_entry_create
  - fs/quota/dquot.c:dquot_alloc
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/generic.c:__proc_create
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/dcookies.c:get_dcookie
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/page-io.c:ext4_init_io_end
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke_table
  - fs/jbd2/revoke.c:insert_revoke_hash
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/keystore.c:ecryptfs_add_global_auth_tok
  - fs/ecryptfs/keystore.c:ecryptfs_add_keysig
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/security.c:security_file_alloc
  - security/security.c:security_inode_alloc
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/avc.c:avc_xperms_decision_alloc
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_import
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smackfs.c:smk_set_access
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/ima/ima_api.c:ima_d_path
  - block/bio.c:bvec_alloc
  - lib/btree.c:btree_alloc
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
  - drivers/acpi/acpica/psutils.c:acpi_os_acquire_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:alloc_domain
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/dax/super.c:dax_alloc_inode
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_prot_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/net_namespace.c:copy_net_ns
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inet_hashtables.c:inet_bind_bucket_create
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - lib/radix-tree.c:__radix_tree_preload
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
**Symbols:**

```
ffffffff812adc60-ffffffff812ade7e: kmem_cache_alloc (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
