# Function: <code>touch_softlockup_watchdog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113a750)
Location: kernel/watchdog.c:228
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_nmi_watchdog
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - kernel/panic.c:panic
  - kernel/sched/clock.c:sched_clock_idle_wakeup_event
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_irq_enter
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
**Symbols:**

```
ffffffff8113a750-ffffffff8113a767: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81142cb1)
Location: kernel/watchdog.c:246
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_nmi_watchdog
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - kernel/panic.c:panic
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/time/timekeeping.c:timekeeping_resume
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
**Symbols:**

```
ffffffff81142c80-ffffffff81142c97: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ca90)
Location: kernel/watchdog.c:186
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - kernel/panic.c:panic
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/watchdog_hld.c:touch_nmi_watchdog
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8114ca90-ffffffff8114caa7: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ea10)
Location: kernel/watchdog.c:269
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8114ea10-ffffffff8114ea27: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8115b2a0)
Location: kernel/watchdog.c:278
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8115b2a0-ffffffff8115b2b7: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81169eb0)
Location: kernel/watchdog.c:278
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81169eb0-ffffffff81169ec2: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81176db0)
Location: kernel/watchdog.c:273
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81176db0-ffffffff81176dc9: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81183c10)
Location: kernel/watchdog.c:280
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81183c10-ffffffff81183c24: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8118fa80)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8118fa80-ffffffff8118fa94: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a4640)
Location: kernel/watchdog.c:261
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:boot_delay_msec
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffffffff811a4640-ffffffff811a4654: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a16e0)
Location: kernel/watchdog.c:261
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:boot_delay_msec
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffffffff811a16e0-ffffffff811a16f4: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a2340)
Location: kernel/watchdog.c:273
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffffffff811a2340-ffffffff811a2354: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811cbb20)
Location: kernel/watchdog.c:273
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffffffff811cbb20-ffffffff811cbb34: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811ff8a0)
Location: kernel/watchdog.c:273
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
```
**Symbols:**

```
ffffffff811ff8a0-ffffffff811ff8ba: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff812472d0)
Location: kernel/watchdog.c:273
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff812472d0-ffffffff812472ea: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8125e380)
Location: kernel/watchdog.c:373
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8125e380-ffffffff8125e39a: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff812782c0)
Location: kernel/watchdog.c:400
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff812782c0-ffffffff812782da: touch_softlockup_watchdog (STB_GLOBAL)
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
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffff8000102071b0)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_active_timers
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffff8000102071b0-ffff8000102071c8: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (0)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
c04467a8-c04467c0: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (c000000000283750)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
c000000000283750-c000000000283770: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (0)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/hung_task.c:watchdog
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffffffe00016a14e-ffffffe00016a160: touch_softlockup_watchdog (STB_GLOBAL)
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
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811880a0)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff811880a0-ffffffff811880b4: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8117b1e0)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff8117b1e0-ffffffff8117b1f4: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81185e70)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81185e70-ffffffff81185e84: touch_softlockup_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void touch_softlockup_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811937c0)
Location: kernel/watchdog.c:282
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff811937c0-ffffffff811937d4: touch_softlockup_watchdog (STB_GLOBAL)
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
