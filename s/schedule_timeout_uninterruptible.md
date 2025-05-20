# Function: <code>schedule_timeout_uninterruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81823610)
Location: kernel/time/timer.c:1562
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/backing-dev.c:wait_iff_congested
  - mm/swapfile.c:SyS_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff81823610-ffffffff81823630: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3d8a)
Location: kernel/time/timer.c:1778
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:SyS_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff8189e260-ffffffff8189e280: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810faf3a)
Location: kernel/time/timer.c:1783
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:SyS_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff818d30e0-ffffffff818d3101: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fdf55)
Location: kernel/time/timer.c:1774
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:SyS_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff8190a250-ffffffff8190a271: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81108804)
Location: kernel/time/timer.c:1824
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:SYSC_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff81994590-ffffffff819945b1: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81113ae4)
Location: kernel/time/timer.c:1835
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff819f0b20-ffffffff819f0b41: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120344)
Location: kernel/time/timer.c:1834
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff81a2bea0-ffffffff81a2bec1: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112ac41)
Location: kernel/time/timer.c:1838
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
```
**Symbols:**

```
ffffffff81a9c060-ffffffff81a9c081: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136be1)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
ffffffff81ad39b0-ffffffff81ad39d1: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144a41)
Location: kernel/time/timer.c:1947
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff81bcb930-ffffffff81bcb951: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141e01)
Location: kernel/time/timer.c:1909
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff81c447b0-ffffffff81c447d1: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142c01)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff81c37a20-ffffffff81c37a41: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811661b1)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff81d562c0-ffffffff81d562e0: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199d31)
Location: kernel/time/timer.c:1966
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff81f28300-ffffffff81f28326: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d83e1)
Location: kernel/time/timer.c:2198
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff820d3f30-ffffffff820d3f56: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec811)
Location: kernel/time/timer.c:2198
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff821581b0-ffffffff821581d6: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202831)
Location: kernel/time/timer.c:2214
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - net/sched/sch_generic.c:dev_deactivate_many
```
**Symbols:**

```
ffffffff8223b020-ffffffff8223b046: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019f128)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
ffff800010da6520-ffff800010da6558: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e8ff4)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
c0e9e2a8-c0e9e2dc: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001ffe60)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
c000000000ee8d10-c000000000ee8d30: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012dad6)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
ffffffe0008c8982-ffffffe0008c89b2: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112f391)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
ffffffff81a72820-ffffffff81a72841: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81121e11)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
ffffffff81a2ebf0-ffffffff81a2ec11: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d0b1)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
ffffffff81adec30-ffffffff81adec51: schedule_timeout_uninterruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_uninterruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138e41)
Location: kernel/time/timer.c:1926
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep
Direct callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/swapfile.c:__do_sys_swapoff
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
```
**Symbols:**

```
ffffffff81aeb0c0-ffffffff81aeb0e1: schedule_timeout_uninterruptible (STB_GLOBAL)
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
