# Function: <code>trace_seq_putc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811554d0)
Location: kernel/trace/trace_seq.c:235
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/trace_events.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811554d0-ffffffff8115554c: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8115e800)
Location: kernel/trace/trace_seq.c:235
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_events.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff8115e800-ffffffff8115e87c: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81169270)
Location: kernel/trace/trace_seq.c:235
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff81169270-ffffffff811692ec: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8116c240)
Location: kernel/trace/trace_seq.c:235
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff8116c240-ffffffff8116c2b1: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811792d0)
Location: kernel/trace/trace_seq.c:235
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811792d0-ffffffff81179341: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81188460)
Location: kernel/trace/trace_seq.c:235
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff81188460-ffffffff811884d2: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81195d60)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff81195d60-ffffffff81195dd2: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a3c00)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811a3c00-ffffffff811a3c72: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811af400)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811af400-ffffffff811af472: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c74e0)
Location: kernel/trace/trace_seq.c:233
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:output_printk
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811c74e0-ffffffff811c7552: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c4be0)
Location: kernel/trace/trace_seq.c:233
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:output_printk
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811c4be0-ffffffff811c4c52: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c5de0)
Location: kernel/trace/trace_seq.c:233
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811c5de0-ffffffff811c5e50: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811f13d0)
Location: kernel/trace/trace_seq.c:233
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_osnoise_print
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811f13d0-ffffffff811f1440: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81229c80)
Location: kernel/trace/trace_seq.c:233
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_osnoise_print
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff81229c80-ffffffff81229d16: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81275400)
Location: kernel/trace/trace_seq.c:233
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_osnoise_print
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff81275400-ffffffff81275496: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8128cdc0)
Location: kernel/trace/trace_seq.c:234
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_osnoise_print
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:print_array
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_probe.c:trace_probe_print_args
  - kernel/trace/trace_probe.c:trace_probe_print_args
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff8128cdc0-ffffffff8128ce56: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff812a81a0)
Location: kernel/trace/trace_seq.c:231
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_osnoise_print
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:print_array
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_comment
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_exit
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_events_synth.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_probe.c:trace_probe_print_args
  - kernel/trace/trace_probe.c:trace_probe_print_args
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_tf_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_host_stat
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff812a81a0-ffffffff812a8239: trace_seq_putc (STB_GLOBAL)
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
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffff80001022ca10)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffff80001022ca10-ffff80001022ca74: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (c046a210)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq_u64
  - kernel/trace/trace_output.c:trace_print_flags_seq_u64
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
**Symbols:**

```
c046a210-c046a278: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (c0000000002b51c0)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
**Symbols:**

```
c0000000002b51c0-c0000000002b5248: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffe00018675a)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
**Symbols:**

```
ffffffe00018675a-ffffffe0001867b0: trace_seq_putc (STB_GLOBAL)
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
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a7a20)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/nvme/host/trace.c:nvme_trace_disk_name
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
```
**Symbols:**

```
ffffffff811a7a20-ffffffff811a7a92: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8119a9a0)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/nvme/host/trace.c:nvme_trace_disk_name
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff8119a9a0-ffffffff8119aa12: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a57f0)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811a57f0-ffffffff811a5862: trace_seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putc(struct trace_seq *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811b3590)
Location: kernel/trace/trace_seq.c:236
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_print_entry_header
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_output.c:trace_raw_data
  - kernel/trace/trace_output.c:trace_hwlat_print
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/trace/trace_output.c:trace_stack_print
  - kernel/trace/trace_output.c:trace_fn_trace
  - kernel/trace/trace_output.c:trace_print_lat_fmt
  - kernel/trace/trace_output.c:seq_print_ip_sym
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_array_seq
  - kernel/trace/trace_output.c:trace_print_hex_seq
  - kernel/trace/trace_output.c:trace_print_bitmask_seq
  - kernel/trace/trace_output.c:trace_print_symbols_seq
  - kernel/trace/trace_output.c:trace_print_flags_seq
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_function_flags
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/trace_functions_graph.c:print_graph_proc
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_log_dump_pdu
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_syscalls.c:print_syscall_enter
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_events_hist.c:print_synth_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/ata/libata-trace.c:libata_trace_parse_subcmd
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_qc_flags
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_eh_action
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/ata/libata-trace.c:libata_trace_parse_status
  - drivers/firmware/efi/cper.c:cper_mem_err_unpack
```
**Symbols:**

```
ffffffff811b3590-ffffffff811b3602: trace_seq_putc (STB_GLOBAL)
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
