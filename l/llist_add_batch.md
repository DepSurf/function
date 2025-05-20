# Function: <code>llist_add_batch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff813fe060)
Location: lib/llist.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:smp_call_function_many
  - kernel/irq_work.c:irq_work_queue_on
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff813fe060-ffffffff813fe07f: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff814456c0)
Location: lib/llist.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff814456c0-ffffffff814456df: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff81463eb0)
Location: lib/llist.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff81463eb0-ffffffff81463ecf: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff81468f40)
Location: lib/llist.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff81468f40-ffffffff81468f5f: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff81495210)
Location: lib/llist.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff81495210-ffffffff8149522f: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff814ca5f0)
Location: lib/llist.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff814ca5f0-ffffffff814ca60f: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff814df310)
Location: lib/llist.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff814df310-ffffffff814df32f: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff8150b170)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff8150b170-ffffffff8150b18a: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff81528f90)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff81528f90-ffffffff81528faa: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff8158c840)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/hugetlb.c:free_huge_page
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:io_file_data_ref_zero
  - fs/io_uring.c:io_file_data_ref_zero
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:alloc_dev_data
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8158c840-ffffffff8158c85a: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff815a92b0)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/hugetlb.c:free_huge_page
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:io_file_data_ref_zero
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:alloc_dev_data
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff815a92b0-ffffffff815a92ca: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff815b3eb0)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:io_rsrc_node_ref_zero
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff815b3eb0-ffffffff815b3eca: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff8161a0b0)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:io_rsrc_node_ref_zero
  - fs/io_uring.c:io_req_task_work_add
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8161a0b0-ffffffff8161a0ca: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff816e7670)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/module/main.c:do_init_module
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:__irq_work_queue_local
  - kernel/irq_work.c:__irq_work_queue_local
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - fs/namespace.c:mntput_no_expire
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
  - io_uring/io_uring.c:io_rsrc_node_ref_zero
  - io_uring/io_uring.c:__io_req_task_work_add
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff816e7670-ffffffff816e7696: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff817d74b0)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/module/main.c:do_init_module
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:__irq_work_queue_local
  - kernel/irq_work.c:__irq_work_queue_local
  - kernel/bpf/memalloc.c:unit_free
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - fs/namespace.c:mntput_no_expire
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff817d74b0-ffffffff817d74d3: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff818166c0)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/module/main.c:do_init_module
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
  - kernel/bpf/memalloc.c:unit_free
  - mm/vmalloc.c:vfree_atomic
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - fs/namespace.c:mntput_no_expire
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_fallback_tw
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff818166c0-ffffffff818166e3: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff8185b800)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/module/main.c:do_init_module
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
  - kernel/bpf/memalloc.c:unit_free_rcu
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:__free_by_rcu
  - mm/vmalloc.c:vfree_atomic
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - fs/namespace.c:mntput_no_expire
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_fallback_tw
  - drivers/tty/tty_buffer.c:tty_buffer_free
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/gpu/drm/drm_connector.c:__drm_connector_put_safe
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8185b800-ffffffff8185b823: llist_add_batch (STB_GLOBAL)
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
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffff800010633920)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffff800010633920-ffff80001063396c: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (c07d9cb4)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
c07d9cb4-c07d9d00: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (c0000000007d8c80)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
c0000000007d8c80-c0000000007d8cb8: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffe000461918)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffe000461918-ffffffe000461942: llist_add_batch (STB_GLOBAL)
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
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff81521570)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff81521570-ffffffff8152158a: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff81511860)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff81511860-ffffffff8151187a: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff8151d600)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff8151d600-ffffffff8151d61a: llist_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node *new_first, struct llist_node *new_last, struct llist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/llist.c (ffffffff81536e70)
Location: lib/llist.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
  - kernel/sched/core.c:try_to_wake_up
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
  - kernel/module.c:do_init_module
  - kernel/irq_work.c:irq_work_queue_on
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/namespace.c:mntput_no_expire
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
**Symbols:**

```
ffffffff81536e70-ffffffff81536e8a: llist_add_batch (STB_GLOBAL)
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
