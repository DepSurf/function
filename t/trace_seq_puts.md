# Function: <code>trace_seq_puts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811557c0)
Location: kernel/trace/trace_seq.c:207
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811557c0-ffffffff81155863: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8115eaf0)
Location: kernel/trace/trace_seq.c:207
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff8115eaf0-ffffffff8115eb93: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81169560)
Location: kernel/trace/trace_seq.c:207
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff81169560-ffffffff81169603: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8116c140)
Location: kernel/trace/trace_seq.c:207
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff8116c140-ffffffff8116c1d9: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811791d0)
Location: kernel/trace/trace_seq.c:207
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811791d0-ffffffff81179269: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811883c0)
Location: kernel/trace/trace_seq.c:207
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811883c0-ffffffff8118845a: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81195c70)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff81195c70-ffffffff81195d0a: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a3b10)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811a3b10-ffffffff811a3ba9: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811af310)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811af310-ffffffff811af3a9: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c73f0)
Location: kernel/trace/trace_seq.c:205
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_map
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_mmiotrace.c:mmio_print_pcidev
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811c73f0-ffffffff811c748b: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c4af0)
Location: kernel/trace/trace_seq.c:205
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_map
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_mmiotrace.c:mmio_print_pcidev
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811c4af0-ffffffff811c4b8b: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c5cf0)
Location: kernel/trace/trace_seq.c:205
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811c5cf0-ffffffff811c5d8a: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811f12e0)
Location: kernel/trace/trace_seq.c:205
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811f12e0-ffffffff811f137a: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81229b40)
Location: kernel/trace/trace_seq.c:205
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff81229b40-ffffffff81229c07: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff812752a0)
Location: kernel/trace/trace_seq.c:205
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff812752a0-ffffffff81275367: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8128cc60)
Location: kernel/trace/trace_seq.c:206
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:print_event_fields
  - kernel/trace/trace_output.c:print_array
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff8128cc60-ffffffff8128cd27: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff812a8030)
Location: kernel/trace/trace_seq.c:203
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:s_show
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:print_event_fields
  - kernel/trace/trace_output.c:print_array
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff812a8030-ffffffff812a80fa: trace_seq_puts (STB_GLOBAL)
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
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffff80001022c930)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffff80001022c930-ffff80001022c9c8: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (c046a128)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq_u64
  - kernel/trace/trace_output.c:trace_print_flags_seq_u64
  - kernel/trace/trace_output.c:trace_print_flags_seq_u64
  - kernel/trace/trace_output.c:trace_print_flags_seq_u64
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
c046a128-c046a1c0: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (c0000000002b5060)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
c0000000002b5060-c0000000002b5150: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffe00018694a)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffe00018694a-ffffffe0001869e4: trace_seq_puts (STB_GLOBAL)
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
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a7930)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811a7930-ffffffff811a79c9: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8119a8b0)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff8119a8b0-ffffffff8119a949: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a5700)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811a5700-ffffffff811a5799: trace_seq_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq *s, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811b34a0)
Location: kernel/trace/trace_seq.c:208
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_bprint_print
  - kernel/trace/trace_output.c:trace_bputs_raw
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_bputs_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_printk_msg_only
  - kernel/trace/trace_output.c:trace_print_bputs_msg_only
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events_filter.c:print_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:print_event_filter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_probe.c:print_type_string
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
**Symbols:**

```
ffffffff811b34a0-ffffffff811b3539: trace_seq_puts (STB_GLOBAL)
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
