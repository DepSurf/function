# Function: <code>arch_touch_nmi_watchdog</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8114f560)
Location: kernel/watchdog_hld.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
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
```
**Symbols:**

```
ffffffff8114f560-ffffffff8114f573: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8115bc10)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
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
```
**Symbols:**

```
ffffffff8115bc10-ffffffff8115bc23: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8116a820)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
ffffffff8116a820-ffffffff8116a82e: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81177800)
Location: kernel/watchdog_hld.c:32
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
ffffffff81177800-ffffffff8117780e: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81184660)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
ffffffff81184660-ffffffff81184669: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811904e0)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
ffffffff811904e0-ffffffff811904e9: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a5050)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:boot_delay_msec
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
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
ffffffff811a5050-ffffffff811a5059: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a2040)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:boot_delay_msec
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
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
ffffffff811a2040-ffffffff811a2049: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a2d30)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
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
ffffffff811a2d30-ffffffff811a2d39: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811cc560)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
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
ffffffff811cc560-ffffffff811cc569: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81200430)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/hung_task.c:check_hung_task
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
```
**Symbols:**

```
ffffffff81200430-ffffffff8120043d: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81248030)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
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
```
**Symbols:**

```
ffffffff81248030-ffffffff8124803d: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8125e360)
Location: kernel/watchdog.c:96
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
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
```
**Symbols:**

```
ffffffff8125e360-ffffffff8125e36d: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff812782a0)
Location: kernel/watchdog.c:96
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
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
```
**Symbols:**

```
ffffffff812782a0-ffffffff812782ad: arch_touch_nmi_watchdog (STB_GLOBAL)
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
In kernel/panic.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/nmi.h:113
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
In kernel/panic.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/watchdog.c (c000000000037390)
Location: arch/powerpc/kernel/watchdog.c:313
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - kernel/panic.c:panic
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
c000000000037390-c0000000000373f4: arch_touch_nmi_watchdog (STB_GLOBAL)
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
In kernel/panic.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/time/timer_list.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/nmi.h:113
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/nmi.h:113
Inline: True
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
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81188b00)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
ffffffff81188b00-ffffffff81188b09: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8117bc40)
Location: kernel/watchdog_hld.c:32
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
ffffffff8117bc40-ffffffff8117bc49: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811868d0)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
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
```
**Symbols:**

```
ffffffff811868d0-ffffffff811868d9: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81194220)
Location: kernel/watchdog_hld.c:32
Inline: False
Direct callers:
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
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
```
**Symbols:**

```
ffffffff81194220-ffffffff81194229: arch_touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
