# Function: <code>trace_seq_init</code>

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
In kernel/trace/ftrace.c (ffffffff8114090e)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8114be32)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_output.c (ffffffff81153491)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff81155426)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_events.c (ffffffff8115e674)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/power-traces.c (ffffffff81169f5a)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff81149022)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8115c2b6)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_output.c (ffffffff8115d981)
Location: include/linux/trace_seq.h:20
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8115e7bc)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_events.c (ffffffff81168fb4)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/power-traces.c (ffffffff811785ea)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/ftrace.c (ffffffff81152ed2)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81166ae6)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_output.c (ffffffff811683f1)
Location: include/linux/trace_seq.h:20
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8116922c)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_events.c (ffffffff81174414)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/power-traces.c (ffffffff811840aa)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/ftrace.c (ffffffff811554b6)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81169fe6)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_output.c (ffffffff8116b4e0)
Location: include/linux/trace_seq.h:20
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8116c1fc)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/trace_events.c (ffffffff81177025)
Location: include/linux/trace_seq.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/power-traces.c (ffffffff81186761)
Location: include/linux/trace_seq.h:20
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
In kernel/trace/ftrace.c (ffffffff81161d56)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81176f86)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff81178574)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8117928c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811847f5)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/power-traces.c (ffffffff81194457)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119bfe9)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff81170c16)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8117dfbc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff81187784)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811884fc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811938f4)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff81198842)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811a9d90)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811b10a2)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff8117e6b6)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8118b8ac)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811950f4)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff81195d2c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811a1a64)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811a6aa2)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811b8290)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811bf722)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff8118b74e)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81198b5c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811a2d9f)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811a3bcc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811af978)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b4a0d)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811c7250)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811cfd00)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff811975ed)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811a44dc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811ae79f)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811af3cc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811baff8)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c003c)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811d2f40)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811dc2b0)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff811acca5)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811baa7c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811c57af)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811c7ab8)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811d3788)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d99ab)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff811ef3b0)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff811aa5b5)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811b861c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811c2ddf)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811c51b8)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811d08d8)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d6aab)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff811edc50)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff811ab195)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811b8ecc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811c3ddf)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811c6362)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811d1a74)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d7e9b)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff811eeb90)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff811d4e75)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811eebc4)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811ef04f)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff811f1952)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811fe7d4)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff81204efb)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff8121fba0)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff8120a00d)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81227014)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff812289d1)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff8122a330)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff81239607)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff8124054b)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff8125fa53)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff8125269d)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81272344)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff812740a1)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff81275b30)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff81286227)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff8128d71b)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff812b0d16)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff812699dd)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff81289644)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff8128b9d1)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff8128d4f0)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff812a3077)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff812aa69b)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff812d3416)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffffffff81283b3d)
Location: include/linux/trace_seq.h:31
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff812a49c4)
Location: include/linux/trace_seq.h:31
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
In kernel/trace/trace_output.c (ffffffff812a6da1)
Location: include/linux/trace_seq.h:31
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_seq.c (ffffffff812a88e0)
Location: include/linux/trace_seq.h:31
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
In kernel/trace/trace_events.c (ffffffff812befd0)
Location: include/linux/trace_seq.h:31
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header_page_file
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c6524)
Location: include/linux/trace_seq.h:31
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (ffffffff812f0f16)
Location: include/linux/trace_seq.h:31
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:trace_raw_output_pm_qos_update_flags
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
In kernel/trace/ftrace.c (ffff80001020fa20)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffff80001021f49c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffff80001022bc4c)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffff80001022c9e8)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffff80001023970c)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffff80001023f638)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffff800010252ae4)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025c39c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (c044efec)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (c045fcc0)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (c0469250)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (c046a1e8)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (c0474ed4)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (c047ad10)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:append_filter_err
```
```
In kernel/trace/power-traces.c (c0485f20)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (c04903cc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (c00000000028edb4)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (c0000000002a2e5c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (c0000000002b3e7c)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (c0000000002b5190)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (c0000000002c717c)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (c0000000002cfaf4)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (c0000000002f2078)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (c000000000301388)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffe000170950)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffe00017c08a)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffe000185c5c)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffe000186736)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffe000190588)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffe000194bfc)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffe000198d10)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffe00019b4c6)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff8118fc0d)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8119cafc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811a6dbf)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811a79ec)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811b3618)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b865c)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811cb560)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d48d0)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff81182e4d)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8118fb5c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff81199d3f)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff8119a96c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811a6418)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811ab43c)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811be330)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c7690)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff8118d9dd)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff8119a8cc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811a4b8f)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811a57bc)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811b13e8)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b642c)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811c9330)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d26a0)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/ftrace.c (ffffffff8119b56d)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace.c (ffffffff811a856c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_output.c (ffffffff811b292f)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/trace_seq.c (ffffffff811b355c)
Location: include/linux/trace_seq.h:21
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
In kernel/trace/trace_events.c (ffffffff811bf488)
Location: include/linux/trace_seq.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:show_header
  - kernel/trace/trace_events.c:subsystem_filter_read
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c44cc)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/trace/power-traces.c (ffffffff811d7590)
Location: include/linux/trace_seq.h:21
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e0990)
Location: include/linux/trace_seq.h:21
Inline: True
```
</details>
</li>
</ul>

## Differences
