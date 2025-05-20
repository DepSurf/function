# Function: <code>arch_atomic_long_add_unless</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3237)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d412)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff811a2921)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a891c)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff81252cd9)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff812a61a0)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6159)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/memcontrol.c (ffffffff8135b9bb)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8135dc2b)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff813982e3)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff813b081d)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff813eef69)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-mq.c (ffffffff815d7e45)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815def59)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815f35eb)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81c825a8)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff811cd797)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0547)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff811d3400)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b49)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812fee33)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813235d6)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff813a698b)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5ccc)
Location: include/linux/atomic/atomic-long.h:489
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
In mm/hugetlb_cgroup.c (ffffffff813d7d2e)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814356ae)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff81684584)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8168d6c9)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff816a4bd5)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/io_uring.c (ffffffff816d6d66)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In net/mptcp/subflow.c (ffffffff81e282d7)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff81210e27)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213fe7)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff81217380)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121f019)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812c5ec3)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812f43b9)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_kptr_get
```
```
In kernel/bpf/memalloc.c (ffffffff8131bee4)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff813695b7)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff81382654)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
```
```
In mm/backing-dev.c (ffffffff81397e26)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff81427f6b)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b6b3)
Location: include/linux/atomic/atomic-long.h:489
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
In mm/hugetlb_cgroup.c (ffffffff8145db9c)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814c371b)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff817423af)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8174bec2)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81763964)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff8179b972)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff82000239)
Location: include/linux/atomic/atomic-long.h:489
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
