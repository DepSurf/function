# Function: <code>kvmalloc_node</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd7a0)
Location: mm/util.c:372
Inline: False
Direct callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - ipc/msg.c:newque
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff811dd7a0-ffffffff811dd820: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3220)
Location: mm/util.c:372
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff811f3220-ffffffff811f32a0: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214460)
Location: mm/util.c:397
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - lib/bucket_locks.c:alloc_bucket_spinlocks
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81214460-ffffffff812144d4: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227330)
Location: mm/util.c:390
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffff81227330-ffffffff812273a4: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237010)
Location: mm/util.c:433
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffff81237010-ffffffff81237095: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812451e0)
Location: mm/util.c:538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffff812451e0-ffffffff81245265: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272df0)
Location: mm/util.c:548
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_list_lru_node
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:deflate_decompress
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/net/tun.c:tun_chr_open
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
  - net/core/page_pool.c:page_pool_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_buff_pool.c:xp_create
  - net/xdp/xsk_buff_pool.c:xp_create
```
**Symbols:**

```
ffffffff81272df0-ffffffff81272e6f: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d4d0)
Location: mm/util.c:561
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - mm/util.c:vmemdup_user
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_list_lru_node
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:deflate_decompress
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/net/tun.c:tun_chr_open
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
  - net/core/page_pool.c:page_pool_init
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff8127d4d0-ffffffff8127d54f: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282660)
Location: mm/util.c:561
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/util.c:vmemdup_user
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_rsrc_data_alloc
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/net/tun.c:tun_chr_open
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff81282660-ffffffff812826dd: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0760)
Location: mm/util.c:561
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/util.c:vmemdup_user
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_files_register
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/net/tun.c:tun_chr_open
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff812c0760-ffffffff812c07f5: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d240)
Location: mm/util.c:591
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:io_sqe_buffer_register
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_sqe_files_register
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - lib/stackdepot.c:stack_depot_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/net/tun.c:tun_chr_open
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/input/evdev.c:evdev_open
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_init
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff8131d240-ffffffff8131d340: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81390ba0)
Location: mm/util.c:559
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/match.c:unpack_table
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:kvmemdup
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/filetable.c:io_alloc_file_tables
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_pin_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - lib/stackdepot.c:stack_depot_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/net/tun.c:tun_chr_open
  - drivers/input/evdev.c:evdev_open
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_init
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff81390ba0-ffffffff81390c9c: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c34b0)
Location: mm/util.c:582
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/printk/printk.c:devkmsg_open
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/module/decompress.c:module_extend_max_pages
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
  - mm/util.c:kvmemdup
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/verity/open.c:fsverity_create_info
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/filetable.c:io_alloc_file_tables
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - lib/stackdepot.c:stack_depot_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/net/tun.c:tun_chr_open
  - drivers/input/evdev.c:evdev_open
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_init
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff813c34b0-ffffffff813c35ac: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813edfd0)
Location: mm/util.c:595
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - kernel/resource.c:walk_system_ram_res_rev
  - kernel/groups.c:__do_sys_setgroups
  - kernel/printk/printk.c:devkmsg_open
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/module/decompress.c:module_zstd_decompress
  - kernel/module/decompress.c:module_extend_max_pages
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_start
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
  - mm/util.c:kvmemdup
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/namespace.c:__do_sys_statmount
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/verity/open.c:fsverity_create_info
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:decompress_record
  - fs/pstore/platform.c:pstore_register
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - security/apparmor/policy_compat.c:aa_compat_map_policy
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_fperms
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - crypto/jitterentropy-kcapi.c:jent_kvzalloc
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/filetable.c:io_alloc_file_tables
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - lib/stackdepot.c:stack_depot_init
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:iterate_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_property.c:drm_property_create_blob
  - drivers/net/tun.c:tun_chr_open
  - drivers/input/evdev.c:evdev_open
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_init
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff813edfd0-ffffffff813ee0cc: kvmalloc_node (STB_GLOBAL)
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
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8178)
Location: mm/util.c:538
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:kvm_create_vm
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffff8000102d8178-ffff8000102d8224: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff7c4)
Location: mm/util.c:538
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - sound/core/info.c:snd_info_text_entry_write
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
c04ff7c4-c04ff840: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397e10)
Location: mm/util.c:538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
c000000000397e10-c000000000397f1c: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2aca)
Location: mm/util.c:538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffe0001f2aca-ffffffe0001f2b4a: kvmalloc_node (STB_GLOBAL)
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
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d830)
Location: mm/util.c:538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffff8123d830-ffffffff8123d8b5: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230830)
Location: mm/util.c:538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffff81230830-ffffffff812308b5: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b5d0)
Location: mm/util.c:538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/netfilter/nf_conntrack_core.c:nf_ct_alloc_hashtable
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffff8123b5d0-ffffffff8123b655: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kvmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124ace0)
Location: mm/util.c:538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/trace/trace.c:set_tracer_flag
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:init_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/frame_vector.c:frame_vector_create
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/selinux/ss/avtab.c:avtab_alloc
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
  - crypto/lzo.c:lzo_init
  - crypto/lzo-rle.c:lzorle_init
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
  - drivers/input/evdev.c:evdev_open
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-stats.c:dm_kvzalloc
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netfilter/core.c:allocate_hook_entries_size
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
**Symbols:**

```
ffffffff8124ace0-ffffffff8124ad65: kvmalloc_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
