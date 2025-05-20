# Function: <code>atomic64_sub_return</code>

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
In mm/page_counter.c (ffffffff811f92d5)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812361bb)
Location: arch/x86/include/asm/atomic64_64.h:156
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
In kernel/locking/rwsem-xadd.c (ffffffff8189d8f0)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8121ce55)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8125fb35)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff818d27c0)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8122f455)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81273055)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff81909687)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8123acb6)
Location: arch/x86/include/asm/atomic64_64.h:156
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812804b9)
Location: arch/x86/include/asm/atomic64_64.h:156
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
In kernel/locking/rwsem-xadd.c (ffffffff81993677)
Location: arch/x86/include/asm/atomic64_64.h:157
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8125a546)
Location: arch/x86/include/asm/atomic64_64.h:157
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a2fe9)
Location: arch/x86/include/asm/atomic64_64.h:157
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
In kernel/locking/rwsem-xadd.c (ffffffff819efc45)
Location: include/asm-generic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8127e315)
Location: include/asm-generic/atomic-instrumented.h:262
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812c9a35)
Location: include/asm-generic/atomic-instrumented.h:262
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
In kernel/locking/rwsem-xadd.c (ffffffff81a2b675)
Location: include/asm-generic/atomic-instrumented.h:309
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff81292a05)
Location: include/asm-generic/atomic-instrumented.h:309
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812dec65)
Location: include/asm-generic/atomic-instrumented.h:309
Inline: True
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
In mm/page_counter.c (ffffffff812ad3c5)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fd316)
Location: include/asm-generic/atomic-instrumented.h:967
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
In mm/page_counter.c (ffffffff812bef15)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130f806)
Location: include/asm-generic/atomic-instrumented.h:967
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
In kernel/bpf/syscall.c (ffffffff811fc369)
Location: include/asm-generic/atomic-instrumented.h:968
Inline: True
```
```
In mm/page_counter.c (ffffffff812f4351)
Location: include/asm-generic/atomic-instrumented.h:968
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
```
```
In fs/fs-writeback.c (ffffffff81348f15)
Location: include/asm-generic/atomic-instrumented.h:968
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
In kernel/bpf/syscall.c (ffffffff811fb4bd)
Location: include/asm-generic/atomic-instrumented.h:968
Inline: True
```
```
In mm/page_counter.c (ffffffff812ffc41)
Location: include/asm-generic/atomic-instrumented.h:968
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
```
```
In fs/fs-writeback.c (ffffffff81355e78)
Location: include/asm-generic/atomic-instrumented.h:968
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
In kernel/bpf/syscall.c (ffffffff811fc1dd)
Location: include/asm-generic/atomic-instrumented.h:968
Inline: True
```
```
In mm/page_counter.c (ffffffff81306785)
Location: include/asm-generic/atomic-instrumented.h:968
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff8135ca58)
Location: include/asm-generic/atomic-instrumented.h:968
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122cd3d)
Location: include/linux/atomic/atomic-instrumented.h:701
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f0fd)
Location: include/linux/atomic/atomic-instrumented.h:747
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c497d)
Location: include/linux/atomic/atomic-instrumented.h:747
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eba5d)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309fad)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
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
In kernel/kthread.c (ffff8000101288f8)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In kernel/acct.c (ffff8000101c7f34)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d082c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca60)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de818)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfa00)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4acc)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/audit_tree.c (ffff8000101f550c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/arraymap.c (ffff80001027b8fc)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028ff58)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffff80001029c468)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffff8000102b7c90)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc748)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In mm/backing-dev.c (ffff8000102df660)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e783c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffff8000102f2794)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffff8000103466cc)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (ffff800010360a9c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In mm/memcontrol.c (ffff800010364cc8)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/memcontrol.c:percpu_ref_put_many
```
```
In mm/hugetlb_cgroup.c (ffff80001036d724)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In mm/hmm.c (ffff80001037b988)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffff80001038571c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In fs/inode.c (ffff8000103acee8)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffff8000103caaec)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffff8000103d92c8)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e1478)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f5c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffff8000103e93bc)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In fs/aio.c (ffff8000103fc564)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff800010405dc0)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db5dc)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In block/blk-core.c (ffff8000105e4184)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffff8000105e8858)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In block/blk-merge.c (ffff8000105eb908)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In block/blk-mq-sched.c (ffff8000105f71c4)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060ea38)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff800010611c50)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffff80001063559c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffff800010922318)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffff80001097831c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeab08)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In net/unix/scm.c (ffff800010cf548c)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001735a0)
Location: include/linux/atomic-fallback.h:1319
Inline: True
```
```
In kernel/cgroup/cgroup.c (c000000000246354)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a9d8)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c8d4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c00000000024e108)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c000000000255334)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (c000000000324b04)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c00000000033cc84)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c00000000034c1a4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c00000000036fb24)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c000000000374c84)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (c00000000037beb0)
Location: include/linux/atomic-fallback.h:1319
Inline: True
```
```
In mm/backing-dev.c (c00000000039f1f4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c0000000003a9630)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (c0000000003b7484)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (c0000000004246e4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (c00000000044bc10)
Location: include/linux/atomic-fallback.h:1319
Inline: True
```
```
In mm/memcontrol.c (c00000000045adc4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (c00000000045d8a4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (c0000000004618a0)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (c00000000046db50)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (c000000000470c1c)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (c00000000047bcb4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
```
```
In fs/inode.c (c0000000004a8734)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c0000000004cc624)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c0000000004dd330)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c0000000004e7474)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c0000000004efadc)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (c0000000005052f0)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c00000000050eb60)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c00000000076b73c)
Location: include/linux/atomic-fallback.h:1319
Inline: True
```
```
In block/blk-core.c (c000000000777ea4)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c000000000780f4c)
Location: include/linux/atomic-fallback.h:1319
Inline: True
```
```
In block/blk-mq-sched.c (c00000000078f7a0)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007ac030)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c0000000007afd44)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (c0000000007dafd0)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (c0000000009c7834)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (c000000000a1a260)
Location: include/linux/atomic-fallback.h:1319
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c000000000a327e0)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c000000000bd6f74)
Location: include/linux/atomic-fallback.h:1319
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffe0000df5ac)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In kernel/acct.c (ffffffe0001481d4)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffe000151e2c)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001546d2)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155b7e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffe000156a3e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffe00015aca8)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/audit_tree.c (ffffffe0001679b0)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/audit_tree.c:__put_chunk
```
```
In kernel/bpf/arraymap.c (ffffffe0001b30f4)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2b66)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffe0001d04c4)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In mm/oom_kill.c (ffffffe0001dbf14)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001df416)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In mm/backing-dev.c (ffffffe0001f73bc)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffe0001fd2da)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffe000204d60)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffe00023957c)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (ffffffe00024033c)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In mm/memcontrol.c (ffffffe000248b3e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a44e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffe00025214e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffe00025861e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In fs/inode.c (ffffffe000271cdc)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffe000288c6c)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffe000291e2a)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffe000297c88)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffe00029da1a)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/notify/mark.c (ffffffe00029dd4e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In fs/aio.c (ffffffe0002aa1cc)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffe0002b1042)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffe00041e49c)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In block/blk-core.c (ffffffe000425a7c)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffe0004293ae)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In block/blk-merge.c (ffffffe00042b8f8)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In block/blk-mq-sched.c (ffffffe0004348b4)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffe000446e60)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffe0004494b4)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffe000462f8e)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffe0005a0ffe)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfdb0)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffe0006de386)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In net/unix/scm.c (ffffffe000840f6a)
Location: arch/riscv/include/asm/atomic.h:141
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
In mm/page_counter.c (ffffffff812b74f5)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81307de6)
Location: include/asm-generic/atomic-instrumented.h:967
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
In mm/page_counter.c (ffffffff812a86c5)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812f8a06)
Location: include/asm-generic/atomic-instrumented.h:967
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
In mm/page_counter.c (ffffffff812b5305)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81305bd6)
Location: include/asm-generic/atomic-instrumented.h:967
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
In mm/page_counter.c (ffffffff812c5845)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81317116)
Location: include/asm-generic/atomic-instrumented.h:967
Inline: True
```
</details>
</li>
</ul>

## Differences
