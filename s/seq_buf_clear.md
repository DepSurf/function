# Function: <code>seq_buf_clear</code>

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
In kernel/trace/ftrace.c (ffffffff8114092b)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8114be44)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:trace_printk_seq
```
```
In kernel/trace/trace_output.c (ffffffff811534a0)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff8115543c)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff8115e689)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/power-traces.c (ffffffff81169f65)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In lib/nmi_backtrace.c (ffffffff813edc40)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
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
In kernel/trace/ftrace.c (ffffffff81149034)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8115c2c8)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/trace/trace_output.c (ffffffff8115d990)
Location: include/linux/seq_buf.h:25
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8115e7d5)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff81168fc9)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/power-traces.c (ffffffff811785f5)
Location: include/linux/seq_buf.h:25
Inline: True
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
In kernel/trace/ftrace.c (ffffffff81152ee4)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81166af8)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff81168400)
Location: include/linux/seq_buf.h:25
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff81169245)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff81174429)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/power-traces.c (ffffffff811840b5)
Location: include/linux/seq_buf.h:25
Inline: True
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
In kernel/trace/ftrace.c (ffffffff811554c8)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81169ff8)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff8116b4fa)
Location: include/linux/seq_buf.h:25
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8116c215)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff8117703a)
Location: include/linux/seq_buf.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/power-traces.c (ffffffff8118676c)
Location: include/linux/seq_buf.h:25
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810472a5)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff81161d68)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81176f98)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff81178583)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811792a5)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff8118480a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/power-traces.c (ffffffff81194462)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119bff4)
Location: include/linux/seq_buf.h:26
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049852)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff81170c2f)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8117dfd1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff8118779a)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8118850e)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff81193909)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff81198858)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811a9da9)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811b10bb)
Location: include/linux/seq_buf.h:26
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810598c1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff8117e6cf)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8118b8c1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff8119510a)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff81195d3e)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811a1a79)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811a6ab8)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811b82a9)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811bf73b)
Location: include/linux/seq_buf.h:26
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce41)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff8118b76b)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81198b71)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff811a2dbb)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811a3be2)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811af98d)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b4a22)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811c7265)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811cfd1b)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ae3e8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105afd8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff8119760a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811a44f1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff811ae7bb)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811af3e2)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811bb00d)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c0052)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811d2f55)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811dc2cb)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bfdf8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106111d)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff811accc2)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811baa91)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:output_printk
```
```
In kernel/trace/trace_output.c (ffffffff811c57cb)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811c7aca)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811d379d)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d99c1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff811ef3c5)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff812f4fb8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f56f)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff811aa5d2)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811b8631)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:output_printk
```
```
In kernel/trace/trace_output.c (ffffffff811c2dfb)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811c51ca)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811d08ed)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d6ac1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dcd1c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:save_cmdstr
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/power-traces.c (ffffffff811edc65)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff813007e8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fc4b)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff811ab1b2)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811b8ee1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff811c3dfb)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811c6374)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811d1a89)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d7eb1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/trace_events_synth.c (ffffffff811de605)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/power-traces.c (ffffffff811eeba5)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff81307618)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a25c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff811d4e92)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811eebd6)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff811ef06b)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811f1964)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811fe7e9)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff81204f11)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120de85)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/power-traces.c (ffffffff8121fbb5)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff81353b4a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8107748a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff8120a02a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81227026)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff812289ec)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff8122a342)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff8123961c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff81240561)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/trace_events_synth.c (ffffffff8124a25c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/power-traces.c (ffffffff8125fa65)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff813cbbca)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108800a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff812526ba)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81272356)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff812740bf)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff81275b42)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff8128623c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff8128d731)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/trace_events_synth.c (ffffffff81298f23)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/power-traces.c (ffffffff812b0d28)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff814508a4)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8191c89c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089a44)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff812699fa)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81289656)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff8128b9ef)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff8128d502)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff812a308c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff812aa6b1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b6046)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/power-traces.c (ffffffff812d3428)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff814889e1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
```
In drivers/pci/p2pdma.c (ffffffff8195fe5c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090b54)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff81283b5a)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff812a49d6)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_printk_seq
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff812a6dbf)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff812a88f2)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_hex_dump
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff812befe5)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header_page_file
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c653d)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d26c4)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/power-traces.c (ffffffff812f0f28)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f43d1)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:dynevent_cmd_init
```
```
In mm/memcontrol.c (ffffffff814b69db)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
```
In drivers/pci/p2pdma.c (ffffffff819a9541)
Location: include/linux/seq_buf.h:33
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
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
In kernel/trace/ftrace.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffff800010227b78)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffff8000103617ec)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In kernel/trace/ftrace.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (c045fcdc)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (c046926c)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (c046a204)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (c0475344)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (c047ad40)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (c0485f44)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (c04903e0)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/powerpc/kernel/process.c (c000000000021c60)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:show_user_instructions
```
```
In arch/powerpc/kernel/security.c (c00000000003b67c)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/powerpc/kernel/security.c:cpu_show_spectre_v2
  - arch/powerpc/kernel/security.c:cpu_show_spectre_v1
  - arch/powerpc/kernel/security.c:cpu_show_meltdown
```
```
In kernel/trace/ftrace.c (c00000000028edd8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (c0000000002a2e84)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (c0000000002b3e98)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (c0000000002b51a8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (c0000000002c7190)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (c0000000002cfb14)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (c0000000002f2090)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (c0000000003013ac)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (c00000000044d958)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In kernel/trace/ftrace.c (ffffffe000170968)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffe00017c094)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffe000185c74)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffe00018673a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffe000190594)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffe000194c0a)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffe000198d20)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffe00019b4d6)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffe000241122)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ab58)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff8118fc2a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8119cb11)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff811a6ddb)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811a7a02)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811b362d)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b8672)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811cb575)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d48eb)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b83d8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104abd8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff81182e6a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8118fb71)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff81199d5b)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8119a982)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811a642d)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811ab452)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811be345)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c76ab)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff812a95a8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105af88)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff8118d9fa)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8119a8e1)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff811a4bab)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811a57d2)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811b13fd)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b6442)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811c9345)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d26bb)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b61e8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c448)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
```
In kernel/trace/ftrace.c (ffffffff8119b58a)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811a8581)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_output.c (ffffffff811b294b)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811b3572)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_seq.c:trace_seq_to_user
  - kernel/trace/trace_seq.c:trace_seq_path
  - kernel/trace/trace_seq.c:trace_seq_putmem_hex
  - kernel/trace/trace_seq.c:trace_seq_puts
  - kernel/trace/trace_seq.c:trace_seq_bprintf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_bitmask
  - kernel/trace/trace_seq.c:trace_seq_printf
  - kernel/trace/trace_seq.c:trace_print_seq
  - kernel/trace/trace_seq.c:trace_print_seq
```
```
In kernel/trace/trace_events.c (ffffffff811bf49d)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c44e2)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811d75a5)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e09ab)
Location: include/linux/seq_buf.h:26
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c69b8)
Location: include/linux/seq_buf.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
</ul>

## Differences
