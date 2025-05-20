# Function: <code>percpu_ref_tryget</code>

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
In kernel/cgroup.c (ffffffff811151dd)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kn_lock_live
```
```
In mm/page-writeback.c (ffffffff8119a5c0)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811af193)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fc91b)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
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
In kernel/cgroup.c (ffffffff81121796)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:cgroup_kn_lock_live
```
```
In mm/page-writeback.c (ffffffff811aeed0)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811c85b3)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8122053a)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In block/blk-mq.c (ffffffff81406e83)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
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
In kernel/cgroup.c (ffffffff81129d13)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:cgroup_kn_lock_live
```
```
In mm/page-writeback.c (ffffffff811bf580)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811d86e3)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff81232c9c)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In block/blk-mq.c (ffffffff814213b3)
Location: include/linux/percpu-refcount.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
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
In kernel/cgroup/cgroup.c (ffffffff81128add)
Location: include/linux/percpu-refcount.h:205
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In mm/page-writeback.c (ffffffff811c72c2)
Location: include/linux/percpu-refcount.h:205
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811e194b)
Location: include/linux/percpu-refcount.h:205
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8123e4b6)
Location: include/linux/percpu-refcount.h:205
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In block/blk-mq.c (ffffffff8142fcc3)
Location: include/linux/percpu-refcount.h:205
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
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
In kernel/cgroup/cgroup.c (ffffffff8113513c)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In mm/page-writeback.c (ffffffff811dc0d2)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811f799b)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8125e056)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In block/blk-mq.c (ffffffff8145b603)
Location: include/linux/percpu-refcount.h:206
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
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
In kernel/cgroup/cgroup.c (ffffffff81143863)
Location: include/linux/percpu-refcount.h:212
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In mm/page-writeback.c (ffffffff811fda98)
Location: include/linux/percpu-refcount.h:212
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81218eb0)
Location: include/linux/percpu-refcount.h:212
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff81282385)
Location: include/linux/percpu-refcount.h:212
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In block/blk-mq.c (ffffffff8148f17c)
Location: include/linux/percpu-refcount.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
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
In kernel/cgroup/cgroup.c (ffffffff8114f383)
Location: include/linux/percpu-refcount.h:213
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In mm/page-writeback.c (ffffffff812105c1)
Location: include/linux/percpu-refcount.h:213
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8122bcea)
Location: include/linux/percpu-refcount.h:213
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff81296562)
Location: include/linux/percpu-refcount.h:213
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In block/bio.c (ffffffff81498132)
Location: include/linux/percpu-refcount.h:213
Inline: True
```
```
In block/blk-mq.c (ffffffff814a7a8c)
Location: include/linux/percpu-refcount.h:213
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ad253)
Location: include/linux/percpu-refcount.h:213
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814c3285)
Location: include/linux/percpu-refcount.h:213
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffff8115b1fe)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbfc)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81165503)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8121fc51)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123b7d3)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff812b538e)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In fs/fs-writeback.c (ffffffff8130030b)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff813304ba)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqe
```
```
In block/bio.c (ffffffff814c5fd2)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffffffff814d5afc)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814db4c4)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f1954)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffff81166ead)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8116b85c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811713f3)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8122d701)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81248c50)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c702e)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9e54)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81314b24)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff81343cd6)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814de3d2)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffffffff814eee2c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814f48f4)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8150af49)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffff81178587)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117d48c)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81183103)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8125b34d)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81276ead)
Location: include/linux/percpu-refcount.h:251
Inline: True
```
```
In mm/memcontrol.c (ffffffff812fd9df)
Location: include/linux/percpu-refcount.h:251
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
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8134e513)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8137fc12)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
```
```
In block/bio.c (ffffffff8153d9ac)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-mq.c (ffffffff8154f8f7)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815552b1)
Location: include/linux/percpu-refcount.h:251
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8156bfd6)
Location: include/linux/percpu-refcount.h:251
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2f8)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180097)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812654bb)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81281788)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In mm/memcontrol.c (ffffffff81309e12)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8135b436)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8138e718)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
```
```
In block/blk-mq.c (ffffffff8156bcd7)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81571961)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81586ceb)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bc37af)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae78)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b67)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812696ca)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81286638)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In mm/memcontrol.c (ffffffff81310682)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81362036)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8139ea1b)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-mq.c (ffffffff815737b2)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815799a4)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8158da31)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bb3e4c)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff811a295d)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8957)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812a6152)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6113)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/memcontrol.c (ffffffff8135b99d)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff813b0865)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff813eeb73)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-mq.c (ffffffff815d7da6)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815deca4)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815f34a1)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81c8258e)
Location: include/linux/percpu-refcount.h:264
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
In kernel/cgroup/cgroup.c (ffffffff811cd763)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d04ec)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff811d33be)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9aea)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812feddb)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8132358b)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff813a6921)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5c7f)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8143563f)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff816844f4)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8168d002)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff816a4a1d)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/io_uring.c (ffffffff81e9036b)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_show_fdinfo
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In net/mptcp/subflow.c (ffffffff81e282b8)
Location: include/linux/percpu-refcount.h:264
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
In kernel/cgroup/cgroup.c (ffffffff81210df3)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213f8c)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff8121733e)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121efba)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812c5ea5)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812f4387)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_kptr_get
```
```
In kernel/bpf/memalloc.c (ffffffff8131bea5)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff81369564)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813825f2)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
```
```
In mm/backing-dev.c (ffffffff81397ddb)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff81427f01)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b666)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814c36ac)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-mq.c (ffffffff8174231f)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8174b822)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817637ad)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff8179b926)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff8200021a)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812298bc)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff8122cc5e)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff812350ea)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff812ece05)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81321528)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff8134c522)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/page-writeback.c (ffffffff8139b704)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b4190)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813cad5b)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slub.c (ffffffff8145c941)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In mm/memcontrol.c (ffffffff814912d6)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814f8a8f)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff81772a18)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff8177f963)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81787f42)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817a284e)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In io_uring/fdinfo.c (ffffffff817dca56)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In net/mptcp/subflow.c (ffffffff8207c3ce)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124228d)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/rdma.c (ffffffff81244d1e)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed35)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/syscall.c (ffffffff8130b5b5)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81343c58)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff81371ea5)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c5674)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd810)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813f5d3b)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/workingset.c (ffffffff8140c3ed)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/slub.c (ffffffff81454e48)
Location: include/linux/percpu-refcount.h:264
Inline: True
```
```
In mm/zswap.c (ffffffff81471088)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
```
```
In mm/memcontrol.c (ffffffff814c0c46)
Location: include/linux/percpu-refcount.h:264
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
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8152d2ee)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff817b4db5)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
```
```
In block/blk-mq.c (ffffffff817c2443)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817ca612)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817e6390)
Location: include/linux/percpu-refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff821518a6)
Location: include/linux/percpu-refcount.h:264
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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool percpu_ref_tryget(struct percpu_ref *ref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8d6c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffff8000101dfba0)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4a68)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffff8000102bc660)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffff8000102de498)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (ffff800010369e10)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
Direct callers:
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffff80001036d6f4)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffff8000103caa90)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffff800010405a88)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db780)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffff8000105ef678)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffff8000105f4738)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffff80001060e860)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffff800010364a38-ffff800010364ad8: percpu_ref_tryget (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (c041bb34)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (c04214e4)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c0425890)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (c04e8d08)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (c05036f4)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (c055b17c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In fs/fs-writeback.c (c05a7034)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (c05d7234)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c078835c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-mq.c (c079aeb4)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (c07a0364)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (c07b906c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (c0000000002461e0)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (c00000000024e2d0)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c0000000002552f0)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (c000000000374b90)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (c00000000039d820)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (c0000000004589e8)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (c00000000045d860)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (c0000000004cc580)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (c00000000050e738)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c00000000076b690)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (c000000000783d68)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (c00000000078c014)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (c0000000007abdb0)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffe000151d1a)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffe000156b8a)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffe00015ac6e)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffe0001df326)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffe0001f61ae)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (ffffffe000247672)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a412)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffe000288c20)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffe0002b0d78)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffe00041e422)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffffffe00042d436)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffe0004326d0)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffe000446cec)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffff8115f4cd)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff81163e7c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81169a13)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81225d51)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812412a0)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bf60e)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c2434)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8130d104)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8133c2b6)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d69b2)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffffffff814e740c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814eced4)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81503529)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffff8115275d)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff811570cc)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cc13)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81218ef1)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812342a0)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b06ee)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3484)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812fdd14)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8132cf86)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814c7372)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffffffff814d797c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814dd424)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f39e9)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffff8115d29d)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff81161c4c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811677e3)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81223af1)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123f040)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bd41e)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c0244)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8130aef4)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff81339d86)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d2a42)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffffffff814e349c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814e8f64)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814ff5b9)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/cgroup/cgroup.c (ffffffff8116a462)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0ae)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174e5a)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81232e72)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8124eb7f)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In mm/memcontrol.c (ffffffff812cdc9f)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0d1a)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8131c64c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8134d750)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814eb57a)
Location: include/linux/percpu-refcount.h:221
Inline: True
```
```
In block/blk-mq.c (ffffffff814fc38c)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81501f04)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8151873e)
Location: include/linux/percpu-refcount.h:221
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
