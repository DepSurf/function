# Function: <code>add_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ee4a0)
Location: kernel/time/timer.c:964
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_reseed
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/core/flow.c:flow_cache_init
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff810ee4a0-ffffffff810ee4bd: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f5200)
Location: kernel/time/timer.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff810f5200-ffffffff810f5493: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fc2b0)
Location: kernel/time/timer.c:1114
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/video/console/fbcon.c:fbcon_add_cursor_timer
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff810fc2b0-ffffffff810fc50f: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fe740)
Location: kernel/time/timer.c:1089
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_new_hashrnd
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff810fe740-ffffffff810fe9a8: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81109420)
Location: kernel/time/timer.c:1127
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81109420-ffffffff81109699: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811146f0)
Location: kernel/time/timer.c:1135
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff811146f0-ffffffff81114966: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111f530)
Location: kernel/time/timer.c:1134
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff8111f530-ffffffff8111f7a6: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a0c0)
Location: kernel/time/timer.c:1129
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff8112a0c0-ffffffff8112a2c9: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136060)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff81136060-ffffffff81136269: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811449f0)
Location: kernel/time/timer.c:1145
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - block/blk-iocost.c:ioc_start_period
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff811449f0-ffffffff81144a14: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141db0)
Location: kernel/time/timer.c:1139
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - block/blk-iocost.c:ioc_start_period
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff81141db0-ffffffff81141dd4: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142bb0)
Location: kernel/time/timer.c:1141
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - block/blk-iocost.c:ioc_start_period
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff81142bb0-ffffffff81142bd4: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811660f0)
Location: kernel/time/timer.c:1141
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-iocost.c:ioc_start_period
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff811660f0-ffffffff81166114: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199c70)
Location: kernel/time/timer.c:1194
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-iocost.c:ioc_start_period
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff81199c70-ffffffff81199ca0: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d82f0)
Location: kernel/time/timer.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-iocost.c:ioc_start_period
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff811d82f0-ffffffff811d832d: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec720)
Location: kernel/time/timer.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/rcu/update.c:tasks_rcu_exit_srcu_stall
  - kernel/rcu/update.c:rcu_tasks_postscan
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-iocost.c:ioc_start_period
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff811ec720-ffffffff811ec75d: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202740)
Location: kernel/time/timer.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/rcu/update.c:tasks_rcu_exit_srcu_stall
  - kernel/rcu/update.c:rcu_tasks_postscan
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-iocost.c:ioc_start_period
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_init
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff81202740-ffffffff8120277d: add_timer (STB_GLOBAL)
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
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019fbb0)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffff80001019fbb0-ffff80001019fdd8: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e8d9c)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - block/blk-iocost.c:ioc_start_period
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_start
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_timer
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
c03e8d9c-c03e8fc8: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001ffb20)
Location: kernel/time/timer.c:1133
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
c0000000001ffb20-c0000000001ffe18: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012d100)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffe00012d100-ffffffe00012d2e4: add_timer (STB_GLOBAL)
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
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112e810)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff8112e810-ffffffff8112ea19: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81121290)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff81121290-ffffffff81121499: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c530)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff8112c530-ffffffff8112c739: add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void add_timer(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81139830)
Location: kernel/time/timer.c:1133
Inline: True
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - fs/jbd2/transaction.c:start_this_handle
  - fs/pstore/platform.c:pstore_register
  - lib/random32.c:prandom_reseed
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_activate
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/ipv4/igmp.c:igmp_heard_query
```
**Symbols:**

```
ffffffff81139830-ffffffff81139a37: add_timer (STB_GLOBAL)
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
