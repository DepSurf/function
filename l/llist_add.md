# Function: <code>llist_add</code>

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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81046e82)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
```
```
In kernel/sched/core.c (ffffffff810abc3d)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff81103867)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/irq_work.c (ffffffff81170dc1)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff811cee53)
Location: include/linux/llist.h:178
Inline: True
```
```
In fs/file_table.c (ffffffff8120e39b)
Location: include/linux/llist.h:178
Inline: True
```
```
In fs/namespace.c (ffffffff8122cf9f)
Location: include/linux/llist.h:178
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b6752)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/tty_buffer.c (ffffffff814ea669)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81047092)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810ae884)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff8110b14b)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8117e4ba)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff811ea246)
Location: include/linux/llist.h:178
Inline: True
```
```
In fs/file_table.c (ffffffff81234dba)
Location: include/linux/llist.h:178
Inline: True
```
```
In fs/namespace.c (ffffffff8125572f)
Location: include/linux/llist.h:178
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81506000)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/tty_buffer.c (ffffffff8153b639)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81048c16)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810b49cb)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff81112b2f)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8118a0ca)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff811fd44c)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/file_table.c (ffffffff8124796a)
Location: include/linux/llist.h:178
Inline: True
```
```
In fs/namespace.c (ffffffff81268b1f)
Location: include/linux/llist.h:178
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152a200)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/tty_buffer.c (ffffffff81567cc6)
Location: include/linux/llist.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff810485a6)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810b0af3)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff8111401f)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8118cc1e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff8120811c)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/file_table.c (ffffffff8125319a)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/namespace.c (ffffffff812762d1)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c9c6)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8157b26e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104bfd6)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810b7f3f)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff8111f5a8)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8119a840)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff812211fc)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/file_table.c (ffffffff8127529a)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/namespace.c (ffffffff81298c20)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f4d6)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff815dfc7e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104ed57)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810bfaa1)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff8112c8d2)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811b027e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff812430ac)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/file_table.c (ffffffff8129bb2a)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/namespace.c (ffffffff812bee0f)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d72de)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/tty_buffer.c (ffffffff81618efc)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166ac3c)
Location: include/linux/llist.h:219
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81886c0a)
Location: include/linux/llist.h:219
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104c427)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810c8e0e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff811381a2)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811be896)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff812577bc)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/file_table.c (ffffffff812b0e5a)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/namespace.c (ffffffff812d40df)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0a22)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8163610c)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff81689341)
Location: include/linux/llist.h:219
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818a72fa)
Location: include/linux/llist.h:219
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104f33c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810d095d)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff81143357)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff811486ac)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811ce448)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff812697a4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/file_table.c (ffffffff812cd87e)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffff812f111e)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/acpi/apei/ghes.c (ffffffff81622716)
Location: include/linux/llist.h:207
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a344)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff816c0622)
Location: include/linux/llist.h:207
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818f2a4a)
Location: include/linux/llist.h:207
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fcbc)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810da90c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff8114ee97)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff8115452c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811daa68)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff812786e4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffffffff81292f02)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (ffffffff812df29e)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffff81302cbe)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/acpi/apei/ghes.c (ffffffff816441f6)
Location: include/linux/llist.h:207
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8168ca29)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e364f)
Location: include/linux/llist.h:207
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819249aa)
Location: include/linux/llist.h:207
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810541c0)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/smp.c (ffffffff8115f837)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff81165d27)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811f739a)
Location: include/linux/llist.h:207
Inline: True
```
```
In mm/vmalloc.c (ffffffff812ac4e2)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffffffff812c67b2)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In fs/file_table.c (ffffffff813160fe)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffff8133c675)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff8137bb4d)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_data_ref_zero
```
```
In ipc/namespace.c (ffffffff81494ff7)
Location: include/linux/llist.h:207
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f2285)
Location: include/linux/llist.h:207
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ea59)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff8179581c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_dev_data
```
```
In net/core/net_namespace.c (ffffffff819f8d4a)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81053120)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff8112f7c5)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/smp.c (ffffffff8115b7d7)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff8116244f)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811f5f0a)
Location: include/linux/llist.h:217
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b7557)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/hugetlb.c (ffffffff812d23b2)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In fs/file_table.c (ffffffff81321295)
Location: include/linux/llist.h:217
Inline: True
```
```
In fs/namespace.c (ffffffff81348522)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff81389d61)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_data_ref_zero
```
```
In ipc/namespace.c (ffffffff814b2a17)
Location: include/linux/llist.h:217
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f645)
Location: include/linux/llist.h:217
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8175a9a9)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a3d9c)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_dev_data
```
```
In net/core/net_namespace.c (ffffffff819f8820)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/ipv4/inet_fragment.c (ffffffff81b022c6)
Location: include/linux/llist.h:217
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81054a10)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff8112fb55)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/smp.c (ffffffff8115c8b8)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff81162f0f)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811f6dfa)
Location: include/linux/llist.h:217
Inline: True
```
```
In mm/vmalloc.c (ffffffff812bce27)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In fs/file_table.c (ffffffff813276fe)
Location: include/linux/llist.h:217
Inline: True
```
```
In fs/namespace.c (ffffffff8134e8ed)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff81390c29)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_node_ref_zero
```
```
In ipc/namespace.c (ffffffff814b8897)
Location: include/linux/llist.h:217
Inline: True
```
```
In block/blk-mq.c (ffffffff81573e30)
Location: include/linux/llist.h:217
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f29)
Location: include/linux/llist.h:217
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173e84f)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff81787fb9)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In net/core/net_namespace.c (ffffffff819df050)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedbd6)
Location: include/linux/llist.h:217
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105d360)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff811513e3)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/smp.c (ffffffff81181a24)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff8118847e)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff812283ca)
Location: include/linux/llist.h:217
Inline: True
```
```
In mm/vmalloc.c (ffffffff812ff597)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/hugetlb.c (ffffffff8131d959)
Location: include/linux/llist.h:217
Inline: True
```
```
In fs/file_table.c (ffffffff81374cfe)
Location: include/linux/llist.h:217
Inline: True
```
```
In fs/namespace.c (ffffffff8139c930)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff813de5dd)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_node_ref_zero
  - fs/io_uring.c:io_req_task_work_add
```
```
In ipc/namespace.c (ffffffff815110c7)
Location: include/linux/llist.h:217
Inline: True
```
```
In block/blk-mq.c (ffffffff815d8303)
Location: include/linux/llist.h:217
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176b039)
Location: include/linux/llist.h:217
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff817befcf)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180eb89)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In net/core/net_namespace.c (ffffffff81a8f430)
Location: include/linux/llist.h:217
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/ipv4/inet_fragment.c (ffffffff81badf86)
Location: include/linux/llist.h:217
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81069890)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff81179633)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/module/main.c (ffffffff8118e537)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/smp.c (ffffffff811b8081)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff812693dd)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/irq_work.c:__irq_work_queue_local
```
```
In mm/vmalloc.c (ffffffff813666d6)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/hugetlb.c (ffffffff81388f09)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/file_table.c (ffffffff813f368a)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/namespace.c (ffffffff8141f82a)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In ipc/namespace.c (ffffffff815a32f1)
Location: include/linux/llist.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff81685aeb)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
```
```
In io_uring/io_uring.c (ffffffff81e8f23e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_node_ref_zero
  - io_uring/io_uring.c:__io_req_task_work_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189fc19)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff818fb4ba)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff81950bcf)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In net/core/net_namespace.c (ffffffff81c0529a)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/ipv4/inet_fragment.c (ffffffff81d410a6)
Location: include/linux/llist.h:219
Inline: True
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81079570)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff811b1aca)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/module/main.c (ffffffff811caedf)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/smp.c (ffffffff811f931e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff812be23d)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/irq_work.c:__irq_work_queue_local
```
```
In kernel/bpf/memalloc.c (ffffffff8131ba06)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
```
```
In mm/vmalloc.c (ffffffff813e2306)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/hugetlb.c (ffffffff81407719)
Location: include/linux/llist.h:219
Inline: True
```
```
In mm/memory-failure.c (ffffffff81463d4d)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In fs/file_table.c (ffffffff8147c44a)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/namespace.c (ffffffff814abd5d)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In ipc/namespace.c (ffffffff8164cec1)
Location: include/linux/llist.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff81743927)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
```
```
In block/blk-cgroup.c (ffffffff81763bf5)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In io_uring/io_uring.c (ffffffff8178dde4)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:io_fallback_tw
```
```
In io_uring/rsrc.c (ffffffff817a01e7)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8ff9)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a5471a)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab547f)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In net/core/net_namespace.c (ffffffff81db4b2a)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09e46)
Location: include/linux/llist.h:219
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b820)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff811c38f1)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kvfree_rcu_bulk
```
```
In kernel/module/main.c (ffffffff811de243)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/smp.c (ffffffff8120dfdd)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/irq_work.c (ffffffff812e4e01)
Location: include/linux/llist.h:219
Inline: True
```
```
In kernel/bpf/memalloc.c (ffffffff8134b446)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
```
```
In mm/vmalloc.c (ffffffff81416edc)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/hugetlb.c (ffffffff8143a849)
Location: include/linux/llist.h:219
Inline: True
```
```
In mm/memory-failure.c (ffffffff8149989e)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In fs/file_table.c (ffffffff814b0fca)
Location: include/linux/llist.h:219
Inline: True
```
```
In fs/namespace.c (ffffffff814e0b1d)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In ipc/namespace.c (ffffffff81685401)
Location: include/linux/llist.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff8177f5ed)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
```
```
In block/blk-cgroup.c (ffffffff817a2c8b)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In io_uring/io_uring.c (ffffffff817cbc8a)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_fallback_tw
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a31709)
Location: include/linux/llist.h:219
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9ecfa)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b015cf)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In net/core/net_namespace.c (ffffffff81e251ca)
Location: include/linux/llist.h:219
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69956)
Location: include/linux/llist.h:219
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082ce0)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff811d38f1)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kvfree_rcu_bulk
```
```
In kernel/module/main.c (ffffffff811f3f72)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/smp.c (ffffffff8122576d)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/irq_work.c (ffffffff81302eb1)
Location: include/linux/llist.h:246
Inline: True
```
```
In kernel/bpf/memalloc.c (ffffffff81371e16)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free_rcu
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In mm/vmalloc.c (ffffffff81443c3c)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/hugetlb.c (ffffffff81473a09)
Location: include/linux/llist.h:246
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c9043)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In fs/file_table.c (ffffffff814e2793)
Location: include/linux/llist.h:246
Inline: True
```
```
In fs/namespace.c (ffffffff81514bed)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In ipc/namespace.c (ffffffff816c1821)
Location: include/linux/llist.h:246
Inline: True
```
```
In block/blk-mq.c (ffffffff817c20d7)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_complete_request_remote
```
```
In block/blk-cgroup.c (ffffffff817e67cb)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In io_uring/io_uring.c (ffffffff8181017a)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_fallback_tw
```
```
In lib/closure.c (ffffffff81925bd1)
Location: include/linux/llist.h:246
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7cb79)
Location: include/linux/llist.h:246
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81af181a)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b5468c)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c875a9)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:__drm_connector_put_safe
```
```
In net/core/net_namespace.c (ffffffff81ee312a)
Location: include/linux/llist.h:246
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/ipv4/inet_fragment.c (ffffffff8202ffd6)
Location: include/linux/llist.h:246
Inline: True
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
In kernel/sched/core.c (ffff80001013a4a4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffff8000101bd418)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffff8000101c36d8)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffff80001025b254)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffff80001030f044)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffff800010330a84)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (ffff800010385b40)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffff8000103b6060)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/acpi/apei/ghes.c (ffff8000107afce0)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
```
```
In drivers/tty/tty_buffer.c (ffff80001085d6b0)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In net/core/net_namespace.c (ffff800010bc045c)
Location: include/linux/llist.h:207
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
In kernel/sched/core.c (c0389e14)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (c0405604)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (c040a8f4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (c048e36c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (c052a88c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/file_table.c (c056e9f0)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (c05943e4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/tty/tty_buffer.c (c0964f7c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In net/core/net_namespace.c (c0cdbee0)
Location: include/linux/llist.h:207
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
In kernel/sched/core.c (c000000000187cb4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (c000000000223810)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (c000000000229da8)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (c0000000002feefc)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (c0000000003e0044)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (c0000000004098a0)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (c00000000047bd28)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (c0000000004b2538)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/tty/tty_buffer.c (c0000000008fc2b0)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In net/core/net_namespace.c (c000000000c99c80)
Location: include/linux/llist.h:207
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
In kernel/sched/core.c (ffffffe0000e9bbc)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffe000140a90)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffe000144584)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffe00019a2ce)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffe000217810)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffffffe00022dca6)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (ffffffe0002587ca)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffe000278d9e)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/tty/tty_buffer.c (ffffffe000536080)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In net/core/net_namespace.c (ffffffe00074df94)
Location: include/linux/llist.h:207
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fdbc)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810d4dbc)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff811474b7)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff8114cb4c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811d3088)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff81270d34)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffffffff8128b4e2)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (ffffffff812d787e)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffff812fb29e)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/tty/tty_buffer.c (ffffffff816524a9)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a909f)
Location: include/linux/llist.h:207
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818c49aa)
Location: include/linux/llist.h:207
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8103f31c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810c340d)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff8113a792)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff8113fdfc)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811c5e48)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff81262ca4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffffffff8127d312)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (ffffffff812c84fe)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffff812ebebe)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/tty/tty_buffer.c (ffffffff816328e9)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff81686a8f)
Location: include/linux/llist.h:207
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8187e8ea)
Location: include/linux/llist.h:207
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fc6c)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810d1bfd)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff81145367)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff8114a9fc)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811d0e58)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff8126ead4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffffffff812892f2)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (ffffffff812d568e)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffff812f908e)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638036)
Location: include/linux/llist.h:207
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81680869)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d730f)
Location: include/linux/llist.h:207
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819159aa)
Location: include/linux/llist.h:207
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810510ac)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810dc5c8)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/smp.c (ffffffff81151f47)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff811576ec)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/irq_work.c (ffffffff811df13f)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/vmalloc.c (ffffffff8127e4d4)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/hugetlb.c (ffffffff812990d2)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/file_table.c (ffffffff812e64de)
Location: include/linux/llist.h:207
Inline: True
```
```
In fs/namespace.c (ffffffff8130a3ba)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652366)
Location: include/linux/llist.h:207
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8169aeb9)
Location: include/linux/llist.h:207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f18bf)
Location: include/linux/llist.h:207
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81936b9a)
Location: include/linux/llist.h:207
Inline: True
```
</details>
</li>
</ul>

## Differences
