# Function: <code>seq_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230df0)
Location: fs/seq_file.c:365
Inline: True
Inline callers:
  - fs/seq_file.c:single_release
  - fs/seq_file.c:seq_release_private
Direct callers:
  - kernel/sched/debug.c:sched_debug_release
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/array.c:children_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff81230df0-ffffffff81230e16: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8125919f)
Location: fs/seq_file.c:368
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/sched/debug.c:sched_debug_release
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/array.c:children_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff81259100-ffffffff81259126: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c649)
Location: fs/seq_file.c:375
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/sched/debug.c:sched_debug_release
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/array.c:children_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff8126c5b0-ffffffff8126c5d6: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a209)
Location: fs/seq_file.c:361
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/sched/debug.c:sched_debug_release
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/array.c:children_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff8127a170-ffffffff8127a196: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129cc89)
Location: fs/seq_file.c:365
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/sched/debug.c:sched_debug_release
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/array.c:children_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff8129cbf0-ffffffff8129cc16: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c2fb9)
Location: fs/seq_file.c:368
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff812c2da0-ffffffff812c2dcd: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d7f29)
Location: fs/seq_file.c:356
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff812d7d10-ffffffff812d7d3d: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6439)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff812f6220-ffffffff812f6250: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81308009)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff81307df0-ffffffff81307e20: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341d99)
Location: fs/seq_file.c:333
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff813412c0-ffffffff813412f2: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e459)
Location: fs/seq_file.c:349
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff8134d330-ffffffff8134d362: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81354799)
Location: fs/seq_file.c:352
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff81353f30-ffffffff81353f62: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2b79)
Location: fs/seq_file.c:352
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff813a2360-ffffffff813a2392: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814268e9)
Location: fs/seq_file.c:352
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff81425f00-ffffffff81425f38: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b3169)
Location: fs/seq_file.c:352
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff814b27e0-ffffffff814b2818: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e81b9)
Location: fs/seq_file.c:352
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff814e7830-ffffffff814e7868: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151c049)
Location: fs/seq_file.c:352
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff8151b6c0-ffffffff8151b6f8: seq_release (STB_GLOBAL)
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
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bbb70)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffff8000103bb8b0-ffff8000103bb8f4: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c05992f0)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
c05990d4-c0599110: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b9050)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
c0000000004b8cf0-c0000000004b8d4c: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d5f0)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffe00027d3e2-ffffffe00027d422: seq_release (STB_GLOBAL)
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
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813005e9)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff813003d0-ffffffff81300400: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f1209)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff812f0ff0-ffffffff812f1020: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe3d9)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff812fe1c0-ffffffff812fe1f0: seq_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int seq_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f719)
Location: fs/seq_file.c:357
Inline: True
Inline callers:
  - fs/seq_file.c:seq_release_private
  - fs/seq_file.c:single_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace_stat.c:tracing_stat_release
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events_trigger.c:event_trigger_release
  - kernel/bpf/inode.c:bpffs_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_release
  - security/apparmor/apparmorfs.c:profiles_release
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release
```
**Symbols:**

```
ffffffff8130f500-ffffffff8130f530: seq_release (STB_GLOBAL)
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
