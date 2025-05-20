# Function: <code>atomic_long_add_unless</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109665c)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (ffffffff812eda96)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffff8109cc1c)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (ffffffff812ff556)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffff810a3855)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff81178557)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117d453)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811830cb)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff812166ed)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff8125b39c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81276e82)
Location: include/asm-generic/atomic-long.h:489
Inline: True
```
```
In mm/memcontrol.c (ffffffff812fd9ed)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff99c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff8133882d)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8134e598)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/eventpoll.c (ffffffff8136cf16)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_loop_check_proc
```
```
In fs/io_uring.c (ffffffff8137fc3d)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/bio.c (ffffffff8153d9c2)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-mq.c (ffffffff8154f964)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81555541)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8156c004)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/fork.c (ffffffff8109f207)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff811752bf)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2bc)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8118005c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff81218626)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff81265509)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128175f)
Location: include/asm-generic/atomic-long.h:489
Inline: True
```
```
In mm/memcontrol.c (ffffffff81309e35)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8130bce9)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff813441c0)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8135b3bd)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8138e751)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/blk-mq.c (ffffffff8156bd4c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81571c0b)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81586d2c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bc37c9)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/fork.c (ffffffff810a00d7)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff81175e25)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae3c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b2c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff8121bdd9)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff81269718)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128660f)
Location: include/asm-generic/atomic-long.h:489
Inline: True
```
```
In mm/memcontrol.c (ffffffff813106a5)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff813122e9)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff8134a560)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff81361fbd)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8139ecc5)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-mq.c (ffffffff81573842)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81579c11)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8158db7c)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bb3e66)
Location: include/asm-generic/atomic-long.h:489
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/fork.c (ffffffff810b3237)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d412)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff811a2921)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a891c)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff81252cd9)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff812a61a0)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6159)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/memcontrol.c (ffffffff8135b9bb)
Location: include/linux/atomic/atomic-instrumented.h:1724
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
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff813982e3)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff813b081d)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff813eef69)
Location: include/linux/atomic/atomic-instrumented.h:1724
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
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815def59)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815f35eb)
Location: include/linux/atomic/atomic-instrumented.h:1724
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81c825a8)
Location: include/linux/atomic/atomic-instrumented.h:1724
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
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0547)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff811d3400)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b49)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812fee33)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813235d6)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff813a698b)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5ccc)
Location: include/linux/atomic/atomic-instrumented.h:1842
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
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814356ae)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff81684584)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8168d6c9)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff816a4bd5)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/io_uring.c (ffffffff816d6d66)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In net/mptcp/subflow.c (ffffffff81e282d7)
Location: include/linux/atomic/atomic-instrumented.h:1842
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
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213fe7)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff81217380)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121f019)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812c5ec3)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812f43b9)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_kptr_get
```
```
In kernel/bpf/memalloc.c (ffffffff8131bee4)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff813695b7)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff81382654)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
```
```
In mm/backing-dev.c (ffffffff81397e26)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff81427f6b)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b6b3)
Location: include/linux/atomic/atomic-instrumented.h:1842
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
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814c371b)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff817423af)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8174bec2)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81763964)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff8179b972)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff82000239)
Location: include/linux/atomic/atomic-instrumented.h:1842
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff81226817)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229917)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff8122cca0)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81235149)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812ece23)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81321557)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff8134c567)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff8139b757)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b41bd)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813cada6)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff8145c9ab)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
```
```
In mm/memcontrol.c (ffffffff81491323)
Location: include/linux/atomic/atomic-instrumented.h:4632
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
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814f8afe)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff81772ad9)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff8177f9d8)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817885e2)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817a29f4)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff817dcaa4)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff8207c40b)
Location: include/linux/atomic/atomic-instrumented.h:4632
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
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812422a9)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff81244d60)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed98)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff8130b5d3)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81343c87)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff81371ec3)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c56c7)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd83d)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813f5d86)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/workingset.c (ffffffff8140c44c)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/slub.c (ffffffff81454e85)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
```
```
In mm/zswap.c (ffffffff8147120c)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
```
```
In mm/memcontrol.c (ffffffff814c0c93)
Location: include/linux/atomic/atomic-instrumented.h:4632
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
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8152d35d)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff817b4e73)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff817c24b8)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817cacb2)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817e6537)
Location: include/linux/atomic/atomic-instrumented.h:4632
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff821518f2)
Location: include/linux/atomic/atomic-instrumented.h:4632
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1868)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (ffff8000103b0d80)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (c0350c30)
Location: include/asm-generic/atomic-long.h:982
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (c05908ec)
Location: include/asm-generic/atomic-long.h:982
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (c000000000136624)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (c0000000004ac3ac)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffe0000beef0)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
```
```
In fs/file.c (ffffffe000274de4)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffff8109653c)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (ffffffff812f7b36)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffff81084fbc)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (ffffffff812e8756)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffff810964ec)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (ffffffff812f5946)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffff8109e4b7)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (ffffffff8130730b)
Location: include/asm-generic/atomic-long.h:488
Inline: True
Inline callers:
  - fs/file.c:__fget
```
</details>
</li>
</ul>

## Differences
