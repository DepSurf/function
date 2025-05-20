# Function: <code>vscnprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff813f5740)
Location: lib/vsprintf.c:2006
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:early_printk
  - kernel/kexec_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:verbose
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/clk/clkdev.c:vclkdev_alloc
```
**Symbols:**

```
ffffffff813f5740-ffffffff813f5769: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143c3c5)
Location: lib/vsprintf.c:2143
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_emit
  - kernel/kexec_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:verbose
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/clk/clkdev.c:vclkdev_alloc
```
**Symbols:**

```
ffffffff8143c2f0-ffffffff8143c319: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff814593a5)
Location: lib/vsprintf.c:2171
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_emit
  - kernel/kexec_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:verbose
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff814592d0-ffffffff814592f9: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818fad66)
Location: lib/vsprintf.c:2311
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_emit
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:verbose
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff818fac90-ffffffff818facb9: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819819b6)
Location: lib/vsprintf.c:2409
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_emit
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:verbose
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff819818e0-ffffffff81981909: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dd9b8)
Location: lib/vsprintf.c:2395
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff819dd8c0-ffffffff819dd8e8: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15fb8)
Location: lib/vsprintf.c:2523
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff81a15ec0-ffffffff81a15ee8: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a85b28)
Location: lib/vsprintf.c:2630
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff81a85a30-ffffffff81a85a59: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abcda8)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff81abccb0-ffffffff81abccd9: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f8eb8)
Location: lib/vsprintf.c:2747
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff815f8c30-ffffffff815f8c5f: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161d578)
Location: lib/vsprintf.c:2746
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - fs/sysfs/file.c:sysfs_emit_at
  - fs/sysfs/file.c:sysfs_emit
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff8161d2f0-ffffffff8161d31f: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81600e78)
Location: lib/vsprintf.c:2877
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:printk_sprint
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - fs/sysfs/file.c:sysfs_emit_at
  - fs/sysfs/file.c:sysfs_emit
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff81600c00-ffffffff81600c2c: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166edd8)
Location: lib/vsprintf.c:2896
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:printk_sprint
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - fs/sysfs/file.c:sysfs_emit_at
  - fs/sysfs/file.c:sysfs_emit
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff8166eb60-ffffffff8166eb8c: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff817890da)
Location: lib/vsprintf.c:2881
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:printk_sprint
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - fs/sysfs/file.c:sysfs_emit_at
  - fs/sysfs/file.c:sysfs_emit
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff81788dd0-ffffffff81788e0f: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8204645a)
Location: lib/vsprintf.c:2895
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:printk_sprint
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - fs/sysfs/file.c:sysfs_emit_at
  - fs/sysfs/file.c:sysfs_emit
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff82046100-ffffffff8204613f: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c4aba)
Location: lib/vsprintf.c:2916
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:printk_sprint
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/bpf/log.c:bpf_verifier_vlog
  - fs/sysfs/file.c:sysfs_emit_at
  - fs/sysfs/file.c:sysfs_emit
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff820c4760-ffffffff820c479f: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219f43a)
Location: lib/vsprintf.c:2923
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:printk_sprint
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/bpf/log.c:bpf_verifier_vlog
  - fs/sysfs/file.c:sysfs_emit_at
  - fs/sysfs/file.c:sysfs_emit
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
  - drivers/leds/led-triggers.c:led_trigger_snprintf
```
**Symbols:**

```
ffffffff8219f0e0-ffffffff8219f11f: vscnprintf (STB_GLOBAL)
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
int vscnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d97328)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffff800010d971c0-ffff800010d97218: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e94788)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
c0e946a8-c0e946d4: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000edd468)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
c000000000edd390-c000000000edd3e8: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008c0f86)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffe0008c0ef6-ffffffe0008c0f22: vscnprintf (STB_GLOBAL)
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
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5bbf8)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff81a5bb00-ffffffff81a5bb29: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a18cd8)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff81a18be0-ffffffff81a18c09: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac7fe8)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff81ac7ef0-ffffffff81ac7f19: vscnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vscnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad44c8)
Location: lib/vsprintf.c:2637
Inline: True
Inline callers:
  - lib/vsprintf.c:scnprintf
Direct callers:
  - kernel/panic.c:panic
  - kernel/printk/printk.c:early_printk
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/crash_core.c:vmcoreinfo_append_str
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-eh.c:ata_port_desc
  - drivers/ata/libata-eh.c:ata_ehi_push_desc
  - drivers/ata/libata-eh.c:__ata_ehi_push_desc
```
**Symbols:**

```
ffffffff81ad43d0-ffffffff81ad43f9: vscnprintf (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
