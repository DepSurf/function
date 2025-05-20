# Function: <code>percpu_ref_tryget_many</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81178587)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117d48c)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81183103)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8125b34d)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81276ead)
Location: include/linux/percpu-refcount.h:222
Inline: True
```
```
In mm/memcontrol.c (ffffffff812fd9df)
Location: include/linux/percpu-refcount.h:222
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
In mm/hugetlb_cgroup.c (ffffffff812ff9d6)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8134e513)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8137fc12)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/bio.c (ffffffff8153d9ac)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-mq.c (ffffffff8154f8f7)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815552b1)
Location: include/linux/percpu-refcount.h:222
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8156bfd6)
Location: include/linux/percpu-refcount.h:222
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
In kernel/cgroup/cgroup.c (ffffffff811752fb)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2f8)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180097)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812654bb)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81281788)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In mm/memcontrol.c (ffffffff81309e12)
Location: include/linux/percpu-refcount.h:235
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
In mm/hugetlb_cgroup.c (ffffffff8130bd35)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8135b436)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8138e718)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/blk-mq.c (ffffffff8156bcd7)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81571961)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81586ceb)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bc37af)
Location: include/linux/percpu-refcount.h:235
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
In kernel/cgroup/cgroup.c (ffffffff81175e64)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae78)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b67)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812696ca)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81286638)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In mm/memcontrol.c (ffffffff81310682)
Location: include/linux/percpu-refcount.h:235
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
In mm/hugetlb_cgroup.c (ffffffff81312335)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81362036)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8139ea1b)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-mq.c (ffffffff815737b2)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815799a4)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8158da31)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bb3e4c)
Location: include/linux/percpu-refcount.h:235
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
In kernel/cgroup/cgroup.c (ffffffff8119d451)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff811a295d)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8957)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812a6152)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6113)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/memcontrol.c (ffffffff8135b99d)
Location: include/linux/percpu-refcount.h:235
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
In mm/hugetlb_cgroup.c (ffffffff8135dc77)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff813b0865)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff813eeb73)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-mq.c (ffffffff815d7da6)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815deca4)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815f34a1)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81c8258e)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd763)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d04ec)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff811d33be)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9aea)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812feddb)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8132358b)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff813a6921)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5c7f)
Location: include/linux/percpu-refcount.h:235
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
In mm/hugetlb_cgroup.c (ffffffff813d7cc4)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8143563f)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff816844f4)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8168d002)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff816a4a1d)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/io_uring.c (ffffffff816d69bb)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
Direct callers:
  - io_uring/io_uring.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff81e282b8)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff816ca260-ffffffff816ca2b6: percpu_ref_tryget_many.constprop.0 (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff81210df3)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213f8c)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff8121733e)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121efba)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812c5ea5)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812f4387)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_kptr_get
```
```
In kernel/bpf/memalloc.c (ffffffff8131bea5)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff81369564)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813825f2)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
```
```
In mm/backing-dev.c (ffffffff81397ddb)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff81427f01)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b666)
Location: include/linux/percpu-refcount.h:235
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
In mm/hugetlb_cgroup.c (ffffffff8145db32)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814c36ac)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff8174231f)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8174b822)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817637ad)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff8179b926)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff8200021a)
Location: include/linux/percpu-refcount.h:235
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
In kernel/cgroup/cgroup.c (ffffffff812267e3)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812298bc)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff8122cc5e)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff812350ea)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812ece05)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81321528)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff8134c522)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff8139b704)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b4190)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813cad5b)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff8145c941)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In mm/memcontrol.c (ffffffff814912d6)
Location: include/linux/percpu-refcount.h:235
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
In mm/hugetlb_cgroup.c (ffffffff81493822)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814f8a8f)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff81772a18)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff8177f963)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81787f42)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817a284e)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff817dca56)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff8207c3ce)
Location: include/linux/percpu-refcount.h:235
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
In kernel/cgroup/cgroup.c (ffffffff8123e473)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124228d)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff81244d1e)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed35)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff8130b5b5)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81343c58)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff81371ea5)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c5674)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd810)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813f5d3b)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/workingset.c (ffffffff8140c3ed)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/slub.c (ffffffff81454e48)
Location: include/linux/percpu-refcount.h:235
Inline: True
```
```
In mm/zswap.c (ffffffff81471088)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
```
```
In mm/memcontrol.c (ffffffff814c0c46)
Location: include/linux/percpu-refcount.h:235
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
In mm/hugetlb_cgroup.c (ffffffff814c315d)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8152d2ee)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff817b4db5)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff817c2443)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817ca612)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817e6390)
Location: include/linux/percpu-refcount.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff821518a6)
Location: include/linux/percpu-refcount.h:235
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
