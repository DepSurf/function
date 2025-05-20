# Function: <code>rcu_barrier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4cb0)
Location: kernel/rcu/tree_plugin.h:910
Inline: False
Direct callers:
  - mm/slab_common.c:release_caches
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/hugetlbfs/inode.c:exit_hugetlbfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - block/elevator.c:elv_unregister
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810e4cb0-ffffffff810e4cc7: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb050)
Location: kernel/rcu/tree_plugin.h:809
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - mm/slab_common.c:release_caches
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - block/elevator.c:elv_unregister
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810eb050-ffffffff810eb067: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2a10)
Location: kernel/rcu/tree_plugin.h:809
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - mm/slab_common.c:release_caches
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - block/elevator.c:elv_unregister
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810f2a10-ffffffff810f2a27: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4670)
Location: kernel/rcu/tree_plugin.h:875
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810f4670-ffffffff810f4687: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fe540)
Location: kernel/rcu/tree_plugin.h:891
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810fe540-ffffffff810fe557: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81105470)
Location: kernel/rcu/tree_plugin.h:931
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
**Symbols:**

```
ffffffff81105470-ffffffff81105487: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110b00)
Location: kernel/rcu/tree.c:3134
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
**Symbols:**

```
ffffffff81110b00-ffffffff81110c73: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111a550)
Location: kernel/rcu/tree.c:2821
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffff8111a550-ffffffff8111a6ec: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126950)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffff81126950-ffffffff81126af8: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811365c0)
Location: kernel/rcu/tree.c:3590
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffff811365c0-ffffffff8113676a: rcu_barrier.part.0 (STB_LOCAL)
ffffffff81136770-ffffffff811367d6: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131e30)
Location: kernel/rcu/tree.c:3900
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:netdev_wait_allrefs
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_free_fn
```
**Symbols:**

```
ffffffff81131e30-ffffffff81131fc0: rcu_barrier.part.0 (STB_LOCAL)
ffffffff81131fc0-ffffffff81132026: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811325c0)
Location: kernel/rcu/tree.c:4008
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_free_fn
```
**Symbols:**

```
ffffffff811325c0-ffffffff81132750: rcu_barrier.part.0 (STB_LOCAL)
ffffffff81132750-ffffffff811327b6: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81154320)
Location: kernel/rcu/tree.c:3979
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_free_fn
```
**Symbols:**

```
ffffffff81154320-ffffffff811544eb: rcu_barrier.part.0 (STB_LOCAL)
ffffffff811544f0-ffffffff81154556: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117a430)
Location: kernel/rcu/tree.c:4094
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_free_fn
```
**Symbols:**

```
ffffffff8117a430-ffffffff8117a702: rcu_barrier.part.0 (STB_LOCAL)
ffffffff8117a710-ffffffff8117a786: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b32e0)
Location: kernel/rcu/tree.c:3986
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:exit_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_free_fn
```
**Symbols:**

```
ffffffff811b32e0-ffffffff811b35d5: rcu_barrier.part.0 (STB_LOCAL)
ffffffff811b35f0-ffffffff811b3666: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c4e40)
Location: kernel/rcu/tree.c:3986
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:exit_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_free_fn
```
**Symbols:**

```
ffffffff811c4e40-ffffffff811c5135: rcu_barrier.part.0 (STB_LOCAL)
ffffffff811c5150-ffffffff811c51c6: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d7df0)
Location: kernel/rcu/tree.c:4058
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/rcu/tree.c:param_set_do_rcu_barrier
  - kernel/bpf/memalloc.c:destroy_mem_alloc
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
  - kernel/bpf/devmap.c:dev_map_free
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:exit_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_free_fn
```
**Symbols:**

```
ffffffff811d7df0-ffffffff811d80e5: rcu_barrier.part.0 (STB_LOCAL)
ffffffff811d8100-ffffffff811d8176: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018c398)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/workqueue.c:flush_rcu_work
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffff80001018c398-ffff80001018c5c0: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dd5d4)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
c03dd5d4-c03dd81c: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001eaba0)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - kernel/workqueue.c:flush_rcu_work
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
c0000000001eaba0-c0000000001eae48: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000121444)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - kernel/workqueue.c:flush_rcu_work
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffe000121444-ffffffe00012161a: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111ef30)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffff8111ef30-ffffffff8111f0d8: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110940)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffff81110940-ffffffff81110ae8: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111ce20)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/netfilter/nfnetlink_queue.c:nfnetlink_queue_fini
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_fini
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffff8111ce20-ffffffff8111cfc8: rcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112a3c0)
Location: kernel/rcu/tree.c:2886
Inline: True
Direct callers:
  - init/main.c:kernel_init
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/inode.c:fuse_fs_cleanup
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/dm-stats.c:dm_statistics_exit
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/ipv4/inet_fragment.c:fqdir_work_fn
```
**Symbols:**

```
ffffffff8112a3c0-ffffffff8112a568: rcu_barrier (STB_GLOBAL)
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
