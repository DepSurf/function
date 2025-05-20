# Function: <code>kvcalloc</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c8ebf)
Location: include/linux/mm.h:597
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
```
```
In mm/swap_state.c (ffffffff8124829f)
Location: include/linux/mm.h:597
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8124db3b)
Location: include/linux/mm.h:597
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8124e7c5)
Location: include/linux/mm.h:597
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
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
Location: include/linux/mm.h:625
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/btf.c (ffffffff811dc0b8)
Location: include/linux/mm.h:625
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
```
```
In mm/swap_state.c (ffffffff8125c870)
Location: include/linux/mm.h:625
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81261f5c)
Location: include/linux/mm.h:625
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81262ca5)
Location: include/linux/mm.h:625
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
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
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811f220b)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff81277a50)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8127ce47)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8127dbf5)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff81452fff)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814580fe)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff814fa5a3)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff8170ab8e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In net/core/bpf_sk_storage.c (ffffffff8195363f)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (ffffffff811ab827)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811f0b1a)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811fe91b)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff81287540)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8128c916)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8128d665)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff8146cd9f)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81471e9e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81518503)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff8172ee8e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In net/core/bpf_sk_storage.c (ffffffff819899ed)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (ffffffff811c3c7b)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff812131bf)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/btf.c (ffffffff8121f87a)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
```
```
In mm/swap_state.c (ffffffff812b9d8b)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812bf7b1)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff812c0115)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff814c156f)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814c7063)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff8158103f)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817ece48)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848eeb)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61704)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9b8a)
Location: include/linux/mm.h:774
Inline: True
Inline callers:
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
In kernel/trace/trace.c (ffffffff811c188b)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff812149a8)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/btf.c (ffffffff8122ac5a)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81230428)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In mm/swap_state.c (ffffffff812c57fb)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812cb34e)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff812cbb75)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff814df0b5)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814e5101)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff8159e05f)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81801778)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859a32)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9105)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
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
In kernel/trace/trace.c (ffffffff811c28c2)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff811f96cc)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff812171fc)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81225a09)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff8122f59a)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
```
```
In mm/swap_state.c (ffffffff812cc4cb)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812d1ee5)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff812d2725)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/io_uring.c (ffffffff813920f7)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_data_alloc
```
```
In security/selinux/ss/avtab.c (ffffffff814e5ac7)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814eba6d)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff815a4daf)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817e6316)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c772)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/md/dm-table.c (ffffffff81965e93)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8115)
Location: include/linux/mm.h:825
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
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
In kernel/trace/trace.c (ffffffff811ed5a2)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff8122ad7c)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff8124da1d)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125da12)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff812682fa)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
```
```
In mm/swap_state.c (ffffffff813116b5)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81317674)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81318025)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/io_uring.c (ffffffff813ec7ff)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_register
```
```
In security/selinux/ss/avtab.c (ffffffff8153f1c7)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81545546)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff8160d823)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
```
```
In drivers/block/xen-blkfront.c (ffffffff818726bc)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c90d2)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/md/dm-zone.c (ffffffff81a059f8)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81a0de85)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f4c)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75d65)
Location: include/linux/mm.h:826
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
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
In kernel/trace/trace.c (ffffffff81225770)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff8126c6f5)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff812949be)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7d63)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff812b562a)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff8137c7e5)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81382d7d)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff813836b5)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff815d6e66)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff815ddfac)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff81632728)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff816c2118)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff81e9151a)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sqe_files_register
```
```
In lib/stackdepot.c (ffffffff81ea4979)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f047)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196bf25)
Location: include/linux/slab.h:771
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba867)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a16655)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/md/dm-zone.c (ffffffff81b6d6b0)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81b765ba)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/xdp/xdp_umem.c (ffffffff81e18f35)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a5cf)
Location: include/linux/slab.h:771
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
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
In kernel/relay.c (ffffffff8124b892)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff812709b0)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff812c17b5)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff812ef59d)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813063e8)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff81315c5a)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff813f9fb5)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff813fcce4)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff814010e5)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff81685316)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8168cc58)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff816e7508)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff81783418)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/filetable.c (ffffffff817940f6)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In lib/stackdepot.c (ffffffff8189ef61)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193dd47)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6300)
Location: include/linux/slab.h:758
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2fd87)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97465)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/md/dm-zone.c (ffffffff81d09a5e)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81d13990)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0318)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1af0)
Location: include/linux/slab.h:758
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
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
In kernel/relay.c (ffffffff81262b12)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff81287c80)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff812e861d)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff812f0775)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
```
```
In kernel/bpf/verifier.c (ffffffff8131beb7)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/btf.c (ffffffff81345c26)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff8142cef5)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8142ffc1)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81433fc5)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/verity/open.c (ffffffff8153ce5b)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In security/selinux/ss/avtab.c (ffffffff816bd689)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff816c4f62)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff81720c54)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff817c3774)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/filetable.c (ffffffff817d4dd6)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In lib/stackdepot.c (ffffffff818e1427)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982127)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b24aa5)
Location: include/linux/slab.h:741
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b831e1)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81beda2e)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/md/dm-zone.c (ffffffff81d727c4)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81d7caf0)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4c3)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206dcee)
Location: include/linux/slab.h:741
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
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
In kernel/resource.c (ffffffff8110bf50)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/resource.c:walk_system_ram_res_rev
```
```
In kernel/relay.c (ffffffff8127cd32)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff812a2f90)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea405)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff8130698d)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff8130f555)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
```
```
In kernel/bpf/verifier.c (ffffffff8133e26f)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/btf.c (ffffffff8136bbb6)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff81466605)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81469a58)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8146d3c5)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/verity/open.c (ffffffff815722bb)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In security/selinux/ss/avtab.c (ffffffff816fa019)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81701ba3)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff8175f7b9)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_policy
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff81808404)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/filetable.c (ffffffff81818c26)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In lib/stackdepot.c (ffffffff8192806f)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9937)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b715)
Location: include/linux/slab.h:749
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7108)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c43160)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/md/dm-zone.c (ffffffff81e29854)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81e33fd0)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/xdp/xdp_umem.c (ffffffff821402c1)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141d6d)
Location: include/linux/slab.h:749
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_init_dma_info
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
In kernel/trace/trace.c (ffff800010228628)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffff8000102742ac)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffff8000102859b8)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffff8000103220b4)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffff800010327f94)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffff800010329804)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffff80001055be7c)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffff800010560fbc)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffff80001061fe78)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/block/xen-blkfront.c (ffff800010925dc8)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In net/core/bpf_sk_storage.c (ffff800010c3107c)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (c0465c70)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (c04a6938)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (c04b5f7c)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (c053a76c)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (c053f3b8)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (c0540148)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (c07105b8)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (c0715d14)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (c07c798c)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In net/core/bpf_sk_storage.c (c0d48654)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (c0000000002af0b0)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (c00000000031bf08)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (c000000000330848)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (c0000000003f7a60)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (c0000000003fef38)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (c0000000004001f4)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (c0000000006bb378)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (c0000000006c2354)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (c0000000007bf4c4)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In net/core/bpf_sk_storage.c (c000000000d2b2e0)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (ffffffe000182f74)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffe0001acbfc)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffe0001babba)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffe0002230f2)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffe000227d46)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffe000228ba0)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffe0003b2b9e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffe0003b8158)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffe00045260a)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7a0e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (ffffffff811a3e47)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811e913a)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811f6f3b)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff8127fb10)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81284ef6)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81285c45)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff8146537f)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8146a47e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81510ae3)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff816f4dfe)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In net/core/bpf_sk_storage.c (ffffffff8192985d)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (ffffffff81196e17)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811dbefa)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811e9c8b)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff812719b0)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81276d66)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81277ab5)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff81455daf)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8145aeae)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81500e03)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In net/core/bpf_sk_storage.c (ffffffff818e360d)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (ffffffff811a1c17)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811e6f0a)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff811f4d0b)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff8127d930)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81282d06)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81283a55)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff8146141f)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8146651e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff8150cb73)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff8172234e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a9ed)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
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
In kernel/trace/trace.c (ffffffff811af9a7)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811f52ba)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffff8120322b)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In mm/swap_state.c (ffffffff8128d4e0)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812929eb)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81293745)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In security/selinux/ss/avtab.c (ffffffff81478c1f)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8147dcfe)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81526253)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/block/xen-blkfront.c (ffffffff8173d78e)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cf1d)
Location: include/linux/mm.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
</details>
</li>
</ul>

## Differences
