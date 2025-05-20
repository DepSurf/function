# Function: <code>kvmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813750cc)
Location: security/apparmor/include/lib.h:68
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff813ab5be)
Location: security/apparmor/include/lib.h:68
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813bbfe6)
Location: security/apparmor/include/lib.h:68
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/apparmorfs.c (ffffffff813c238e)
Location: security/apparmor/include/lib.h:69
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813d34f1)
Location: security/apparmor/include/lib.h:69
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In mm/swap_slots.c (ffffffff811ec4d6)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/swap_state.c (ffffffff8120c506)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81210d48)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
```
In mm/frame_vector.c (ffffffff8124c379)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff81269f7b)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff81272eed)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff8127a9ab)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
```
```
In fs/xattr.c (ffffffff8127b5e4)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/ext4/mballoc.c (ffffffff8130f76d)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff81336add)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/msg.c (ffffffff81383c56)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813882ac)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff813891f8)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff8139222e)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/apparmor/match.c (ffffffff813de7af)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff813e65ee)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff81412136)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In lib/iov_iter.c (ffffffff81468aec)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff8146b847)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In drivers/acpi/apei/erst.c (ffffffff8153af33)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/char/agp/generic.c (ffffffff815b1534)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f882)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
```
```
In drivers/md/dm-ioctl.c (ffffffff81755c22)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff817cb653)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ece4)
Location: include/linux/mm.h:522
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fc3f)
Location: include/linux/mm.h:522
Inline: True
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
In kernel/bpf/cpumap.c (ffffffff811affe0)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/slab_common.c (ffffffff811fd49c)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/swap_slots.c (ffffffff81202856)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/list_lru.c (ffffffff81204113)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff81225c86)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8122829e)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
```
```
In mm/frame_vector.c (ffffffff8126c7bf)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff8128c81b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff8129581d)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff8129d41b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
```
```
In fs/xattr.c (ffffffff8129e084)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/ext4/mballoc.c (ffffffff8133464d)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff8135b094)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/msg.c (ffffffff813a80c6)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813ab4d3)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff813adf48)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff813b787e)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/apparmor/match.c (ffffffff8140513f)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d7d0)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff8143c8a6)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In lib/iov_iter.c (ffffffff81494d9c)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff81497b37)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In drivers/acpi/apei/erst.c (ffffffff8159da93)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/char/agp/generic.c (ffffffff81618124)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81698062)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
```
```
In drivers/net/tun.c (ffffffff81702492)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In drivers/md/dm-ioctl.c (ffffffff817c7ed1)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff81844eaa)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/sched/sch_api.c (ffffffff8187c368)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff8188bd50)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dc94)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff818befdf)
Location: include/linux/mm.h:539
Inline: True
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
In kernel/bpf/btf.c (ffffffff811c8a83)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/cpumap.c (ffffffff811ca7a9)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff81214705)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff8121e7a2)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff81224c48)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff8124829f)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8124db4e)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8124e7c5)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/frame_vector.c (ffffffff8129136f)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812b3c0a)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff812bb99d)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff812c3085)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/seq_file.c:traverse
```
```
In fs/xattr.c (ffffffff812c4744)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/binfmt_elf.c (ffffffff81305e21)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813097c5)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff8136290e)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813898f9)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In ipc/msg.c (ffffffff813d7b08)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813dbb1e)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff813de3fa)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff813e8467)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/apparmor/match.c (ffffffff8143622e)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ef21)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff8146f6e5)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In block/blk-zoned.c (ffffffff814b8103)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff814c5f5b)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff814ccacb)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/bucket_locks.c (ffffffff814cdd13)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - lib/bucket_locks.c:alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff815d56d3)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/char/agp/generic.c (ffffffff81651a2d)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816d41e1)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
```
```
In drivers/net/tun.c (ffffffff817411d0)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/md/dm-ioctl.c (ffffffff8180fa75)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff818910fb)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff818bd91a)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818cc3b7)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff818ceb85)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff818df844)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f18bc)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914be9)
Location: include/linux/mm.h:574
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811d01e4)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/btf.c (ffffffff811dc792)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
```
```
In kernel/bpf/cpumap.c (ffffffff811de0d5)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff812275e5)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff81231782)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff81237bb8)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff8125c870)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81261f6f)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81262ca5)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffff812940a2)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffff812a638f)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812c8e49)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff812d0b8d)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff812d7ff5)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff812d9944)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/binfmt_elf.c (ffffffff8131b5b1)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131efc5)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff8137ab1e)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813a24a0)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffff813dc9ce)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff813f2288)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff813f6198)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff813f8ab8)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff81402c67)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/apparmor/match.c (ffffffff81452e4e)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be37)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff8148d095)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In block/blk-zoned.c (ffffffff814cc061)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff814da76e)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff814e0fa2)
Location: include/linux/mm.h:602
Inline: True
```
```
In lib/bucket_locks.c (ffffffff814e25e3)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff815eee83)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/char/agp/generic.c (ffffffff8166f8cd)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5def)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff816fe7e0)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffff817652c7)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/md/dm-ioctl.c (ffffffff8183ba4c)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff818b172b)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff818e4c5d)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818f75d7)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff818f9e85)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff8190c3d4)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f49c)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194339b)
Location: include/linux/mm.h:602
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81a065af)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/bpf/verifier.c (ffffffff811e42ba)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811f1ebf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811f37a1)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff81237375)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff81241c12)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff81249137)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff81277a50)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8127ce5a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8127dbf5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffff812b02d2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffff812c1a8f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812e58b2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff812edbbf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff812f6505)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff812f7ec1)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff81331812)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff81342e86)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8134681b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff813a4cc2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813ccdc7)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffff81408502)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff8141e578)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81422550)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff81425018)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff8142f8a8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff81452fff)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814580fe)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffffffff81480800)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814895a3)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff814ba785)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff814baa05)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffffffff814fa5a3)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff81505d70)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff8150ce47)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffffffff8150e499)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a4fc2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/acpi/apei/erst.c (ffffffff81620c90)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff81676bd5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff816a544d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f547b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8170ab8e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172f5bb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8173897d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffff8179e74d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/md/dm-ioctl.c (ffffffff8187f62e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff818fe4cb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff819344ba)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8195363f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff81956cc5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff819595e5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff8196df64)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff81981dfb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a793f)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81a75f1d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (ffffffff81167da3)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811ab827)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811f0b1a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811fe5cf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff81200541)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff812452b5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff8125009a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff81257587)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff81287540)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8128c929)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8128d665)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffff812c1dc2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffff812d39bf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812f7379)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff812ff67f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff813080d5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff81309ac5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff81345452)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff8135b2c4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135eb29)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff813bdb2d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813e628c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffff81422782)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff814383c8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8143c326)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8143ed68)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff81449608)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff8146cd9f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81471e9e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffffffff8149a509)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814a344d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff814d3555)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff814d37d5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffffffff81518503)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff81523d50)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff8152ac97)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffffffff8152c3b9)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c5e92)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/acpi/apei/erst.c (ffffffff81642770)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff81699375)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff816c817d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff8171987b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8172ee8e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753a4b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8175c67d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffff817c21dd)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (ffffffff8185d38f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (ffffffff818b14ba)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff819307fb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff819670ea)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff819899ed)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff8198d165)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff8198fa85)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff819a4a14)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b864b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de9cf)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81aacddd)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (ffffffff81179ba1)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811c3c7b)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff812131bf)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/hashtab.c (ffffffff81218876)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/btf.c (ffffffff812246a8)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
```
```
In kernel/bpf/cpumap.c (ffffffff81227fd0)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/util.c (ffffffff812730a5)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff8127e6da)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff81285b3f)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_list_lru_node
```
```
In mm/swap_state.c (ffffffff812b9d8b)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812bf7b9)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff812c0115)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/frame_vector.c (ffffffff8130972f)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff8132feff)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff8133866f)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff813414b5)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff81344922)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff8137f478)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813a0133)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff813a33d7)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/ext4/mballoc.c (ffffffff81409aed)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff8141a54d)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8143338a)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff8143740e)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff81471939)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff81488468)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff8148ca5b)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8148f928)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff8149af48)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff814c156f)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814c7063)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff814ef59a)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:deflate_decompress
```
```
In security/apparmor/match.c (ffffffff814f2b26)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcc11)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff81532815)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff81532a95)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/keyslot-manager.c (ffffffff8158103f)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff81587334)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff8158e2a7)
Location: include/linux/mm.h:751
Inline: True
```
```
In lib/bucket_locks.c (ffffffff8158fd29)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff816efb9f)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff8174b735)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff8177d20d)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d59bb)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff817ece48)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8181252b)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8181be97)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848eeb)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff8188a871)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0763)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/input/evdev.c (ffffffff8193155d)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81962e25)
Location: include/linux/mm.h:751
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff819811af)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff819b835d)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff81a0442b)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
```
```
In net/core/page_pool.c (ffffffff81a3a459)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61704)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff81a646ae)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81a68605)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netfilter/core.c (ffffffff81a8db0a)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa2f6b)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb6fc)
Location: include/linux/mm.h:751
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9b35)
Location: include/linux/mm.h:751
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create
  - net/xdp/xsk_buff_pool.c:xp_create
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
In kernel/cgroup/cgroup-v1.c (ffffffff81176911)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811bd745)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff812149a8)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121797a)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8121ab6d)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/btf.c (ffffffff81224079)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff8122e802)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8123042c)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In mm/util.c (ffffffff8127d813)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/list_lru.c (ffffffff8128fdff)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_list_lru_node
```
```
In mm/swap_state.c (ffffffff812c57fb)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812cb35a)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff812cbb75)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/frame_vector.c (ffffffff8131553f)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff8133b854)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff81343fff)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff8134d525)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/xattr.c (ffffffff81350c12)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff8138d924)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813b00d0)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff813b2dc0)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/coredump.c (ffffffff813b973f)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/proc_sysctl.c (ffffffff813d922b)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff8141c8f3)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff8142e72d)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8144c1ae)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff8144ff2e)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff8148c1a9)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff814a5a98)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff814aa0bb)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff814ad028)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff814b7938)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff814df0b5)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814e5101)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff8150ca1a)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:deflate_decompress
```
```
In security/apparmor/match.c (ffffffff8150fcf6)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff81519e61)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff8154f777)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff8154f9f7)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/keyslot-manager.c (ffffffff8159e05f)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff815a4b10)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff815aadb8)
Location: include/linux/mm.h:779
Inline: True
```
```
In lib/bucket_locks.c (ffffffff815ac899)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff8170cf7f)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff81766e45)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff8179635d)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea3cb)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81801778)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8182177b)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8182aeeb)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859a32)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81898a71)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af703)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/input/evdev.c (ffffffff81938803)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff819696c5)
Location: include/linux/mm.h:779
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff819857cf)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff819ba78d)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff81a0648b)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
```
```
In net/core/page_pool.c (ffffffff81a3c9e9)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a6c7ee)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81a70d15)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netfilter/core.c (ffffffff81a97ada)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad49b)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad769f)
Location: include/linux/mm.h:779
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9aabc)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9105)
Location: include/linux/mm.h:779
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f7cb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/groups.c (ffffffff810d7af4)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177320)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811bd245)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff811f96cc)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff812171fc)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121adf0)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8121e81e)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81225a09)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff81228b49)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
```
```
In kernel/bpf/cpumap.c (ffffffff812336d8)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/util.c (ffffffff812829e3)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/list_lru.c (ffffffff81295567)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff812cc4cb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812d1ef1)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff812d2725)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/select.c (ffffffff81341d49)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff8134a39f)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff813546f8)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/xattr.c (ffffffff81357902)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff81391920)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_rsrc_data_alloc
```
```
In fs/binfmt_elf.c (ffffffff813b7200)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff813b9ea0)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/coredump.c (ffffffff813c089f)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/proc_sysctl.c (ffffffff813e06cb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81422f33)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff8143644d)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81451aad)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff8145571e)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff81491aa9)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff814aba68)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff814b09a3)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff814b2eb1)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff814bd7ac)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff814e5ac7)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814eba6d)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff8151308b)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In security/apparmor/match.c (ffffffff81516a24)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81520771)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff81557fe7)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff81558277)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/keyslot-manager.c (ffffffff815a4daf)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff815ae1e1)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff815b58c8)
Location: include/linux/mm.h:802
Inline: True
```
```
In lib/bucket_locks.c (ffffffff815b7505)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff816ee5da)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff8174aa85)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff8177902d)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ceacb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff817e6316)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804a9a)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8180e1cb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c772)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff8187b1b1)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892e33)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/input/evdev.c (ffffffff8191c072)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff8194d5c5)
Location: include/linux/mm.h:802
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff81965e93)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81969105)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff8199efad)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff819ecfdb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff81a2393d)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81a54f91)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81a59665)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netfilter/core.c (ffffffff81a82e2a)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98577)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac277d)
Location: include/linux/mm.h:802
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b899eb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8115)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0c43)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/groups.c (ffffffff810eb3a4)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119ea90)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811e7d15)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff8122ad7c)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff8122edec)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
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
```
```
In kernel/bpf/verifier.c (ffffffff8124da1d)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251bf0)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff81254e0e)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125da12)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff81260e39)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
```
```
In kernel/bpf/cpumap.c (ffffffff8126d35a)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/util.c (ffffffff812c0c63)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/list_lru.c (ffffffff812d5aa7)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff813116b5)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81317680)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff81318025)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/select.c (ffffffff8138f709)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff8139810c)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff813a2ad8)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/xattr.c (ffffffff813a5d32)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff813df820)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_files_register
```
```
In fs/binfmt_elf.c (ffffffff81406ee0)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff81409b90)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/coredump.c (ffffffff8141070f)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/proc_sysctl.c (ffffffff814320ff)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81476714)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff8148a041)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff814a5131)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff814a973e)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff814e9599)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81509afb)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In security/keys/keyctl.c (ffffffff815161ac)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff8153f1c7)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81545546)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff81570c8b)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In security/apparmor/match.c (ffffffff81574a24)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8157e911)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff815b9297)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff815b9527)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/keyslot-manager.c (ffffffff8160d823)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff81615aea)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff8161bd58)
Location: include/linux/mm.h:803
Inline: True
```
```
In lib/bucket_locks.c (ffffffff8161db35)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff817686ba)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff817cc345)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff817fef4d)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff818591db)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff818726bc)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f0ca)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff818987db)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c90d2)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff8190c9b1)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819258a7)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/input/evdev.c (ffffffff819be762)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff819f29d5)
Location: include/linux/mm.h:803
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81a059f8)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81a0de85)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81a11325)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff81a4bc4d)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff81a9e1eb)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff81ad7f6d)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81b0dcd1)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81b12715)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netfilter/core.c (ffffffff81b3ca7f)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53a54)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b799c7)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b8062f)
Location: include/linux/mm.h:803
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c55afb)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f4c)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75d65)
Location: include/linux/mm.h:803
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810c6a73)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/groups.c (ffffffff811062d0)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/printk/printk.c (ffffffff8115c17b)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf24f)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff8121db2e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff8125a01c)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff8126eb2e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff812716be)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
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
```
```
In kernel/bpf/verifier.c (ffffffff812949be)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_iter.c (ffffffff8129982e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8129e054)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7d63)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff812ac4b0)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff812bc492)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/util.c (ffffffff8131d8bf)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
```
```
In mm/swap_state.c (ffffffff8137c7e5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81382d89)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff813836b5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/select.c (ffffffff814108d9)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff8141a876)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff81426828)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/xattr.c (ffffffff8142a0ae)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
```
```
In fs/binfmt_elf.c (ffffffff8147b9cf)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff8147e7df)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/coredump.c (ffffffff81484998)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/proc_sysctl.c (ffffffff814acbcf)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff814f8a19)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff8150d01d)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8152d0c6)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff81531a5e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff81577d1b)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff8159b78e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In security/keys/keyctl.c (ffffffff815a8a50)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff815d6e66)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff815ddfac)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff8160b551)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In security/apparmor/match.c (ffffffff81612000)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d1af)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_compat.c (ffffffff81632734)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In crypto/lzo.c (ffffffff81662797)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff81662a87)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-crypto-profile.c (ffffffff816c2135)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff816cd5cf)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sqe_buffer_register
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_sqe_files_register
```
```
In lib/iov_iter.c (ffffffff816e270c)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff816e9748)
Location: include/linux/slab.h:748
Inline: True
```
```
In lib/bucket_locks.c (ffffffff816eb6f3)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff81ea4979)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f04e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/apei/erst.c (ffffffff8189ce8b)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/tty_io.c (ffffffff818f1be2)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/vt/consolemap.c (ffffffff81909cd5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff8193e020)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196bf25)
Location: include/linux/slab.h:748
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199e95a)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba867)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d85d9)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff819e26f9)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a16655)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81a612a1)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7e243)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/input/evdev.c (ffffffff81b1d5a5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81b555e5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_init_serial
```
```
In drivers/md/dm-zone.c (ffffffff81b6d6b0)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81b765ba)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81b79a5c)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff81bba36c)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff81c12a0d)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff81c58ce9)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81c950dd)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81c999f5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81cb457e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/netfilter/core.c (ffffffff81cc94ee)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce15a6)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d093c5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d109d4)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a212)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/unix/af_unix.c (ffffffff81d7d7e5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
```
```
In net/packet/af_packet.c (ffffffff81df1b34)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81e18f35)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a5cf)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3a09)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/groups.c (ffffffff8112bf1d)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/printk/printk.c (ffffffff8118ec0b)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212bdf)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/relay.c (ffffffff8124b892)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff812680be)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff812aa33b)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff812c430e)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff812c78e5)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
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
```
```
In kernel/bpf/verifier.c (ffffffff812ef59d)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f561a)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff812fbc79)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813063e8)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff8130be30)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff8131f9aa)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/vmscan.c (ffffffff81382745)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_start
```
```
In mm/util.c (ffffffff813914cf)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
```
```
In mm/swap_state.c (ffffffff813f9fb5)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff813fcce4)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff814010e5)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/select.c (ffffffff8149b5a9)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff814a6606)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff814b3098)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/xattr.c (ffffffff814b717e)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
```
```
In fs/binfmt_elf.c (ffffffff8150ec7f)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff815118ff)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/coredump.c (ffffffff81517ea4)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/proc_sysctl.c (ffffffff81542fef)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81593139)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff815a7d3d)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815c933f)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff815d2881)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff8161d24b)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81644aee)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In security/keys/keyctl.c (ffffffff81652be0)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff81685316)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8168cc58)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff816bdb3e)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
```
```
In security/apparmor/match.c (ffffffff816c4d20)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - security/apparmor/match.c:unpack_table
```
```
In security/apparmor/policy_unpack.c (ffffffff816d053f)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:kvmemdup
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_compat.c (ffffffff816e7514)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In crypto/lzo.c (ffffffff8171c8a7)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff8171cc17)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-crypto-profile.c (ffffffff81783435)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/filetable.c (ffffffff817940f6)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In io_uring/rsrc.c (ffffffff817a2470)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_pin_pages
```
```
In lib/iov_iter.c (ffffffff817d2ab6)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages
```
```
In lib/rhashtable.c (ffffffff817d98d8)
Location: include/linux/slab.h:735
Inline: True
```
```
In lib/bucket_locks.c (ffffffff817dbe33)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff8189ef61)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193dd4e)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/property.c (ffffffff81974ea0)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_data_add_buffer_props
```
```
In drivers/acpi/apei/erst.c (ffffffff819e5b1b)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/tty_io.c (ffffffff81a49c67)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/vt/consolemap.c (ffffffff81a643e5)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff81a9ef20)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6300)
Location: include/linux/slab.h:735
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b1032a)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2fd87)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b534c9)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81b5e346)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97465)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81bec5e6)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/input/evdev.c (ffffffff81caf585)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81cee685)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_init_serial
```
```
In drivers/md/dm-zone.c (ffffffff81d09a5e)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81d13990)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17e71)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff81d5f89c)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff81dc2b2c)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff81e0ebd9)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81e50bdd)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81e55d15)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81e727fe)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/ethtool/common.c (ffffffff81e7c5bf)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/netfilter/core.c (ffffffff81e890be)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2656)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece645)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6734)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02b72)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/unix/af_unix.c (ffffffff81f49467)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
```
```
In net/packet/af_packet.c (ffffffff81fc5b04)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0318)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1af0)
Location: include/linux/slab.h:735
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810ef286)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/groups.c (ffffffff81138d7d)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/printk/printk.c (ffffffff811a039b)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In kernel/dma/remap.c (ffffffff811d8892)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_common_contiguous_remap
```
```
In kernel/module/decompress.c (ffffffff811e199b)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_extend_max_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812284ef)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/relay.c (ffffffff81262b12)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff8127f27e)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff812ccaaa)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff812eb2be)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff812eedb5)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
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
```
```
In kernel/bpf/verifier.c (ffffffff8131beb7)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_iter.c (ffffffff813233ba)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8132a54a)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/btf.c (ffffffff8133ae90)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff8134f9aa)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/vmscan.c (ffffffff813b42d5)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_start
```
```
In mm/util.c (ffffffff813c3f5f)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
  - mm/util.c:kvmemdup
```
```
In mm/swap_state.c (ffffffff8142cef5)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8142ffc1)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff81433fc5)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/select.c (ffffffff814d0437)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff814db5c1)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff814e80e8)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/xattr.c (ffffffff814ebff0)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
```
```
In fs/verity/open.c (ffffffff8153ce5b)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/binfmt_elf.c (ffffffff8154643f)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff815491df)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/coredump.c (ffffffff8154f79e)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b432)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff815ca17e)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff815de5ad)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff816010fe)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff8160a37a)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff816553ab)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff8167cfb6)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In security/keys/keyctl.c (ffffffff8168b400)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff816bd689)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff816c4f62)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff816f65f6)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
```
```
In security/apparmor/match.c (ffffffff816fdc25)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8170911f)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_compat.c (ffffffff81720c73)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In crypto/lzo.c (ffffffff81758047)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff817583b7)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-crypto-profile.c (ffffffff817c3790)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff817c9385)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uaddr_map
```
```
In io_uring/filetable.c (ffffffff817d4dd6)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In io_uring/rsrc.c (ffffffff817e34f2)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
```
```
In lib/iov_iter.c (ffffffff8181466d)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff81818c51)
Location: include/linux/slab.h:718
Inline: True
```
```
In lib/bucket_locks.c (ffffffff8181b1f2)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff818e1427)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8198212e)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/property.c (ffffffff819bb6f5)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_data_add_buffer_props
```
```
In drivers/acpi/apei/erst.c (ffffffff81a2e163)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/tty_io.c (ffffffff81a942e6)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/vt/consolemap.c (ffffffff81aaea95)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/tty/vt/vt.c (ffffffff81ab101b)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_get
```
```
In drivers/char/agp/generic.c (ffffffff81aea88e)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b24aa5)
Location: include/linux/slab.h:718
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5e3ea)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81b831e1)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6971)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81bb1906)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff81beda2e)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81c449c3)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/input/evdev.c (ffffffff81d16b85)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81d573b5)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_init_serial
```
```
In drivers/md/dm-zone.c (ffffffff81d727c4)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81d7caf0)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81d810fc)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff81dca99c)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff81e31fdc)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff81e82260)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81eac3fb)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81eb15b5)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81ece98a)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/ethtool/common.c (ffffffff81ed8957)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/netfilter/core.c (ffffffff81ee70ae)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00e76)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d2e8)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3568a)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
```
```
In net/ipv4/udp.c (ffffffff81f3fd95)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6230b)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/unix/af_unix.c (ffffffff81fa9047)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
```
```
In net/packet/af_packet.c (ffffffff8202a04e)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4c3)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206dcee)
Location: include/linux/slab.h:718
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b4c7)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f8546)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
```
In kernel/resource.c (ffffffff8110bf50)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/resource.c:walk_system_ram_res_rev
```
```
In kernel/groups.c (ffffffff81143abd)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/printk/printk.c (ffffffff811af3bb)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In kernel/dma/remap.c (ffffffff811ee3a2)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_common_contiguous_remap
```
```
In kernel/module/decompress.c (ffffffff811f784c)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_zstd_decompress
  - kernel/module/decompress.c:module_extend_max_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812402f0)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/relay.c (ffffffff8127cd32)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff81299ffe)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea405)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff813097e0)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff8130db75)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
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
```
```
In kernel/bpf/verifier.c (ffffffff8133e26f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_iter.c (ffffffff813472ea)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8134ea12)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/btf.c (ffffffff8136101e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff81376eba)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/vmscan.c (ffffffff813dd955)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_start
```
```
In mm/util.c (ffffffff813eeb0f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:vmemdup_user
  - mm/util.c:kvmemdup
```
```
In mm/swap_state.c (ffffffff81466605)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81469a60)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/swap_slots.c (ffffffff8146d3c5)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/select.c (ffffffff81502d77)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff8150dbc1)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/namespace.c (ffffffff815139ec)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_statmount
```
```
In fs/seq_file.c (ffffffff8151bf78)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/xattr.c (ffffffff8151ff10)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_alloc
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
```
```
In fs/verity/open.c (ffffffff815722bb)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/binfmt_elf.c (ffffffff8157b88f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_files_note
```
```
In fs/compat_binfmt_elf.c (ffffffff8157e45f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_files_note
```
```
In fs/coredump.c (ffffffff815855dd)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/proc_sysctl.c (ffffffff815b3ce2)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/mballoc.c (ffffffff81602f8e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/resize.c (ffffffff8161703f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81639e4e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/xattr.c (ffffffff81643128)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/fuse/dev.c (ffffffff8168e11b)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In fs/pstore/platform.c (ffffffff816adc6b)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:decompress_record
  - fs/pstore/platform.c:pstore_register
```
```
In ipc/sem.c (ffffffff816b9386)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In security/keys/keyctl.c (ffffffff816c7900)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff816fa019)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81701ba3)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/apparmorfs.c (ffffffff81733356)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:decompress_zstd
```
```
In security/apparmor/match.c (ffffffff8173b1b7)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81746baf)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_compat.c (ffffffff8175f7b9)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_policy
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In crypto/lzo.c (ffffffff81799f47)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff8179a2b7)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8179fb65)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_kvzalloc
```
```
In block/blk-crypto-profile.c (ffffffff81808420)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff818109e0)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uaddr_map
```
```
In io_uring/filetable.c (ffffffff81818c26)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In io_uring/rsrc.c (ffffffff818275a2)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
```
```
In lib/iov_iter.c (ffffffff8185966e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff8185df81)
Location: include/linux/slab.h:726
Inline: True
```
```
In lib/bucket_locks.c (ffffffff81860532)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff81928073)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951a0d)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c993e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/property.c (ffffffff81a05f25)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_data_add_buffer_props
```
```
In drivers/acpi/apei/erst.c (ffffffff81a793d3)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/tty_io.c (ffffffff81ae6d68)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:iterate_tty_write
```
```
In drivers/tty/vt/consolemap.c (ffffffff81b01785)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/tty/vt/vt.c (ffffffff81b03c7b)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_get
```
```
In drivers/char/agp/generic.c (ffffffff81b3dd6d)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b715)
Location: include/linux/slab.h:726
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb1cfa)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7108)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfac21)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81c05df6)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c43160)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c74e)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81cadd9b)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_create_blob
```
```
In drivers/net/tun.c (ffffffff81cfa523)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/input/evdev.c (ffffffff81dcc835)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/md.c (ffffffff81e0e315)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_init_serial
```
```
In drivers/md/dm-zone.c (ffffffff81e29854)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81e33fd0)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81e3875d)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
```
In drivers/leds/led-triggers.c (ffffffff81e8350c)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
```
```
In net/core/dev.c (ffffffff81ef0479)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff81f4323f)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81f6ee8b)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81f74065)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81f921ba)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/ethtool/common.c (ffffffff81f9c777)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
```
```
In net/netfilter/core.c (ffffffff81faaebe)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc51d6)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2188)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
```
```
In net/ipv4/tcp_metrics.c (ffffffff83969956)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
```
```
In net/ipv4/udp.c (ffffffff82005a55)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
```
```
In net/ipv4/fib_semantics.c (ffffffff820288db)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/unix/af_unix.c (ffffffff82076547)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
```
```
In net/packet/af_packet.c (ffffffff820f9b4d)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff821402c1)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141d6d)
Location: include/linux/slab.h:726
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In virt/kvm/kvm_main.c (ffff8000100b7f88)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101da8b4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffff800010228628)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffff8000102742ac)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffff8000102855a4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffff800010288818)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffff8000102d8700)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffff8000102e6ff4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffff8000102eefe8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffff8000103220b4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffff800010327f94)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffff800010329804)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffff8000103662a4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffff800010379868)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffff8000103a46b0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffff8000103b0b90)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffff8000103bbc84)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffff8000103be8d0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffff80001040360c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffff800010420c44)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104244f0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffff800010494758)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffff8000104bf578)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffff800010505540)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffff80001051e85c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffff800010524170)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffff80001052653c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffff800010533254)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__arm64_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffff80001055be7c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffff800010560fbc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffff8000105905b0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffff80001059915c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffff8000105cfde0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffff8000105d0150)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffff80001061fe78)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffff80001062de6c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffff800010635ddc)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffff800010638320)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffff80001074d93c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/acpi/apei/erst.c (ffff8000107ad930)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffff80001086ffe4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c9f8c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/base/firmware_loader/main.c (ffff80001090ceb0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffff800010925dc8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/nvdimm/dimm_devs.c (ffff80001095439c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffff80001095ddb4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffff8000109dc8b8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/input/evdev.c (ffff800010a9e288)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (ffff800010b094a4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffff800010bcc724)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffff800010c0c764)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffff800010c3107c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffff800010c37a48)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffff800010c3ba10)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffff800010c53e00)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffff800010c698e4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91b54)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffff800010d81708)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (c041d1e4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/trace/trace.c (c0465c70)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (c04a6948)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (c04b5b88)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (c04b7db8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (c04ff854)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (c050b1b8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (c0512eb0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (c053a770)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (c053f3b8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (c0540148)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (c0556938)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (c0564aa4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (c0586200)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (c059045c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (c05993d4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (c059b5fc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (c05d6d58)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (c05e8bbc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (c06561d4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (c0683198)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (c06c193c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (c06da9fc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (c06def50)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (c06e06d8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (c06eaaf0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/selinux/ss/avtab.c (c07105b8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (c0715d24)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (c0741308)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c074a44c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (c077d94c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (c077dc18)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (c07c798c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (c07d4cc4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (c07dbccc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/bucket_locks.c (c07ddc5c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (c08d1364)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/tty/vt/consolemap.c (c097335c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (c09f5fd8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/net/tun.c (c0ac6ec0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (c0b7f270)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (c0be7c98)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In sound/core/info.c (c0c897e8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - sound/core/info.c:snd_info_text_entry_write
```
```
In net/core/dev.c (c0ce6af8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (c0d24e2c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (c0d4857c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (c0d4ad3c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (c0d4d8b4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (c0d63840)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (c0d78d58)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (c0da0860)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (c0e7bcb0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (c000000000248928)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (c0000000002af0b0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (c00000000031bf08)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (c000000000330418)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (c000000000333d38)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (c0000000003984c8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (c0000000003a8b4c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (c0000000003b36f8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (c0000000003f7a60)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (c0000000003fef38)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (c0000000004001f4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (c000000000450a6c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (c00000000046ca60)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (c00000000049e2b0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (c0000000004ac584)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (c0000000004b91d0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (c0000000004bbd40)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (c00000000051023c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (c00000000052f8d4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005334ec)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (c0000000005bdbf4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (c0000000005f5c30)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (c00000000064aa24)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (c000000000668928)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (c00000000066e5e0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (c000000000671960)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (c000000000680e60)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/selinux/ss/avtab.c (c0000000006bb378)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (c0000000006c2354)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (c000000000703c80)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c00000000071028c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (c00000000075be90)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (c00000000075c2a0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (c0000000007bf4c4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (c0000000007d1514)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (c0000000007dc340)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (c0000000007de5cc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (c0000000008b5010)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/tty/vt/consolemap.c (c00000000090ffb0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (c000000000955e30)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (c0000000009ad0fc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a019a4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (c000000000a0fa54)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (c000000000a9efa4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (c000000000b7e964)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (c000000000bfafc0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (c000000000caba58)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (c000000000cf7e90)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (c000000000d2b2e0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (c000000000d305c0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (c000000000d35280)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (c000000000d53710)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e688)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (c000000000da20bc)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (c000000000ec1640)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (ffffffe000152e72)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffe000182f74)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffe0001acbfc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffe0001baa00)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc9ae)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffe0001f2e3c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffe0001fcce4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffe000202e4c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffe0002230fe)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffe000227d4a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffe000228ba0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffe000243090)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffe000250c86)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffe00026b670)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffe000274fba)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffe00027d6dc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffe00027eea4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffe0002adf44)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffe0002c16a8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffe000319412)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffe00033a848)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffe000371efc)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffe000385f70)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffe000388f96)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffe00038adf6)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffe0003938be)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffe0003b2b9e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffe0003b8158)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffffffe0003de032)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e592a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffe000414bf4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffe000414e52)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffffffe00045260a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffe00045da8a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffe000463b62)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffffffe00046510e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fec50)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/tty/vt/consolemap.c (ffffffe000542554)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffe000591bb0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3bc8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffe0005cbe66)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffe000627dd0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (ffffffe0006adf40)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f79e6)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffe0007581aa)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffe000789b16)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7a0e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffe0007a9b46)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffe0007ac6c8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffe0007be60a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf8e2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1bdc)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffe0008adb92)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (ffffffff811603c3)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811a3e47)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811e913a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811f6bef)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811f8b61)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff8123d905)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff812486ea)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff8124fbd7)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff8127fb10)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81284f09)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81285c45)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffff812ba3a2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffff812cbf9f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812ef959)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff812f7c5f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff813006b5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff813020a5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff8133da32)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813538a4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81357109)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff813b610d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813de86c)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffff8141ad62)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff814309a8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81434906)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff81437348)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff81441be8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff8146537f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8146a47e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffffffff81492ae9)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149ba2d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff814cbb35)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff814cbdb5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffffffff81510ae3)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff8151c330)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff81523277)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffffffff81524999)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b9f92)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/tty/vt/consolemap.c (ffffffff8165edd5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff8168dbcd)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff816dfbab)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff816f4dfe)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8170813b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff81710d6d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffff81786cad)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (ffffffff8181239f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (ffffffff8185733a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff818d07fb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff819070ba)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8192985d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff8192cfd5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff8192f8f5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff81944884)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff819584bb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e83f)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81a4c16d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (ffffffff81153633)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff81196e17)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811dbefa)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811e993f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811eb8b1)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff81230905)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff8123b69a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff81242b77)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff812719b0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81276d79)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81277ab5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffff812ab562)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffff812bce0f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812e0589)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff812e887f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff812f12d5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff812f2cc5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff8132e6f2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff81344564)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81347db9)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff813a6b9d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813cf2ec)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffff8140b7e2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff81421428)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81425386)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff81427db8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff81432658)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff81455daf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8145aeae)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffffffff81483509)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8148c44d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff814bc555)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff814bc7d5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffffffff81500e03)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff8150c620)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff81513557)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffffffff81514c79)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a8d72)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/acpi/apei/erst.c (ffffffff815feb80)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff8163f155)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff8166b5bd)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba1eb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dbbbb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff816e47ed)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffff817665fd)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (ffffffff817d9adf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (ffffffff8181e94a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff8188a6db)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff818c0eca)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff818e360d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff818e6ad5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff818e93f5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff818fe374)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff81911fab)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819382ff)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81a08d5d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115e193)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811a1c17)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811e6f0a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811f49bf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811f6931)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff8123b6a5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff8124648a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff8124d977)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff8127d930)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81282d19)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81283a55)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffff812b81b2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffff812c9daf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812ed769)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff812f5a6f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff812fe4a5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff812ffe95)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff8133b502)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff81351374)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81354bd9)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff813b396d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813dbc29)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffff81416f02)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff8142cb48)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81430aa6)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff814334e8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff8143dd88)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff8146141f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8146651e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffffffff8148eb89)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81497acd)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff814c7bc5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff814c7e45)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffffffff8150cb73)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff815183c0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff8151f307)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffffffff81520a29)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ba522)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/acpi/apei/erst.c (ffffffff816365b0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff8168d1b5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff816bbe3d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d2cb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8172234e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746f0b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8174fb3d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffff817b705d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (ffffffff8185151f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (ffffffff818a696a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff819217fb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff819580ea)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a9ed)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff8197e165)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81980a85)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff81995a14)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ce95)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_alloc_hashtable
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2c8b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e900f)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81ab801d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116b5c3)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811af9a7)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811f52ba)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff81202ecf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff81205561)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/util.c (ffffffff8124adb5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/util.c:vmemdup_user
```
```
In mm/slab_common.c (ffffffff81255c9a)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:memcg_update_all_caches
```
```
In mm/list_lru.c (ffffffff8125d637)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/swap_state.c (ffffffff8128d4e0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812929fe)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81293745)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In mm/memcontrol.c (ffffffff812c8ae2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In mm/frame_vector.c (ffffffff812daaaf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/frame_vector.c:frame_vector_create
```
```
In fs/select.c (ffffffff812fe773)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/file.c (ffffffff81306baf)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
  - fs/file.c:alloc_fdtable
```
```
In fs/seq_file.c (ffffffff8130f7e5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffffffff813111d5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/io_uring.c (ffffffff8134e6b2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff81364914)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813681b9)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/mballoc.c (ffffffff813c8503)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/super.c (ffffffff813f0fd9)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/fuse/dev.c (ffffffff8142dc92)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/msg.c (ffffffff81443468)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffff81447101)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffff8144a8b8)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
```
In security/keys/keyctl.c (ffffffff81454f08)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/selinux/ss/avtab.c (ffffffff81478c1f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8147dcfe)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/match.c (ffffffff814a6a99)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814afc1d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In crypto/lzo.c (ffffffff814e0695)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
```
In crypto/lzo-rle.c (ffffffff814e0915)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - crypto/lzo-rle.c:lzorle_init
```
```
In block/blk-zoned.c (ffffffff81526253)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff81531c40)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/rhashtable.c (ffffffff81538d27)
Location: include/linux/mm.h:668
Inline: True
```
```
In lib/bucket_locks.c (ffffffff8153a3a9)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d3fd2)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
```
```
In drivers/acpi/apei/erst.c (ffffffff816508c0)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff816a77b5)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/char/agp/generic.c (ffffffff816d640d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/base/firmware_loader/main.c (ffffffff81727eeb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8173d78e)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8176234b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
```
```
In drivers/nvdimm/label.c (ffffffff8176afbd)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/net/tun.c (ffffffff817d12ad)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/evdev.c (ffffffff8186c33f)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/md/dm-ioctl.c (ffffffff818c2baa)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/core/dev.c (ffffffff819401cb)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/core/page_pool.c (ffffffff8197a1fa)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cf1d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff819a0965)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff819a3005)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/core.c (ffffffff819b85f4)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/netfilter/core.c:allocate_hook_entries_size
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc75b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2d6f)
Location: include/linux/mm.h:668
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffff81ac443d)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
</details>
</li>
</ul>

## Differences
