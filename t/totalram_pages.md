# Function: <code>totalram_pages</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int totalram_pages();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052a95)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff81096596)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff828ad2c6)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/kexec_core.c (ffffffff81142641)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff81205451)
Location: include/linux/mm.h:52
Inline: True
```
```
In mm/page_alloc.c (ffffffff828b9b74)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/swap.c (ffffffff828ba043)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff81225809)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/util.c (ffffffff812279a0)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffff81a253b6)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff828bd8d6)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff81257639)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/zswap.c (ffffffff81264b9c)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff828c0ae4)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff828c24ac)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff81332915)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff828cc8cf)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/xen/xen-selfballoon.c (ffffffff8161caa7)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:selfballoon_process
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/char/agp/backend.c (ffffffff8166cf02)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (ffffffff81840485)
Location: include/linux/mm.h:52
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194335f)
Location: include/linux/mm.h:52
Inline: True
```
**Symbols:**

```
ffffffff812065d0-ffffffff812065d8: totalram_pages (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055c45)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff8109aad6)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff828c5c65)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/kexec_core.c (ffffffff8114da4a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff8121c40d)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffffffff828d1464)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff812329c9)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/util.c (ffffffff812377c8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffff81a9513d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff828d4ed0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff8126a419)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff828d6c8d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff8127f7bc)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff828d9e6f)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff828db87a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff8135a8a5)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff828e623e)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/char/agp/backend.c (ffffffff816a2b10)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (ffffffff81883346)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7903)
Location: include/linux/mm.h:53
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056585)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff828ca67a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff828ce2a9)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/kexec_core.c (ffffffff8115975a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff81229ddd)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffffffff828d98e2)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff81240a6d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff81245a18)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffff81acca1d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff828dd35f)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff81279329)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff828df11e)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff8128f5ac)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff828e2316)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff828e3cb0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff81372ab5)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff828eed04)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/char/agp/backend.c (ffffffff816c58a0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (ffffffff818b51e6)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de993)
Location: include/linux/mm.h:53
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b974)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff82cecc15)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff82cef6c7)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff82cf16eb)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff8116ab12)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff812556f6)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff82cf8934)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff81271a2d)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8127374a)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff81bc537e)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff82cfa7e4)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff812ac558)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff82cfc507)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff812c224b)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff82cff6f0)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff82d007f1)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff813badf5)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff8147d2cc)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
```
```
In drivers/char/agp/backend.c (ffffffff8177a095)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff81984f32)
Location: include/linux/mm.h:56
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb6c3)
Location: include/linux/mm.h:56
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a3c4)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff82fd926f)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff82fdbdf2)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff82fde13f)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff81167252)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff81260376)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff82fe562d)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff81278973)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8127dfda)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff81282b42)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff82fe74e0)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff812b7a88)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff82fe8f22)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff812cdf44)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff82fec09c)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff82fed1b6)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff813cc945)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff814984dc)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
```
```
In drivers/char/agp/backend.c (ffffffff81794755)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff81988fd2)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7663)
Location: include/linux/mm.h:61
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105ad64)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff831e3ae8)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff831e6b55)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff831e8c73)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff81167fe2)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff81265055)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff831efd06)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff8127d923)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8128314a)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff81287c73)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff831f1c02)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff812bd4a6)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff831f3766)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff812d45e4)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff831f68fb)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff831f79e7)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff813d3905)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff8149d70c)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
```
```
In drivers/char/agp/backend.c (ffffffff81777425)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff8196d6b2)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/inetpeer.c (ffffffff83227a0a)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2795)
Location: include/linux/mm.h:61
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810642a4)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff832c7613)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff832cacf0)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff832cd189)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff8118d9da)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff812a1885)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff832d547c)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff812bbc65)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff812c130a)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff812c7413)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff832d77a3)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff812ffc66)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff832d99a2)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff8131a906)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff832dd411)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff832de929)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff81424eb5)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff814f515c)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
```
```
In drivers/char/agp/backend.c (ffffffff817fd1c5)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff81a15c82)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/inetpeer.c (ffffffff83311dd0)
Location: include/linux/mm.h:61
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b805f8)
Location: include/linux/mm.h:61
Inline: True
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
In kernel/fork.c (ffffffff8347a48d)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff8347e2c8)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff83480cc8)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff811bceca)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff812f9745)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff83489ca7)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff81317365)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8131e2ea)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff81324763)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff8348c342)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff81366e83)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff8348e949)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff81385f6b)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff83492c3f)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff83494264)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff8149dc25)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff815850a6)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
```
```
In drivers/char/agp/backend.c (ffffffff8193c125)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff81b7e682)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/inetpeer.c (ffffffff834cbcd2)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1097f)
Location: include/linux/mm.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
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
In kernel/fork.c (ffffffff83ea4c86)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff83eaa105)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff83ead9c8)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff811fee8a)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff81363325)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff83eba4e5)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff8138bd45)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff81391d5a)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff83ebacb7)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/workingset.c (ffffffff83ebd685)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff813e2d23)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff83ec0ba4)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff81403d9b)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff83ec6b6a)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff83ec8875)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff815328b5)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff83ecec44)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
```
```
In security/integrity/ima/ima_kexec.c (ffffffff81700fa8)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In drivers/char/agp/backend.c (ffffffff81a9c9e5)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff81d1c792)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/inetpeer.c (ffffffff83f0e3c5)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed66df)
Location: include/linux/mm.h:55
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
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
In kernel/fork.c (ffffffff836c9006)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff836cf0c5)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff836d29a8)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff8121428a)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff81395775)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff836dfaf5)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff813be299)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff813c475a)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff836e317e)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/show_mem.c (ffffffff813dda45)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/show_mem.c:si_meminfo
```
```
In mm/workingset.c (ffffffff836e5b45)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff81417983)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/zswap.c (ffffffff81436bfa)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:shrink_worker
```
```
In mm/huge_memory.c (ffffffff836ebb5a)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff836ed8e5)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff8156aaa5)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff836f3cd4)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
```
```
In security/integrity/ima/ima_kexec.c (ffffffff8173b048)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In drivers/char/agp/backend.c (ffffffff81ae8345)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff81d85972)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/inetpeer.c (ffffffff837349d5)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3564b)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_net_metrics_init
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
In kernel/fork.c (ffffffff838f9c66)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff839004d5)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/dma/pool.c (ffffffff83904768)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffffffff8122c1da)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff813bf535)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/swap.c (ffffffff83912375)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff813e72f8)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff813ef1da)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (ffffffff83915a0e)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/show_mem.c (ffffffff81407915)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/show_mem.c:si_meminfo
```
```
In mm/workingset.c (ffffffff83918385)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff814444d3)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
```
```
In mm/zswap.c (ffffffff81470745)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
```
```
In mm/huge_memory.c (ffffffff8391ebdf)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff83920945)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff815a3485)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff83926ea4)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
```
```
In security/integrity/ima/ima_kexec.c (ffffffff8177bbb8)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In drivers/char/agp/backend.c (ffffffff81b3b7b5)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_initialize
```
```
In drivers/md/dm-stats.c (ffffffff81e3d0b2)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In net/ipv4/inetpeer.c (ffffffff83968f95)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_initpeers
```
```
In net/ipv4/tcp_metrics.c (ffffffff83969917)
Location: include/linux/mm.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
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
In kernel/fork.c (ffff800011441bec)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/kexec_core.c (ffff8000101c8da0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffff8000102b7d20)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffff8000114524dc)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffff8000102d2710)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffff8000102d90a4)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffff800010d9f93c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffff800011455eb4)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffff80001030fd84)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffff800011457ecc)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffff80001032bf50)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffff80001145b4e0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffff80001145d2b0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffff80001043d12c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffff800011468868)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/md/dm-stats.c (ffff800010b0cfc8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91b18)
Location: include/linux/mm.h:53
Inline: True
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
In kernel/fork.c (c151bbc8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (c151ff68)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/kexec_core.c (c040fc18)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (c04e5270)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (c152d084)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (c04f9e5c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (c0500230)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/mm_init.c (c152e4c8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/workingset.c (c1530f2c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (c052c290)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (c1531e4c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (c054227c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/file_table.c (c1535798)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (c0602f98)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (c154122c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/md/dm-stats.c (c0bea5d8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (c0da082c)
Location: include/linux/mm.h:53
Inline: True
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
In kernel/fork.c (c0000000013655b8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/kexec_core.c (c0000000002314e8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (c00000000036fbb8)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (c00000000137a4f8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (c00000000039007c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (c000000000398bf0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (c000000000eec238)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (c00000000137edf0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (c0000000003e0fec)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (c000000001381668)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (c000000000402b04)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (c000000001385c2c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (c000000001387ab8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (c000000000551014)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (c00000000139664c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In security/integrity/ima/ima_kexec.c (c000000000738454)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
```
In drivers/char/agp/backend.c (c00000000095218c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (c000000000bff7f8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (c000000000da208c)
Location: include/linux/mm.h:53
Inline: True
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
In kernel/fork.c (ffffffe0000042a4)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In mm/oom_kill.c (ffffffe0001dc71e)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffffffe000011a34)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffe0001ef40a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffe0001f34ba)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffe000012ab2)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/workingset.c (ffffffe000014e1c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffe0002182dc)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffe0000167dc)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffe00022ab86)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/file_table.c (ffffffe00001a25c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffe0002d5ab0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffe000023b16)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/md/dm-stats.c (ffffffe0006fa690)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1bc8)
Location: include/linux/mm.h:53
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056105)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff828b346d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/kexec_core.c (ffffffff81151d7a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff8122242d)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffffffff828c2793)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff812390bd)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8123e068)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffff81a6b88d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff828c6213)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff81271979)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff828c7fd2)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff81287b8c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff828cb1ca)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff828ccb64)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff8136b095)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff828d7bb8)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/char/agp/backend.c (ffffffff8168b2f0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (ffffffff8185b066)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e803)
Location: include/linux/mm.h:53
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046315)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff828ab5ee)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff828af22c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/kexec_core.c (ffffffff8114505a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff812155dd)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffffffff828baebb)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff8122c0fd)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff81231068)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffff81a27dd4)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff828be938)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff812638e9)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff828c06f7)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff812799ec)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff828c38ef)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff828c5280)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff8135bb25)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff828d02d4)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/char/agp/backend.c (ffffffff81668cf0)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (ffffffff81822646)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819382c3)
Location: include/linux/mm.h:53
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056535)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff828c636c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff828c9edd)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/kexec_core.c (ffffffff8114fc2a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff812201cd)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffffffff828d5516)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff81236e5d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8123be08)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffff81ad7c9d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff828d8f93)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff8126f719)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff828dad52)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff8128599c)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff828ddf4a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff828df8e4)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff81368b65)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff828ea938)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/char/agp/backend.c (ffffffff816b9560)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (ffffffff818aa696)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a08e5)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8fd3)
Location: include/linux/mm.h:53
Inline: True
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057a85)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
```
In kernel/fork.c (ffffffff828cb6b7)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/power/snapshot.c (ffffffff828cf28f)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_image_size_init
```
```
In kernel/kexec_core.c (ffffffff8115ca8a)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In mm/oom_kill.c (ffffffff8122f2ed)
Location: include/linux/mm.h:53
Inline: True
```
```
In mm/swap.c (ffffffff828da937)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/swap.c:swap_setup
```
```
In mm/shmem.c (ffffffff8124450d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_parse_one
```
```
In mm/util.c (ffffffff8124b518)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:vm_commit_limit
```
```
In mm/mm_init.c (ffffffff81ae415d)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/workingset.c (ffffffff828de3b4)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/vmalloc.c (ffffffff8127f129)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
```
```
In mm/page_alloc.c (ffffffff828e0173)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:si_meminfo
```
```
In mm/zswap.c (ffffffff812956bc)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/huge_memory.c (ffffffff828e3361)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In fs/file_table.c (ffffffff828e4cfb)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/base.c (ffffffff8137c1e5)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/fuse/inode.c (ffffffff828efd4e)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
```
In drivers/char/agp/backend.c (ffffffff816d3b30)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/md/dm-stats.c (ffffffff818c5eaf)
Location: include/linux/mm.h:53
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2d33)
Location: include/linux/mm.h:53
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
