# Function: <code>kvmalloc_array</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81272eed)
Location: include/linux/mm.h:535
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In ipc/sem.c (ffffffff813882ac)
Location: include/linux/mm.h:535
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In lib/iov_iter.c (ffffffff81468aec)
Location: include/linux/mm.h:535
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ece4)
Location: include/linux/mm.h:535
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
Location: include/linux/mm.h:552
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In fs/file.c (ffffffff8129581d)
Location: include/linux/mm.h:552
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In ipc/sem.c (ffffffff813ace2b)
Location: include/linux/mm.h:552
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In lib/iov_iter.c (ffffffff81494d9c)
Location: include/linux/mm.h:552
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In drivers/net/tun.c (ffffffff81702492)
Location: include/linux/mm.h:552
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_attach
```
```
In net/sched/sch_api.c (ffffffff8187c368)
Location: include/linux/mm.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dc94)
Location: include/linux/mm.h:552
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/bpf/btf.c (ffffffff811c8ebf)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/cpumap.c (ffffffff811ca7a9)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff8124829f)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8124db3b)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8124e7c5)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff812bb99d)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/super.c (ffffffff813898f9)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/sem.c (ffffffff813dbb1e)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In block/blk-zoned.c (ffffffff814b8103)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff814c5f5b)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff814cdd13)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - lib/bucket_locks.c:alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff815d56d3)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/net/tun.c (ffffffff817411d0)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818bd91a)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818cc3b7)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff818ceb85)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f18bc)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/btf.c (ffffffff811dc0b8)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
```
```
In kernel/bpf/cpumap.c (ffffffff811de0d5)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff8125c870)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81261f5c)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81262ca5)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff812d0b8d)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/ext4/super.c (ffffffff813a24a0)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff813dc9ce)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff813f6198)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In block/blk-zoned.c (ffffffff814cc061)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff814da76e)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff814e25e3)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff815eee83)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/net/tun.c (ffffffff817652c7)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818e4c5d)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818f75d7)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff818f9e85)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f49c)
Location: include/linux/mm.h:615
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811f37a1)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff81277a50)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8127ce47)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8127dbf5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff812edbbf)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff813317fe)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffff813ccdb0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff81408502)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81422550)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff81452fff)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814580fe)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff814fa5a3)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff81505d70)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff8150e499)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff81620c90)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff81676bd5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f5467)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8170ab8e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/net/tun.c (ffffffff8179e74d)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819344ba)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8195363f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff81956cc5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff819595e5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81981dfb)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (ffffffff81167d8f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811ab827)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811f0b1a)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff81200541)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff81287540)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8128c916)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8128d665)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff812ff67f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8134543e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffff813e628c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff81422782)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff8143c326)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff8146cd9f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81471e9e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81518503)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff81523d50)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff8152c3b9)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff81642770)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff81699375)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719867)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8172ee8e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/net/tun.c (ffffffff817c21dd)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819670ea)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff819899ed)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff8198d165)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff8198fa85)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b864b)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (ffffffff81179b8d)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811c3c7b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff812131bf)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/btf.c (ffffffff8121f87a)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
  - kernel/bpf/btf.c:env_resolve_init
```
```
In kernel/bpf/cpumap.c (ffffffff81227fd0)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/swap_state.c (ffffffff812b9d8b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812bf7b1)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff812c0115)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff8133866f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8137f464)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffff8143338a)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff81471939)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff8148ca5b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff814c156f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814c7063)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff8158103f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff81587334)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff8158fd29)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff816efb9f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff8174b735)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d59a7)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff817ece48)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848eeb)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff8188a871)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3a459)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61704)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff81a646ae)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81a68605)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa2f6b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9b8a)
Location: include/linux/mm.h:764
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
In kernel/cgroup/cgroup-v1.c (ffffffff811768fd)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811c188b)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff812149a8)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/btf.c (ffffffff8122ac5a)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff8122e802)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81230428)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In mm/swap_state.c (ffffffff812c57fb)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812cb34e)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff812cbb75)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff81343fff)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8138d910)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff813b9729)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/ext4/super.c (ffffffff8144c1ae)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff8148c1a9)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff814aa0bb)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff814df0b5)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_duplicate
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814e5101)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff8159e05f)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff815a4b10)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff815ac899)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff8170cf7f)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff81766e45)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea3b7)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81801778)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859a32)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81898a71)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffffffff81a3c9e9)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81a6c7ee)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81a70d15)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad49b)
Location: include/linux/mm.h:792
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9105)
Location: include/linux/mm.h:792
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f7cb)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117730c)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811c28c2)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff811f96cc)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff812171fc)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/hashtab.c (ffffffff8121e81e)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81225a09)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff8122f59a)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
```
```
In kernel/bpf/cpumap.c (ffffffff812336d8)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/swap_state.c (ffffffff812cc4cb)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812d1ee5)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff812d2725)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff8134a39f)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8139190b)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_rsrc_data_alloc
```
```
In fs/coredump.c (ffffffff813c0887)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/ext4/super.c (ffffffff81451aad)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff81491aa9)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff814b09a3)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff814e5ac7)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff814eba6d)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff815a4daf)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff815ae1e1)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff815b7505)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff816ee5da)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff8174aa85)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ceab7)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff817e6316)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c772)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff8187b1b1)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/md/dm-table.c (ffffffff81965e93)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/core/page_pool.c (ffffffff81a2393d)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81a54f91)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81a59665)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98577)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8115)
Location: include/linux/mm.h:815
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0c43)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119ea7c)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811ed5a2)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/core.c (ffffffff8122ad7c)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff8124da1d)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/hashtab.c (ffffffff81254e0e)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125da12)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff812682fa)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_metas
```
```
In kernel/bpf/cpumap.c (ffffffff8126d35a)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/swap_state.c (ffffffff813116b5)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81317674)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81318025)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff8139810c)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff813df80b)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_files_register
```
```
In fs/coredump.c (ffffffff814106f7)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/ext4/super.c (ffffffff814a511d)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff814e9599)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81509afb)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff8153f1c7)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81545546)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/keyslot-manager.c (ffffffff8160d823)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_init
  - block/keyslot-manager.c:blk_ksm_init
```
```
In lib/iov_iter.c (ffffffff81615ad8)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff8161db35)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff817686ba)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff817cc345)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff818591c7)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff818726bc)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c90d2)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff8190c9b1)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/md/dm-zone.c (ffffffff81a059f8)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81a0de85)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/core/page_pool.c (ffffffff81ad7f6d)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff81b0dcd1)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81b12715)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53a54)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f4c)
Location: include/linux/mm.h:816
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75d65)
Location: include/linux/mm.h:816
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810c6a73)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf23b)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff81225770)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff8125a01c)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff8126c6f5)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff812949be)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/hashtab.c (ffffffff8129e054)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7d63)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff812b562a)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff812bc492)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/swap_state.c (ffffffff8137c7e5)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81382d7d)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff813836b5)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff8141a876)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/coredump.c (ffffffff81484986)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/ext4/super.c (ffffffff8152d0b2)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff81577d1b)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff8159b78e)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff815d6e66)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff815ddfac)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff81632728)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff816c2118)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff816ca058)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_pin_pages
  - io_uring/io_uring.c:io_sqe_files_register
```
```
In lib/iov_iter.c (ffffffff816e26fa)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff816eb6f3)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff81ea4979)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f047)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/apei/erst.c (ffffffff8189ce8b)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff81909cd5)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196bf25)
Location: include/linux/slab.h:761
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199fccd)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba867)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a16655)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81a612a1)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/md/dm-zone.c (ffffffff81b6d6b0)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81b765ba)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/core/page_pool.c (ffffffff81c58ce9)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81c950dd)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81c999f5)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81cb457e)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce15a6)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/xdp/xdp_umem.c (ffffffff81e18f35)
Location: include/linux/slab.h:761
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a5cf)
Location: include/linux/slab.h:761
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3a09)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212bcb)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/relay.c (ffffffff8124b892)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff812709b0)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff812aa33b)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff812c17b5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/verifier.c (ffffffff812ef59d)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/hashtab.c (ffffffff812fbc73)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813063e8)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff81315c5a)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff8131f9aa)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/swap_state.c (ffffffff813f9fb5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff813fcce4)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff814010e5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff814a6606)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/coredump.c (ffffffff81517e92)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/ext4/super.c (ffffffff815c9329)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
```
```
In fs/fuse/dev.c (ffffffff8161d24b)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81644aee)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff81685316)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8168cc58)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff816e7508)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff81783418)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/filetable.c (ffffffff817940f6)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In io_uring/rsrc.c (ffffffff817a21b8)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
  - io_uring/rsrc.c:io_pin_pages
```
```
In lib/iov_iter.c (ffffffff817d2ab6)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages
```
```
In lib/bucket_locks.c (ffffffff817dbe33)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff8189ef61)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193dd47)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/apei/erst.c (ffffffff819e5b1b)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff81a643e5)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6300)
Location: include/linux/slab.h:748
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b117bd)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2fd87)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97465)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81bec5e6)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/md/dm-zone.c (ffffffff81d09a5e)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81d13990)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/core/page_pool.c (ffffffff81e0ebd9)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81e50bdd)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81e55d15)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81e727fe)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2656)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/unix/af_unix.c (ffffffff81f49467)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0318)
Location: include/linux/slab.h:748
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1af0)
Location: include/linux/slab.h:748
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810ef286)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/dma/remap.c (ffffffff811d887a)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_common_contiguous_remap
```
```
In kernel/module/decompress.c (ffffffff811e1975)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_extend_max_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812284db)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/relay.c (ffffffff81262b12)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff81287c80)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff812ccaaa)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff812e861d)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff812f0781)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
```
```
In kernel/bpf/verifier.c (ffffffff8131beb7)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/hashtab.c (ffffffff8132a525)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/btf.c (ffffffff81345c26)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff8134f9aa)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/swap_state.c (ffffffff8142cef5)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff8142ffc1)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81433fc5)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff814db5c1)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/verity/open.c (ffffffff8153ce5b)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/coredump.c (ffffffff8154f78c)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/ext4/super.c (ffffffff816010e8)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
```
```
In fs/fuse/dev.c (ffffffff816553ab)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff8167cfb6)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff816bd689)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff816c4f62)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff81720c54)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_perms
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff817c3774)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff817c9385)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uaddr_map
```
```
In io_uring/filetable.c (ffffffff817d4dd6)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In io_uring/rsrc.c (ffffffff817e32d8)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In lib/iov_iter.c (ffffffff8181466d)
Location: include/linux/slab.h:731
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
In lib/bucket_locks.c (ffffffff8181b1f2)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff818e1427)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982127)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/apei/erst.c (ffffffff81a2e14e)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff81aaea95)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b24aa5)
Location: include/linux/slab.h:731
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5fa5a)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81b831e1)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81beda2e)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/net/tun.c (ffffffff81c449c3)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/md/dm-zone.c (ffffffff81d727c4)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81d7caf0)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/core/page_pool.c (ffffffff81e82260)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81eac3fb)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81eb15b5)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81ece98a)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00e76)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/udp.c (ffffffff81f3fd95)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
```
```
In net/unix/af_unix.c (ffffffff81fa9047)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4c3)
Location: include/linux/slab.h:731
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206dcee)
Location: include/linux/slab.h:731
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810f8546)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/resource.c (ffffffff8110bf50)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/resource.c:walk_system_ram_res_rev
```
```
In kernel/dma/remap.c (ffffffff811ee38a)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_common_contiguous_remap
```
```
In kernel/module/decompress.c (ffffffff811f76d5)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_extend_max_pages
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812402dc)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/relay.c (ffffffff8127cd32)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff812a2f90)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea405)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
```
In kernel/bpf/core.c (ffffffff8130698d)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
```
```
In kernel/bpf/syscall.c (ffffffff8130f561)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
```
```
In kernel/bpf/verifier.c (ffffffff8133e26f)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
```
In kernel/bpf/hashtab.c (ffffffff8134e9ed)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/btf.c (ffffffff8136bbb6)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff81376eba)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In mm/swap_state.c (ffffffff81466605)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81469a58)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff8146d3c5)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff8150dbc1)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/verity/open.c (ffffffff815722bb)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_create_info
```
```
In fs/coredump.c (ffffffff815855cb)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/ext4/super.c (ffffffff81639e38)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
```
```
In fs/fuse/dev.c (ffffffff8168e11b)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff816b9386)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff816fa019)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc_dup
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff81701ba3)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In security/apparmor/policy_compat.c (ffffffff8175f7b9)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - security/apparmor/policy_compat.c:aa_compat_map_policy
  - security/apparmor/policy_compat.c:aa_compat_map_xmatch
  - security/apparmor/policy_compat.c:compute_fperms
```
```
In block/blk-crypto-profile.c (ffffffff81808404)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In io_uring/io_uring.c (ffffffff818109e0)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uaddr_map
```
```
In io_uring/filetable.c (ffffffff81818c26)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - io_uring/filetable.c:io_alloc_file_tables
```
```
In io_uring/rsrc.c (ffffffff81827394)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In lib/iov_iter.c (ffffffff8185966e)
Location: include/linux/slab.h:739
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
In lib/bucket_locks.c (ffffffff81860532)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/stackdepot.c (ffffffff8192806f)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_init
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9937)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_init
```
```
In drivers/acpi/apei/erst.c (ffffffff81a793be)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
```
```
In drivers/tty/vt/consolemap.c (ffffffff81b01785)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b715)
Location: include/linux/slab.h:739
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb346a)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7108)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:negotiate_mq
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c43160)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c729)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
```
```
In drivers/net/tun.c (ffffffff81cfa523)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/md/dm-zone.c (ffffffff81e29854)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
```
```
In drivers/md/dm-table.c (ffffffff81e33fd0)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_create
```
```
In net/core/page_pool.c (ffffffff81f4323f)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/sched/sch_generic.c (ffffffff81f6ee8b)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81f74065)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_init
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/bpf/test_run.c (ffffffff81f921ba)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc51d6)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/udp.c (ffffffff82005a55)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
```
```
In net/unix/af_unix.c (ffffffff82076547)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
  - net/unix/af_unix.c:unix_net_init
```
```
In net/xdp/xdp_umem.c (ffffffff821402c1)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141d6d)
Location: include/linux/slab.h:739
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
In kernel/cgroup/cgroup-v1.c (ffff8000101da8a8)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffff800010228628)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffff8000102742ac)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffff800010288818)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffff8000103220b4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffff800010327f94)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffff800010329804)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffff8000103b0b90)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffff800010403600)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffff8000104bf56c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffff800010505540)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffff800010524170)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffff80001055be7c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffff800010560fbc)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffff80001061fe78)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffff80001062de6c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffff800010638320)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffff8000107ad930)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffff80001086ffe4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffff80001090cea0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffff800010925dc8)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/net/tun.c (ffff8000109dc8b8)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
```
```
In net/core/page_pool.c (ffff800010c0c764)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffff800010c3107c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffff800010c37a48)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffff800010c3ba10)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffff800010c698e4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (c041d1dc)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/trace/trace.c (c0465c70)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (c04a6938)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (c04b7db8)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (c053a76c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (c053f3b8)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (c0540148)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (c0590458)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (c05d6d44)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (c068318c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (c06c1920)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (c06def40)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (c07105b8)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (c0715d14)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (c07c798c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (c07d4cc4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (c07ddc50)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/tty/vt/consolemap.c (c097335c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (c09f5fcc)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/net/tun.c (c0ac6ec0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (c0d24e2c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (c0d48654)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (c0d4ad3c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (c0d4d8a4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (c0d78d44)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (c000000000248920)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (c0000000002af0b0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (c00000000031bf08)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (c000000000333d38)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (c0000000003f7a60)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (c0000000003fef38)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (c0000000004001f4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (c0000000004ac584)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (c000000000510234)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (c0000000005f5c20)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (c00000000064aa24)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (c00000000066e5e0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (c0000000006bb378)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (c0000000006c2354)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (c0000000007bf4c4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (c0000000007d1514)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (c0000000007de5cc)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/tty/vt/consolemap.c (c00000000090ffb0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (c0000000009ad0f0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/net/tun.c (c000000000a9efa4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (c000000000cf7e90)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (c000000000d2b2e0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (c000000000d305c0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (c000000000d35280)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e688)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (ffffffe000152e66)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffe000182f74)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffe0001acbfc)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc9ae)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffe0002230f2)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffe000227d46)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffe000228ba0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffe000274fba)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffe0002adf38)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffe00033a848)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffe000371efc)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffe000388f96)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffe0003b2b9e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffe0003b8158)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffe00045260a)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffe00045da8a)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffe00046510e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/tty/vt/consolemap.c (ffffffe000542554)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffe000591ba6)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/net/tun.c (ffffffe000627dc4)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffe000789b16)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7a0e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffe0007a9b38)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffe0007ac6c8)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf8e2)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (ffffffff811603af)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811a3e47)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811e913a)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811f8b61)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff8127fb10)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81284ef6)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81285c45)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff812f7c5f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8133da1e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffff813de86c)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff8141ad62)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81434906)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff8146537f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8146a47e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81510ae3)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff8151c330)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff81524999)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/tty/vt/consolemap.c (ffffffff8165edd5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff816dfb97)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff816f4dfe)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/net/tun.c (ffffffff81786cad)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819070ba)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8192985d)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff8192cfd5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff8192f8f5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819584bb)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115361f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff81196e17)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811dbefa)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811eb8b1)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff812719b0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81276d66)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81277ab5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff812e887f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8132e6de)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffff813cf2ec)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff8140b7e2)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81425386)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff81455daf)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8145aeae)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81500e03)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff8150c620)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff81514c79)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff815feb80)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff8163f155)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba1d7)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/net/tun.c (ffffffff817665fd)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff818c0eca)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff818e360d)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff818e6ad5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff818e93f5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81911fab)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115e17f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811a1c17)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811e6f0a)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff811f6931)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff8127d930)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff81282d06)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81283a55)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff812f5a6f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8133b4ee)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffff813dbc29)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff81416f02)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81430aa6)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff8146141f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8146651e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff8150cb73)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff815183c0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff81520a29)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff816365b0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff8168d1b5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d2b7)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8172234e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/net/tun.c (ffffffff817b705d)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff819580ea)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a9ed)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff8197e165)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff81980a85)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ce95)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_alloc_hashtable
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2c8b)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116b5af)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/trace/trace.c (ffffffff811af9a7)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/trace/trace.c:set_tracer_flag
```
```
In kernel/bpf/verifier.c (ffffffff811f52ba)
Location: include/linux/mm.h:681
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
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
```
In kernel/bpf/cpumap.c (ffffffff81205561)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/swap_state.c (ffffffff8128d4e0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/swapfile.c (ffffffff812929eb)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/swap_slots.c (ffffffff81293745)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - mm/swap_slots.c:alloc_swap_slot_cache
  - mm/swap_slots.c:alloc_swap_slot_cache
```
```
In fs/file.c (ffffffff81306baf)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/io_uring.c (ffffffff8134e69e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/super.c (ffffffff813f0fd9)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fuse/dev.c (ffffffff8142dc92)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In ipc/sem.c (ffffffff81447101)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
```
In security/selinux/ss/avtab.c (ffffffff81478c1f)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In security/selinux/ss/policydb.c (ffffffff8147dcfe)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:policydb_index
```
```
In block/blk-zoned.c (ffffffff81526253)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffffffff81531c40)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In lib/bucket_locks.c (ffffffff8153a3a9)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/acpi/apei/erst.c (ffffffff816508c0)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
```
```
In drivers/tty/vt/consolemap.c (ffffffff816a77b5)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/base/firmware_loader/main.c (ffffffff81727ed7)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/xen-blkfront.c (ffffffff8173d78e)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/net/tun.c (ffffffff817d12ad)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In net/core/page_pool.c (ffffffff8197a1fa)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cf1d)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (ffffffff819a0965)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:pfifo_fast_init
```
```
In net/sched/sch_api.c (ffffffff819a3005)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc75b)
Location: include/linux/mm.h:681
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
</details>
</li>
</ul>

## Differences
