# Function: <code>raw_atomic_long_add_unless</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81226817)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229917)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff8122cca0)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81235149)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812ece23)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81321557)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff8134c567)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff8139b757)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b41bd)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813cada6)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff8145c9ab)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
```
```
In mm/memcontrol.c (ffffffff81491323)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8149388c)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814f8afe)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff81772ad9)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff8177f9d8)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817885e2)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817a29f4)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff817dcaa4)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff8207c40b)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff8123e4a7)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812422a9)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff81244d60)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed98)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff8130b5d3)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81343c87)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff81371ec3)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c56c7)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd83d)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813f5d86)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/workingset.c (ffffffff8140c44c)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/slub.c (ffffffff81454e85)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
```
```
In mm/zswap.c (ffffffff8147120c)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
```
```
In mm/memcontrol.c (ffffffff814c0c93)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_current
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff814c31fe)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8152d35d)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff817b4e73)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff817c24b8)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817cacb2)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817e6537)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff821518f2)
Location: include/linux/atomic/atomic-long.h:1708
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
