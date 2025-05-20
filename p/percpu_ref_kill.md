# Function: <code>percpu_ref_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81115317)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_release_root
```
```
In mm/backing-dev.c (ffffffff811ae271)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In fs/aio.c (ffffffff8125b4f2)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff813c4eb8)
Location: include/linux/percpu-refcount.h:117
Inline: True
```
```
In block/partition-generic.c (ffffffff813cd252)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
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
In kernel/cgroup.c (ffffffff8111c329)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kill_sb
```
```
In mm/backing-dev.c (ffffffff811c762f)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In fs/aio.c (ffffffff812840e7)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff81409088)
Location: include/linux/percpu-refcount.h:117
Inline: True
```
```
In block/partition-generic.c (ffffffff81411692)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
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
In kernel/cgroup.c (ffffffff81124659)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kill_sb
```
```
In mm/backing-dev.c (ffffffff811d774f)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In fs/aio.c (ffffffff81297d57)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff81423a48)
Location: include/linux/percpu-refcount.h:117
Inline: True
```
```
In block/partition-generic.c (ffffffff8142ca22)
Location: include/linux/percpu-refcount.h:117
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
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
In kernel/cgroup/cgroup.c (ffffffff811234a2)
Location: include/linux/percpu-refcount.h:118
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In mm/backing-dev.c (ffffffff811e051f)
Location: include/linux/percpu-refcount.h:118
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In fs/aio.c (ffffffff812a5be9)
Location: include/linux/percpu-refcount.h:118
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff81430c49)
Location: include/linux/percpu-refcount.h:118
Inline: True
```
```
In block/partition-generic.c (ffffffff81439d32)
Location: include/linux/percpu-refcount.h:118
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
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
In kernel/cgroup/cgroup.c (ffffffff81133f4a)
Location: include/linux/percpu-refcount.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In mm/backing-dev.c (ffffffff811f650f)
Location: include/linux/percpu-refcount.h:119
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/hmm.c (ffffffff8126d0a6)
Location: include/linux/percpu-refcount.h:119
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_ref_kill
```
```
In fs/aio.c (ffffffff812c910b)
Location: include/linux/percpu-refcount.h:119
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff8145ba58)
Location: include/linux/percpu-refcount.h:119
Inline: True
```
```
In block/partition-generic.c (ffffffff81465d52)
Location: include/linux/percpu-refcount.h:119
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
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
In kernel/cgroup/cgroup.c (ffffffff8114264d)
Location: include/linux/percpu-refcount.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In mm/backing-dev.c (ffffffff812177ff)
Location: include/linux/percpu-refcount.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/hmm.c (ffffffff81291e65)
Location: include/linux/percpu-refcount.h:125
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_ref_kill
```
```
In fs/aio.c (ffffffff812f50fb)
Location: include/linux/percpu-refcount.h:125
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff8148e961)
Location: include/linux/percpu-refcount.h:125
Inline: True
```
```
In block/partition-generic.c (ffffffff8149973b)
Location: include/linux/percpu-refcount.h:125
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
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
In kernel/cgroup/cgroup.c (ffffffff8114e0cd)
Location: include/linux/percpu-refcount.h:126
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In mm/backing-dev.c (ffffffff8122a70f)
Location: include/linux/percpu-refcount.h:126
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/hmm.c (ffffffff812a6e35)
Location: include/linux/percpu-refcount.h:126
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_ref_kill
```
```
In fs/aio.c (ffffffff8130a1eb)
Location: include/linux/percpu-refcount.h:126
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff814a8281)
Location: include/linux/percpu-refcount.h:126
Inline: True
```
```
In block/partition-generic.c (ffffffff814b399b)
Location: include/linux/percpu-refcount.h:126
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff814c1ce1)
Location: include/linux/percpu-refcount.h:126
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff81159ea0)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffff811f8c9f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8123a383)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffff81240542)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (ffffffff812c23b5)
Location: include/linux/percpu-refcount.h:134
Inline: True
```
```
In fs/aio.c (ffffffff8132c058)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81331cf0)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffff814d6d25)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffffffff814e1f36)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff814f0396)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff81165b30)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffff81205ccf)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8124867f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffff8124eab2)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (ffffffff812d42e5)
Location: include/linux/percpu-refcount.h:134
Inline: True
```
```
In fs/aio.c (ffffffff8133eea4)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff813458b0)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffff814f00a5)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffffffff814fb2f6)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff81509843)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff81176caa)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffff8122d44f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8127683f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffff8127cd72)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (ffffffff8130a430)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff81378ddb)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8138147f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_sqe_files_unregister
```
```
In block/blk-mq.c (ffffffff8155056f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partitions/core.c (ffffffff8155d893)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partitions/core.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff81569c57)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff811739af)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/trampoline.c (ffffffff812223b0)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
```
```
In kernel/bpf/cgroup.c (ffffffff81235963)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8128113f)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/memcontrol.c (ffffffff8130367d)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/memremap.c (ffffffff81316495)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff81386b15)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8138f413)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_sqe_files_unregister
```
```
In block/blk-mq.c (ffffffff8156c98f)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/blk-cgroup.c (ffffffff81584567)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff8117457f)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/trampoline.c (ffffffff81226d40)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
```
```
In kernel/bpf/cgroup.c (ffffffff81239bb3)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8128626f)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/memcontrol.c (ffffffff8130a7c4)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In mm/memremap.c (ffffffff8131c6d4)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff8138df95)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8139e4b7)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_rsrc_node_switch
```
```
In block/blk-mq.c (ffffffff81574365)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/blk-cgroup.c (ffffffff8158b367)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff8119b619)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/trampoline.c (ffffffff8125ee40)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
```
```
In kernel/bpf/cgroup.c (ffffffff81274323)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812c54de)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/swapfile.c (ffffffff813166db)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memcontrol.c (ffffffff81355436)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In mm/memremap.c (ffffffff813699cd)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff813db7f9)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff813ee6c6)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffff815d88b5)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/blk-cgroup.c (ffffffff815f038e)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff811cb817)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/trampoline.c (ffffffff812a9430)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812c49c3)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81322bae)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/swapfile.c (ffffffff81381883)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memcontrol.c (ffffffff813c9c27)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In mm/memremap.c (ffffffff813e7169)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff8146164e)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff816850c9)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In block/blk-cgroup.c (ffffffff816a15de)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In io_uring/io_uring.c (ffffffff81e923a6)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
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
In kernel/cgroup/cgroup.c (ffffffff8120ec96)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/trampoline.c (ffffffff81308220)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81329e93)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8139736e)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/swapfile.c (ffffffff8140000d)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memcontrol.c (ffffffff8144edac)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/memremap.c (ffffffff8146edc6)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff814f160e)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff81743049)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8176044e)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In io_uring/io_uring.c (ffffffff8178a600)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In io_uring/rsrc.c (ffffffff817a0ee9)
Location: include/linux/percpu-refcount.h:147
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff812246a6)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/trampoline.c (ffffffff813370f0)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81359fd3)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff813ca2fe)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/swapfile.c (ffffffff81432ebc)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memcontrol.c (ffffffff814848dc)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/memremap.c (ffffffff814a3586)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff81528bae)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff8177e689)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8179f7c6)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In io_uring/io_uring.c (ffffffff817cb090)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In drivers/md/md.c (ffffffff81d5d77a)
Location: include/linux/percpu-refcount.h:147
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff8123c392)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/trampoline.c (ffffffff8135cf70)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81382b83)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff813f4c8e)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/swapfile.c (ffffffff8146c2dc)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memcontrol.c (ffffffff814b3dcc)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/memremap.c (ffffffff814d4426)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/aio.c (ffffffff8155dcae)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/blk-mq.c (ffffffff817c0d29)
Location: include/linux/percpu-refcount.h:147
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e3296)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In io_uring/io_uring.c (ffffffff8180dd7f)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In drivers/md/md.c (ffffffff81e0e4ac)
Location: include/linux/percpu-refcount.h:147
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_suspend
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
In kernel/cgroup/cgroup.c (ffff8000101d75e8)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffff80001028ef30)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffff8000102dd6d0)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffff8000102e4d70)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In fs/aio.c (ffff8000103faccc)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff800010403a80)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffff8000105ef01c)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffff8000105fd2e8)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffff80001060c614)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (c041a364)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (c04be78c)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (c0502b74)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (c0509a58)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In fs/aio.c (c05ceeb4)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c05d770c)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (c079b950)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (c07a81f4)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (c07b7d98)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (c000000000243eb4)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (c00000000033bae0)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (c00000000039cf18)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (c0000000003a68ec)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (c00000000046d8c0)
Location: include/linux/percpu-refcount.h:134
Inline: True
```
```
In fs/aio.c (c000000000502ab4)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c000000000510828)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (c000000000785b80)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (c000000000796ac4)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (c0000000007a9474)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffe000150766)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffe0001c20c0)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffe0001f5c24)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffe0001fb8f8)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In fs/aio.c (ffffffe0002aa708)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffe0002b1144)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffe00042e41c)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffffffe000438f30)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffe0004450b8)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff8115e150)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffff811fe2ef)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81240ccf)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffff81247102)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (ffffffff812cc8c5)
Location: include/linux/percpu-refcount.h:134
Inline: True
```
```
In fs/aio.c (ffffffff81337484)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8133de90)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffff814e8685)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffffffff814f38d6)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff81501e23)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff81151424)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffff811f103f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81233ccf)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffff8123a0b2)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (ffffffff812bd735)
Location: include/linux/percpu-refcount.h:134
Inline: True
```
```
In fs/aio.c (ffffffff813281b4)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8132eb50)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffff814d8bf5)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffffffff814e3de6)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff814f2333)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff8115bf20)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffff811fc0bf)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8123ea6f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffff81244ea2)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (ffffffff812ca6d5)
Location: include/linux/percpu-refcount.h:134
Inline: True
```
```
In fs/aio.c (ffffffff81334f54)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8133b960)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffff814e4715)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffffffff814ef966)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff814fdeb3)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
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
In kernel/cgroup/cgroup.c (ffffffff81169048)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/bpf/cgroup.c (ffffffff8120acdf)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8124e19f)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_kill
```
```
In mm/slab_common.c (ffffffff81254662)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_deactivate_after_rcu
```
```
In mm/memremap.c (ffffffff812db3d5)
Location: include/linux/percpu-refcount.h:134
Inline: True
```
```
In fs/aio.c (ffffffff81343852)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8134eb10)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In block/blk-mq.c (ffffffff814fcb75)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_freeze_queue_start
```
```
In block/partition-generic.c (ffffffff815089f6)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition
```
```
In block/blk-cgroup.c (ffffffff81517693)
Location: include/linux/percpu-refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
</details>
</li>
</ul>

## Differences
