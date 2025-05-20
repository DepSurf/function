# Function: <code>touch_nmi_watchdog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113a770)
Location: kernel/watchdog.c:252
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl
  - arch/x86/kernel/dumpstack.c:print_trace_address
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
**Symbols:**

```
ffffffff8113a770-ffffffff8113a78f: touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81142ca0)
Location: kernel/watchdog.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl
  - arch/x86/kernel/dumpstack.c:print_trace_address
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - kernel/panic.c:panic
  - kernel/sched/core.c:show_state_filter
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffffffff81142ca0-ffffffff81142cbf: touch_nmi_watchdog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void touch_nmi_watchdog();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8114d590)
Location: kernel/watchdog_hld.c:57
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
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/hung_task.c:watchdog
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_timedout
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
```
**Symbols:**

```
ffffffff8114d590-ffffffff8114d5a8: touch_nmi_watchdog (STB_GLOBAL)
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
In arch/x86/kernel/dumpstack.c (ffffffff8102eea2)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff8102f840)
Location: include/linux/nmi.h:91
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104648a)
Location: include/linux/nmi.h:91
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810541fd)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81054cd5)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff81063471)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff8108491a)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/sched/core.c (ffffffff810b34d8)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff810e3780)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer_list.c (ffffffff8110548c)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff811331fa)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81146264)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114d4ab)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff8114e91e)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff8116a29c)
Location: include/linux/nmi.h:91
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c125a)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff814f633f)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff8153a98f)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159bb5e)
Location: include/linux/nmi.h:91
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102a7f2)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030eb1)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81031840)
Location: include/linux/nmi.h:124
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049cba)
Location: include/linux/nmi.h:124
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052a2b)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057fe1)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81058a95)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff810675f1)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff8108b3d9)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810a884b)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810ba770)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff810eb440)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer_list.c (ffffffff811105ec)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff811401bf)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81152bdd)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81159d39)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff8115b1ae)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff81177220)
Location: include/linux/nmi.h:124
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d5801)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff81536a9f)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff8159d4ef)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81600e0e)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102b387)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102be03)
Location: include/linux/nmi.h:124
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810321fd)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81032ddc)
Location: include/linux/nmi.h:124
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c270)
Location: include/linux/nmi.h:124
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055887)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105aca6)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105b9b5)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106a1be)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff8108eb59)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810b0572)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810c2f93)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff810f47bc)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff81104a64)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff8111bc15)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff8114e9d6)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81161830)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81168968)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff81169d82)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff811866a9)
Location: include/linux/nmi.h:124
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f6c70)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff8156c6af)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff815d5223)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8163a06e)
Location: include/linux/nmi.h:124
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102bf7b)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102c9fd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ce0c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810334c2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81033d62)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049960)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052f27)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060926)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061633)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106ff4e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff81096ef9)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810b96b2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810cc245)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff810fff4c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff8111421d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff811273c5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff8115b7b6)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8116e660)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8117579f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff81176c8a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff81194029)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff81209010)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff815842df)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff815ee9d3)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816583ae)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102e03f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102e75d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ea4a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035335)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81035f35)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ccd9)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810560da)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810643c2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064d23)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107404e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff8109b48a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810bf303)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810d464e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff811086f9)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff8111df2f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff81131e07)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff81167fbb)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117b3f1)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81182506)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff81183a7a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff811a1d0a)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127037f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff815b4edf)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff81620776)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d84e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102e94f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f06d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f35a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035b65)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81036755)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d679)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056515)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a42)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065393)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107500e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099915)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810a19b6)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810c57fa)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810dec1d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff81114ad9)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff8112a4fd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff8113dd57)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff81173e7c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81187281)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8118e376)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff8118f8ea)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff811ad6f0)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127f1bf)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff815d610f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff81642256)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816afd9e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff81030eab)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810316b5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103187a)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81037be3)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff8103842c)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051e24)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b6ed)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b3cc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bcf3)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107c21d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f092)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810a87cf)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810cd237)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810e6e9e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/debug.c (ffffffff81107bda)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
```
```
In kernel/printk/printk.c (ffffffff8112030d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:boot_delay_msec
```
```
In kernel/rcu/tree.c (ffffffff811387c9)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff8114d30c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/stop_machine.c (ffffffff81185e60)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8119b14f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a2ec0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff811a4178)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff811c571e)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b1393)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff8167fe0f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff816efe79)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81763244)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff81031c1b)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810323c5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103257a)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81bd37a5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81bd3a02)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050f44)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a13d)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d038)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d5d3)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107c10d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ac1c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff81bdb387)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff81bdc098)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810e38f1)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/debug.c (ffffffff811063ea)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
```
```
In kernel/printk/printk.c (ffffffff8111b2ca)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:boot_delay_msec
```
```
In kernel/rcu/tree.c (ffffffff81be20ab)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff811494ec)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/stop_machine.c (ffffffff81182fc0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811982df)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a0042)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff811a12d8)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff81be5a3b)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bcdd9)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff8169e8bf)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff8170d259)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177e2a4)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff81032730)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032f2e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103362a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810339c0)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8103421c)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5c17)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81bc5e74)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105292a)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105aadd)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dac7)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e043)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107d2c0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b36b)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff81bcd479)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff81bce1bd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810e5a81)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/debug.c (ffffffff8110842a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
```
```
In kernel/printk/printk.c (ffffffff8111b7f2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff8113046a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff8114a9bc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff81183fc0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8119912f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a0c84)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff811a1f38)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff81bd78d5)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c1cc4)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff8168156f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff816ee930)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761a36)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff810378c2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810380dc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810387c3)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038e4c)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810394ba)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81c98961)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81c98bbe)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105aeea)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8106401d)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810792d4)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079863)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8108bbe0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab4dd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff81ca3c40)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff81ca537a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810fcb3e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/debug.c (ffffffff8112659a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
```
```
In kernel/printk/printk.c (ffffffff8113bf35)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff81151f6e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff8116e6dc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff811ac370)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811c2f0f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811ca3a1)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff811cb6da)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff81cb5802)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff8130543b)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff816f665f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff81768a10)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5a96)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8103daf7)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e371)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103ea57)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f373)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fbf4)
Location: include/linux/nmi.h:134
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104033d)
Location: include/linux/nmi.h:134
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81e47ec0)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81e48208)
Location: include/linux/nmi.h:134
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f15970)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/smpboot.c (ffffffff8108811a)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810885ef)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8109c460)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c110c)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff81e533f5)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810f4e2a)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
```
```
In kernel/sched/core.c (ffffffff8111946e)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/build_utility.c (ffffffff81146cb8)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
```
```
In kernel/printk/printk.c (ffffffff8115ed67)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff81e5fb2f)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff811a298c)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff811ddd8f)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811f670f)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811fe02e)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff811ff3df)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff81e66802)
Location: include/linux/nmi.h:134
Inline: True
```
```
In mm/page_alloc.c (ffffffff8136d6cc)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff81823496)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff8189d282)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81924e67)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
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
In arch/x86/hyperv/mmu.c (ffffffff8104691e)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047235)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047a05)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff810484b1)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048b22)
Location: include/linux/nmi.h:134
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810495a5)
Location: include/linux/nmi.h:134
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81051854)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff810527fb)
Location: include/linux/nmi.h:134
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd094)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109baa9)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c0a2)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b3150)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddaa0)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810ea59d)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff81117377)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
```
```
In kernel/sched/core.c (ffffffff81140d56)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/build_utility.c (ffffffff81174687)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
```
```
In kernel/printk/printk.c (ffffffff81191cc7)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff811b4c29)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff811e1eec)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff8122386f)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8123d93f)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81245877)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff81246dd1)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff81272603)
Location: include/linux/nmi.h:134
Inline: True
```
```
In mm/page_alloc.c (ffffffff813e9a7c)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff819546b6)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff819e601d)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a817a7)
Location: include/linux/nmi.h:134
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
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
In arch/x86/hyperv/mmu.c (ffffffff81046b34)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810475b5)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047cfa)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104885d)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048d94)
Location: include/linux/nmi.h:139
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049801)
Location: include/linux/nmi.h:139
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810525bd)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff8105355b)
Location: include/linux/nmi.h:139
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213eaa4)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f002)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b6250)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8f8a)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810f620b)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff81124339)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
```
```
In kernel/sched/core.c (ffffffff8114ca76)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/build_utility.c (ffffffff81185297)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
```
```
In kernel/power/snapshot.c (ffffffff81196b27)
Location: include/linux/nmi.h:139
Inline: True
```
```
In kernel/printk/printk.c (ffffffff811a3567)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff811c841b)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff811f644c)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff81239eff)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81254966)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8125c907)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff8125de4f)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff81289903)
Location: include/linux/nmi.h:139
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8199aac6)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff81a2e69d)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81accd97)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
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
In arch/x86/hyperv/mmu.c (ffffffff8104d32b)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104dd13)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e409)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f91f)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8105001e)
Location: include/linux/nmi.h:139
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050bc0)
Location: include/linux/nmi.h:139
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810597dd)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a77b)
Location: include/linux/nmi.h:139
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220ac4)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6482)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bd690)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f11ca)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810ff527)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff8112ea39)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_one_workqueue
```
```
In kernel/sched/core.c (ffffffff81158736)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/sched/build_utility.c (ffffffff811939f7)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
```
```
In kernel/power/snapshot.c (ffffffff811a5581)
Location: include/linux/nmi.h:139
Inline: True
```
```
In kernel/printk/printk.c (ffffffff811b2315)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff811da264)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff8120c5ec)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff81253bcf)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8126e7d6)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81276847)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
```
```
In kernel/hung_task.c (ffffffff81277d90)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/trace.c (ffffffff812a4c82)
Location: include/linux/nmi.h:139
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff819e2f46)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff81a79984)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1fe82)
Location: include/linux/nmi.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
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
In kernel/panic.c (ffff8000100f6bb8)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffff8000101223fc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffff80001013e64c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffff800010175b00)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffff800010192d28)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffff8000101a7ba0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/stop_machine.c (ffff8000101e8664)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffff8000101fd32c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffff8000102058c8)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffff800010206fd4)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffff80001022a3fc)
Location: include/linux/nmi.h:132
Inline: True
```
```
In drivers/acpi/osl.c (ffff800010763a2c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffff8000107ad1f0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b1b4)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In kernel/panic.c (c0354bd0)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (c0375dc8)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (c038e628)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (c03c7d9c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (c03dfee8)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (c03f3178)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (c042876c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (c043d3f8)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (c0444530)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (c0445dcc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (c0467aac)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (c053152c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/tty/serial/8250/8250_port.c (c0988d70)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/powerpc/xmon/xmon.c (c000000000110b98)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In kernel/panic.c (c00000000013caa8)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (c00000000016be38)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (c00000000018d7a4)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (c0000000001cf71c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (c0000000001edbbc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (c00000000020a730)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (c000000000259018)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (c000000000275b5c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (c000000000281224)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (c00000000028358c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (c0000000002b2054)
Location: include/linux/nmi.h:132
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000933b38)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In kernel/panic.c (ffffffe0000c277a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffe0000dae7c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffe0000ecf24)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffe000111294)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffe000125262)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffe00013385a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffe00015d662)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/hung_task.c (ffffffe0001697e4)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffe0001849bc)
Location: include/linux/nmi.h:132
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000554f86)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102eaaf)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f1cd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f4ba)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035cc5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff810368b5)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d7d9)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056095)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064532)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064e83)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107400e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff8109b2d6)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810bfb6a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810d8e0d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff8110d0b9)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff81122add)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff81136507)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff8116c49c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117f8a1)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81186996)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff81187f0a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff811a5d10)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127780f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff815c9e6f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8167580e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8101e38c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8101eb45)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ee43)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81025615)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff810261f5)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103ca29)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810462a5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105481e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055153)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106405e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff81089d10)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810ae38a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810c7818)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff810fde79)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff81115596)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff81128f57)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff8115f685)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811729dd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81179ad6)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff8117b04a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff81198c9b)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126972f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff815b2eef)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff815fe666)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816548ee)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102e90f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f02d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f31a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035b25)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81036715)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d629)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810564c5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810649e2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065333)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073fbe)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In kernel/panic.c (ffffffff8109b286)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810bf0ca)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810d514d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff8110afa9)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff811209cd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/timer_list.c (ffffffff81134227)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff8116a26c)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117d671)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81184766)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff81185cda)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff811a3ae0)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff812755af)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff815ca3ef)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff81636096)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a3bde)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
In arch/x86/hyperv/mmu.c (ffffffff8102f718)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102fe4d)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103015a)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81036b05)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/nmi.c (ffffffff81037715)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ea69)
Location: include/linux/nmi.h:132
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057965)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065fc2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066913)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107601e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ade5)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810a2efd)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/workqueue.c (ffffffff810c7435)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/sched/core.c (ffffffff810e0a01)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:show_state_filter
```
```
In kernel/printk/printk.c (ffffffff81116449)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff8112cca2)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/time/timer_list.c (ffffffff81140c47)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/stop_machine.c (ffffffff811779bc)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8118af91)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811920b6)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/hung_task.c (ffffffff81193619)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace.c (ffffffff811b1870)
Location: include/linux/nmi.h:132
Inline: True
```
```
In mm/page_alloc.c (ffffffff8128516f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
```
```
In drivers/acpi/osl.c (ffffffff815e424f)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_stall
```
```
In drivers/acpi/apei/erst.c (ffffffff816503a6)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_timedout
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816be06e)
Location: include/linux/nmi.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
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
</ul>
