# Function: <code>down_read_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810c9ef0)
Location: kernel/locking/rwsem.c:32
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/swapfile.c:unuse_mm
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/super.c:trylock_super
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
```
**Symbols:**

```
ffffffff810c9ef0-ffffffff810c9f15: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ce950)
Location: kernel/locking/rwsem.c:33
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/oom_kill.c:__oom_reap_task
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/swapfile.c:unuse_mm
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
```
**Symbols:**

```
ffffffff810ce950-ffffffff810ce98e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810d5590)
Location: kernel/locking/rwsem.c:33
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/swapfile.c:unuse_mm
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff810d5590-ffffffff810d55ce: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810d4560)
Location: kernel/locking/rwsem.c:34
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - kernel/sched/fair.c:task_numa_work
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/swapfile.c:unuse_mm
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff810d4560-ffffffff810d459e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810dc4c0)
Location: kernel/locking/rwsem.c:51
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - kernel/sched/fair.c:task_numa_work
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/swapfile.c:unuse_mm
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff810dc4c0-ffffffff810dc4fe: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810e4b00)
Location: kernel/locking/rwsem.c:51
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/swapfile.c:unuse_mm
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/super.c:trylock_super
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff810e4b00-ffffffff810e4b41: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f0010)
Location: kernel/locking/rwsem.c:51
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/swapfile.c:unuse_mm
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/super.c:trylock_super
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff810f0010-ffffffff810f0050: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f7ad0)
Location: kernel/locking/rwsem.c:1484
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff810f7ad0-ffffffff810f7b1e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81103900)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff81103900-ffffffff8110394e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110e450)
Location: kernel/locking/rwsem.c:1515
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff8110e450-ffffffff8110e49e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110b710)
Location: kernel/locking/rwsem.c:1390
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
```
**Symbols:**

```
ffffffff8110b710-ffffffff8110b75e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110d530)
Location: kernel/locking/rwsem.c:1390
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
```
**Symbols:**

```
ffffffff8110d530-ffffffff8110d57e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112cd80)
Location: kernel/locking/rwsem.c:1507
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:filemap_update_page
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
```
**Symbols:**

```
ffffffff8112cd80-ffffffff8112cdce: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114e020)
Location: kernel/locking/rwsem.c:1536
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:filemap_update_page
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/ksm.c:rmap_walk_ksm
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
```
**Symbols:**

```
ffffffff8114e020-ffffffff8114e083: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117cf80)
Location: kernel/locking/rwsem.c:1557
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:filemap_update_page
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/ksm.c:rmap_walk_ksm
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff8117cf80-ffffffff8117cff9: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118dc30)
Location: kernel/locking/rwsem.c:1557
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:filemap_update_page
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memory.c:print_vma_addr
  - mm/memory.c:lock_vma_under_rcu
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/ksm.c:rmap_walk_ksm
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff8118dc30-ffffffff8118dca9: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119c5e0)
Location: kernel/locking/rwsem.c:1563
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:filemap_update_page
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:walk_mm
  - mm/memory.c:print_vma_addr
  - mm/memory.c:lock_vma_under_rcu
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/ksm.c:rmap_walk_ksm
  - mm/memcontrol.c:mem_cgroup_move_charge
  - fs/super.c:super_cache_scan
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff8119c5e0-ffffffff8119c659: down_read_trylock (STB_GLOBAL)
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
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010168f48)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/arm64/mm/fault.c:do_page_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffff800010168f48-ffff800010168fd0: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b57bc)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/arm/mm/fault.c:do_page_fault
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
c03b57bc-c03b5840: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c1270)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
c0000000001c1270-c0000000001c12e4: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe00010a80c)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffe00010a80c-ffffffe00010a86c: down_read_trylock (STB_GLOBAL)
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
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fcc10)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff810fcc10-ffffffff810fcc5e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ece20)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff810ece20-ffffffff810ece6e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f9dd0)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff810f9dd0-ffffffff810f9e1e: down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int down_read_trylock(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81104f40)
Location: kernel/locking/rwsem.c:1518
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/oom_kill.c:oom_reaper
  - mm/memory.c:print_vma_addr
  - mm/memory.c:vm_insert_page
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_invalidate_range_start
  - fs/super.c:trylock_super
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff81104f40-ffffffff81104f8e: down_read_trylock (STB_GLOBAL)
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
