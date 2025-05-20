# Function: <code>kvfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abe70)
Location: mm/util.c:294
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_destroy_work_fn
  - kernel/cgroup.c:pidlist_array_load
  - kernel/cgroup.c:pidlist_array_load
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - mm/frame_vector.c:frame_vector_destroy
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:alloc_fdtable
  - fs/seq_file.c:traverse
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:single_release
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_open_size
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_release
  - ipc/util.c:ipc_rcu_free
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/match.c:dfa_free
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - crypto/lzo.c:lzo_exit
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:bucket_table_free
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff811abe70-ffffffff811abea3: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c48f0)
Location: mm/util.c:324
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/bpf/stackmap.c:stack_map_alloc
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:pcpu_extend_area_map
  - mm/vmalloc.c:__vunmap
  - mm/frame_vector.c:frame_vector_destroy
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - ipc/util.c:ipc_rcu_free
  - ipc/util.c:ipc_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:dfa_free
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
  - crypto/lzo.c:lzo_exit
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:bucket_table_free
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff811c48f0-ffffffff811c4925: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4a00)
Location: mm/util.c:327
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/syscall.c:bpf_map_area_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:pcpu_extend_area_map
  - mm/vmalloc.c:__vunmap
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - ipc/util.c:ipc_rcu_free
  - ipc/util.c:ipc_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:dfa_free
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
  - crypto/lzo.c:lzo_exit
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:bucket_table_free
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff811d4a00-ffffffff811d4a35: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd820)
Location: mm/util.c:411
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/syscall.c:bpf_map_area_free
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:pcpu_extend_area_map
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:bucket_table_free
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff811dd820-ffffffff811dd855: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f32a0)
Location: mm/util.c:411
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:SyS_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:free_memcg_params
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:SYSC_swapoff
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - block/bio.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:bucket_table_free
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
  - net/netfilter/core.c:nf_register_net_hook
```
**Symbols:**

```
ffffffff811f32a0-ffffffff811f32d5: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812144e0)
Location: mm/util.c:437
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:free_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:traverse
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:free_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:__page_pool_destroy_rcu
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
```
**Symbols:**

```
ffffffff812144e0-ffffffff81214515: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812273b0)
Location: mm/util.c:440
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:free_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:free_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:__page_pool_destroy_rcu
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff812273b0-ffffffff812273e5: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812370a0)
Location: mm/util.c:483
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:free_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff812370a0-ffffffff812370d5: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245270)
Location: mm/util.c:588
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81245270-ffffffff812452a5: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127306e)
Location: mm/util.c:598
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_evict_inode
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_list_lru_node
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_fdtable
  - fs/file.c:expand_fdtable
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:deflate_decompress
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:unpack_table
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_buff_pool.c:xp_create
  - net/xdp/xsk_buff_pool.c:xp_create
```
**Symbols:**

```
ffffffff81272e70-ffffffff81272ea0: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d7ce)
Location: mm/util.c:611
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_evict_inode
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_list_lru_node
  - mm/list_lru.c:kvfree_rcu_local
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_fdtable
  - fs/file.c:expand_fdtable
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:deflate_decompress
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:unpack_table
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netif_alloc_rx_queues
  - net/core/page_pool.c:page_pool_release
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff8127d550-ffffffff8127d580: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8128299e)
Location: mm/util.c:611
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/bpf/core.c:bpf_prog_jit_attempt_done
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:free_shrinker_info
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_evict_inode
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:__io_sqe_buffers_unregister
  - fs/io_uring.c:io_buffer_unmap
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_unregister
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff812826e0-ffffffff81282710: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0b9e)
Location: mm/util.c:617
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/bpf/core.c:bpf_prog_jit_attempt_done
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/btf.c:btf_free_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:free_shrinker_info
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_evict_inode
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_buffer_unmap
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:__io_sqe_files_unregister
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff812c0800-ffffffff812c0830: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d8e4)
Location: mm/util.c:650
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/printk/printk.c:devkmsg_release
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_prog_jit_attempt_done
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:free_shrinker_info
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_evict_inode
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:unpack_table
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_compat.c:aa_compat_map_file
  - security/apparmor/policy_compat.c:aa_compat_map_policy
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_sqe_buffer_register
  - io_uring/io_uring.c:io_sqe_buffer_register
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_buffer_unmap
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:__io_sqe_files_unregister
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_fsetxattr
  - io_uring/io_uring.c:io_getxattr
  - io_uring/io_uring.c:io_getxattr
  - io_uring/io_uring.c:io_fgetxattr
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:__tun_detach
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/unix/af_unix.c:bpf_iter_fini_unix
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff8131d340-ffffffff8131d37f: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813914f4)
Location: mm/util.c:622
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/printk/printk.c:devkmsg_release
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_prog_jit_attempt_done
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:free_shrinker_info
  - mm/shmem.c:shmem_initxattrs
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:unpack_table
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_compat.c:aa_compat_map_file
  - security/apparmor/policy_compat.c:aa_compat_map_policy
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/filetable.c:io_free_file_tables
  - io_uring/filetable.c:io_alloc_file_tables
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_buffer_unmap
  - lib/iov_iter.c:iov_iter_get_pages_alloc2
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_cleanup
  - drivers/acpi/property.c:acpi_free_device_properties
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/udp.c:udp_pernet_exit
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/unix/af_unix.c:bpf_iter_fini_unix
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff81390cb0-ffffffff81390cef: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3f84)
Location: mm/util.c:645
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/printk/printk.c:devkmsg_release
  - kernel/printk/printk.c:devkmsg_release
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_rcu_list
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/module/decompress.c:module_decompress_cleanup
  - kernel/module/decompress.c:module_extend_max_pages
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_prog_jit_attempt_done
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:free_shrinker_info
  - mm/shmem.c:shmem_initxattrs
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/vmalloc.c:vfree
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/verity/open.c:__fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_compat.c:aa_compat_map_file
  - security/apparmor/policy_compat.c:aa_compat_map_policy
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/filetable.c:io_free_file_tables
  - io_uring/filetable.c:io_alloc_file_tables
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_buffer_unmap
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_cleanup
  - drivers/acpi/property.c:acpi_free_device_properties
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/udp.c:bpf_iter_fini_udp
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/udp.c:udp_pernet_exit
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/unix/af_unix.c:bpf_iter_fini_unix
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
**Symbols:**

```
ffffffff813c35c0-ffffffff813c35ff: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813eeb34)
Location: mm/util.c:658
Inline: True
Inline callers:
  - mm/util.c:kvrealloc
  - mm/util.c:kvfree_sensitive
  - mm/util.c:vmemdup_user
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:finalize_late_load
  - arch/x86/kernel/cpu/microcode/intel.c:finalize_late_load
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:save_builtin_microcode
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - kernel/resource.c:walk_system_ram_res_rev
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/printk/printk.c:devkmsg_release
  - kernel/printk/printk.c:devkmsg_release
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_rcu_list
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/module/decompress.c:module_decompress_cleanup
  - kernel/module/decompress.c:module_zstd_decompress
  - kernel/module/decompress.c:module_extend_max_pages
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_dealloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_prog_jit_attempt_done
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:free_shrinker_info
  - mm/shmem.c:shmem_initxattrs
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - fs/select.c:core_sys_select
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
  - fs/file.c:alloc_fdtable
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:free_fdtable_rcu
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__do_sys_statmount
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read_iter
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/verity/open.c:__fsverity_cleanup_inode
  - fs/verity/open.c:fsverity_set_info
  - fs/verity/open.c:fsverity_create_info
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_files_note
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_files_note
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/pstore/platform.c:pstore_init
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:decompress_record
  - fs/pstore/platform.c:decompress_record
  - fs/pstore/platform.c:decompress_record
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_write_user_compat
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:decompress_zstd
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - crypto/jitterentropy-kcapi.c:jent_kvzfree
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/bio-integrity.c:bio_integrity_map_user
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/filetable.c:io_free_file_tables
  - io_uring/filetable.c:io_alloc_file_tables
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_buffer_unmap
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_cleanup
  - drivers/acpi/property.c:acpi_free_device_properties
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:iterate_tty_write
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/generic.c:agp_free_memory
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_decompress_zstd
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_property.c:drm_property_create_blob
  - drivers/gpu/drm/drm_property.c:drm_property_free_blob
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_create
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/leds/led-triggers.c:led_trigger_read
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_create
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/udp.c:bpf_iter_fini_udp
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/udp.c:udp_pernet_exit
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/unix/af_unix.c:bpf_iter_fini_unix
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:fanout_add
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
  - lib/objpool.c:objpool_init
```
**Symbols:**

```
ffffffff813ee0e0-ffffffff813ee11f: kvfree (STB_GLOBAL)
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
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8228)
Location: mm/util.c:588
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:kvm_free_memslots
  - virt/kvm/kvm_main.c:kvm_free_memslot
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/iommu/dma-iommu.c:__iommu_dma_free_pages
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffff8000102d8228-ffff8000102d827c: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff63c)
Location: mm/util.c:588
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - arch/arm/mm/dma-mapping.c:__iommu_free_buffer
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_maps
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_user_free
  - sound/core/control.c:snd_ctl_elem_user_free
  - sound/core/control.c:snd_ctl_elem_user_tlv
  - sound/core/control.c:snd_ctl_elem_user_tlv
  - sound/core/info.c:snd_info_text_entry_release
  - sound/core/info.c:snd_info_text_entry_write
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
c04ff63c-c04ff694: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397f20)
Location: mm/util.c:588
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/list_lru.c:memcg_destroy_list_lru_node
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
c000000000397f20-c000000000397fa8: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2b4a)
Location: mm/util.c:588
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_current_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_maps
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffe0001f2b4a-ffffffe0001f2b96: kvfree (STB_GLOBAL)
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
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d8c0)
Location: mm/util.c:588
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff8123d8c0-ffffffff8123d8f5: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812308c0)
Location: mm/util.c:588
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff812308c0-ffffffff812308f5: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b660)
Location: mm/util.c:588
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_end
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_fini
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_fini
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_init
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff8123b660-ffffffff8123b695: kvfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kvfree(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124ad70)
Location: mm/util.c:588
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_area_free
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/btf.c:btf_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/util.c:vmemdup_user
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/slab_common.c:free_memcg_params
  - mm/slab_common.c:destroy_memcg_params
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:kvfree_rcu
  - mm/vmalloc.c:__vunmap
  - mm/swap_state.c:exit_swap_address_space
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/memcontrol.c:memcg_free_shrinker_map_rcu
  - mm/frame_vector.c:frame_vector_destroy
  - fs/select.c:core_sys_select
  - fs/file.c:alloc_fdtable
  - fs/file.c:__free_fdtable
  - fs/file.c:__free_fdtable
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
  - fs/seq_file.c:single_open_size
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
  - fs/splice.c:default_file_splice_read
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/ext4/resize.c:ext4_rcu_ptr_callback
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - ipc/msg.c:newque
  - ipc/msg.c:msg_rcu_free
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:newary
  - ipc/sem.c:sem_rcu_free
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_rcu_free
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/commoncap.c:cap_convert_nscap
  - security/selinux/ss/avtab.c:avtab_init
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - crypto/lzo.c:lzo_exit
  - crypto/lzo-rle.c:lzorle_exit
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/rhashtable.c:bucket_table_free
  - lib/bucket_locks.c:free_bucket_spinlocks
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/char/agp/generic.c:agp_generic_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-ioctl.c:free_params
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/md/dm-stats.c:dm_stat_free
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/page_pool.c:page_pool_release
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_destroy
  - net/sched/sch_api.c:qdisc_class_hash_destroy
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/netfilter/core.c:__nf_hook_entries_free
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff8124ad70-ffffffff8124ada5: kvfree (STB_GLOBAL)
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
