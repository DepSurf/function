# Function: <code>llist_del_all</code>

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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81046dd5)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
```
```
In kernel/sched/core.c (ffffffff810ac18d)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff81103632)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff81170e74)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff811cedd5)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff8120e655)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff8122cc05)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b6556)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/tty_buffer.c (ffffffff814eac59)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81046fd5)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810aed83)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff8110ab14)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8117e564)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff811e9e0b)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff812350b5)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff81255395)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff81506062)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8153bb49)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81048b55)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810b4eb3)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff81112334)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8118a174)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff811fad35)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff81247c55)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812688d5)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152a262)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff815681c9)
Location: include/linux/llist.h:191
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff810484e5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810b107e)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff81113970)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8118cc84)
Location: include/linux/llist.h:232
Inline: True
```
```
In mm/vmalloc.c (ffffffff81205a40)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff81253485)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff81275c35)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153d4f6)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8157b779)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104bf16)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810b84be)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff8111eef0)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8119a681)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff8121e860)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff81275586)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff81298186)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff815a00d6)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff815e0189)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104ec15)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810bffae)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff8112c230)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811b00c1)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff812415a5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff8129be25)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812bddb5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d722d)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff81619419)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81887b63)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104c2e5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810c931e)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff81137b00)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811be6d1)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff81255ca5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff812b0ae5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812d30b5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f14a5)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff81636669)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff818a8673)
Location: include/linux/llist.h:232
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104f1e5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810d0ef0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff81142c32)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff81147e35)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811ce271)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff81268d85)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff812cd475)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812f13b5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff81623285)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a8b5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff818f3c53)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fb65)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810daea0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff8114e7a0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff81153c75)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811da891)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffffffff812776c5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff81292f35)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff812dee95)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff81302f65)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644d55)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8168cfa5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81925c03)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81054065)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/smp.c (ffffffff8115f042)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff811656a5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811f755e)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffffffff812a8585)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff812c6255)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff81315fe5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff8133c9c5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In fs/io_uring.c (ffffffff813801e5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_put_work
```
```
In ipc/namespace.c (ffffffff81495075)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1f35)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f075)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff819f84f0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81052fc5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/smp.c (ffffffff8115afe2)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff81161e15)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811f60be)
Location: include/linux/llist.h:235
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b74f5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff812d1e45)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff813215a5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff81348885)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In fs/io_uring.c (ffffffff8138ebe5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_put_work
```
```
In ipc/namespace.c (ffffffff814b2a95)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f2f5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8175afa5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff819f7f72)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02855)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810548b5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/smp.c (ffffffff8115c372)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff811628a5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811f6fae)
Location: include/linux/llist.h:235
Inline: True
```
```
In mm/vmalloc.c (ffffffff812bcdc5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (ffffffff81327315)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff8134ec55)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In fs/io_uring.c (ffffffff813966a5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_put_work
```
```
In ipc/namespace.c (ffffffff814b8685)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In block/blk-mq.c (ffffffff81572c49)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_complete_reqs
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0bd5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ee45)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff819de413)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee165)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105d205)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff81151ab9)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
```
In kernel/smp.c (ffffffff81181532)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff81187e15)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff8122857e)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff812ff535)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff8131d995)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff81374be5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff8139ccf5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In fs/io_uring.c (ffffffff813e5a15)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_fallback_req_func
```
```
In ipc/namespace.c (ffffffff81510eb5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In block/blk-mq.c (ffffffff815d7159)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_complete_reqs
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176ace5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf5d5)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81a8e153)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae515)
Location: include/linux/llist.h:235
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81069725)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff8117a149)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
```
In kernel/module/main.c (ffffffff8118df65)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/module/main.c:do_free_init
```
```
In kernel/smp.c (ffffffff811b7aa5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/smp.c:__flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8126962d)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In mm/vmalloc.c (ffffffff81366655)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff81389085)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff813f3a15)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff8141fc25)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In ipc/namespace.c (ffffffff815a3355)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In block/blk-mq.c (ffffffff81683209)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_complete_reqs
```
```
In io_uring/io_uring.c (ffffffff816cc0a5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f895)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff818fbad5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81c04083)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41705)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810793e5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff811b26f9)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
```
In kernel/module/main.c (ffffffff811cab45)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/module/main.c:do_free_init
```
```
In kernel/smp.c (ffffffff811f8ce5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/smp.c:__flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff812be4e0)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/memalloc.c (ffffffff8131bc35)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In mm/vmalloc.c (ffffffff813e2275)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff81407795)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/memory-failure.c (ffffffff8145f362)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/memory-failure.c:__free_raw_hwp_pages
```
```
In fs/file_table.c (ffffffff8147c825)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff814ac105)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In ipc/namespace.c (ffffffff8164cf45)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In block/blk-mq.c (ffffffff81740a29)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_complete_reqs
```
```
In block/blk-cgroup.c (ffffffff81761d1c)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_rstat_flush
```
```
In io_uring/io_uring.c (ffffffff8178f862)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/rsrc.c (ffffffff817a0c65)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_put_work
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8c65)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff81a54ec5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81db3793)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a505)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b695)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff811cc013)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
```
In kernel/module/main.c (ffffffff811dde05)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/module/main.c:do_free_init
```
```
In kernel/smp.c (ffffffff8120e47a)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/smp.c:__flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff812e5120)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/memalloc.c (ffffffff8134b688)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In mm/vmalloc.c (ffffffff81417225)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/vmalloc.c:delayed_vfree_work
```
```
In mm/hugetlb.c (ffffffff8143ac65)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/memory-failure.c (ffffffff81494ba4)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In fs/file_table.c (ffffffff814b13f5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff814e0ec5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In ipc/namespace.c (ffffffff816856b5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In block/blk-mq.c (ffffffff8177cc59)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_complete_reqs
```
```
In block/blk-cgroup.c (ffffffff817a0658)
Location: include/linux/llist.h:237
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817d0bae)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30c45)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f4a5)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81e23e43)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a035)
Location: include/linux/llist.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082b55)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/rcu/tree.c (ffffffff811ddd13)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
```
In kernel/module/main.c (ffffffff811f3b05)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - kernel/module/main.c:do_free_init
```
```
In kernel/smp.c (ffffffff81225c1f)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - kernel/smp.c:__flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff813031d0)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
```
```
In kernel/bpf/memalloc.c (ffffffff8137254a)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:__free_by_rcu
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In mm/vmalloc.c (ffffffff81443d15)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - mm/vmalloc.c:delayed_vfree_work
```
```
In mm/hugetlb.c (ffffffff814743c5)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/memory-failure.c (ffffffff814c4445)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - mm/memory-failure.c:__folio_free_raw_hwp
```
```
In fs/file_table.c (ffffffff814e2c35)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff81514f95)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In ipc/namespace.c (ffffffff816c1ad5)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In block/blk-mq.c (ffffffff817bf059)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_complete_reqs
```
```
In block/blk-cgroup.c (ffffffff817e4188)
Location: include/linux/llist.h:264
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8181449e)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In lib/lwq.c (ffffffff8185b999)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - lib/lwq.c:lwq_dequeue_all
  - lib/lwq.c:__lwq_dequeue
```
```
In lib/closure.c (ffffffff81925ce4)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - lib/closure.c:__closure_wake_up
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c0b5)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1ea5)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8877c)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_connector_free_work_fn
```
```
In net/core/net_namespace.c (ffffffff81ee1da3)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/ipv4/inet_fragment.c (ffffffff820306e5)
Location: include/linux/llist.h:264
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
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
In kernel/sched/core.c (ffff80001013aaa8)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffff8000101bd93c)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffff8000101c3084)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffff80001025b020)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffff80001030db84)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffff800010330adc)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffff800010385664)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:delayed_fput
```
```
In fs/namespace.c (ffff8000103b6314)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffff8000107afd4c)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffff80001085d858)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffff800010bc0e24)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In kernel/sched/core.c (c038a4f8)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (c04058b8)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (c040a27c)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (c048e0c0)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (c05295d0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In fs/file_table.c (c056e824)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:delayed_fput
```
```
In fs/namespace.c (c0594658)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/tty/tty_buffer.c (c096550c)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (c0cdbfc4)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In kernel/sched/core.c (c00000000018855c)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (c000000000222b04)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (c000000000229630)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (c0000000002fec20)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (c0000000003de774)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (c000000000409918)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (c00000000047b648)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:delayed_fput
```
```
In fs/namespace.c (c0000000004b2948)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/tty/tty_buffer.c (c0000000008fcb74)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (c000000000c9b8ac)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In kernel/sched/core.c (ffffffe0000ea24c)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffe000140404)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffe00014403c)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffe00019a05c)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffffffe000217788)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffe00022dcf2)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffe000258326)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffe000279008)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/tty/tty_buffer.c (ffffffe000536620)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffe00074dc64)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fc65)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810d5350)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff81146dc0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff8114c295)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811d2eb1)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126fd15)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff8128b515)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff812d7475)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812fb545)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/tty/tty_buffer.c (ffffffff81652a25)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff818c5c03)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8103f1c5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810c39a0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff8113a0c0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff8113f545)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811c5c71)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffffffff81261c85)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff8127d345)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff812c80f5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812ec165)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/tty/tty_buffer.c (ffffffff81632e65)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff8187fb43)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fb15)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810d2190)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff81144c70)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff8114a145)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811d0c81)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126dab5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff81289325)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff812d5285)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff812f9335)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638b95)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff81680de5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81916c03)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81050f55)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records
```
```
In kernel/sched/core.c (ffffffff810dcc20)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/smp.c (ffffffff811517f0)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffffffff81156e25)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/irq_work.c (ffffffff811def41)
Location: include/linux/llist.h:220
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127d475)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/hugetlb.c (ffffffff81299105)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In fs/file_table.c (ffffffff812e60d5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/file_table.c:flush_delayed_fput
```
```
In fs/namespace.c (ffffffff8130a655)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652ee5)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/tty/tty_buffer.c (ffffffff8169b435)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/net_namespace.c (ffffffff81937e13)
Location: include/linux/llist.h:220
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
</details>
</li>
</ul>

## Differences
