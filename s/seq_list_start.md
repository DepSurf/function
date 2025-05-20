# Function: <code>seq_list_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230660)
Location: fs/seq_file.c:801
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/ftrace.c:fpid_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_kprobe.c:probes_seq_start
  - kernel/trace/trace_uprobe.c:probes_seq_start
  - mm/slab_common.c:slab_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81230660-ffffffff8123068a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81258cf0)
Location: fs/seq_file.c:804
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_kprobe.c:probes_seq_start
  - kernel/trace/trace_uprobe.c:probes_seq_start
  - mm/slab_common.c:slab_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81258cf0-ffffffff81258d1a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c1a0)
Location: fs/seq_file.c:842
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_kprobe.c:probes_seq_start
  - kernel/trace/trace_uprobe.c:probes_seq_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff8126c1a0-ffffffff8126c1ca: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81279980)
Location: fs/seq_file.c:828
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_kprobe.c:probes_seq_start
  - kernel/trace/trace_uprobe.c:probes_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/blk-mq-debugfs.c:ctx_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81279980-ffffffff812799aa: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129c3b0)
Location: fs/seq_file.c:832
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_kprobe.c:probes_seq_start
  - kernel/trace/trace_uprobe.c:probes_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/blk-mq-debugfs.c:ctx_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff8129c3b0-ffffffff8129c3da: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c28f0)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_hist.c:synth_events_seq_start
  - kernel/trace/trace_kprobe.c:probes_seq_start
  - kernel/trace/trace_uprobe.c:probes_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/blk-mq-debugfs.c:ctx_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff812c28f0-ffffffff812c291a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d7b90)
Location: fs/seq_file.c:884
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff812d7b90-ffffffff812d7bba: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f60a0)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff812f60a0-ffffffff812f60ca: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81307c70)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81307c70-ffffffff81307c9a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341130)
Location: fs/seq_file.c:872
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81341130-ffffffff8134115a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134d1c0)
Location: fs/seq_file.c:888
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff8134d1c0-ffffffff8134d1ea: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81353da0)
Location: fs/seq_file.c:910
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81353da0-ffffffff81353dca: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a21f0)
Location: fs/seq_file.c:919
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch2_start
  - block/mq-deadline.c:deadline_dispatch1_start
  - block/mq-deadline.c:deadline_dispatch0_start
  - block/mq-deadline.c:deadline_write2_fifo_start
  - block/mq-deadline.c:deadline_read2_fifo_start
  - block/mq-deadline.c:deadline_write1_fifo_start
  - block/mq-deadline.c:deadline_read1_fifo_start
  - block/mq-deadline.c:deadline_write0_fifo_start
  - block/mq-deadline.c:deadline_read0_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff813a21f0-ffffffff813a221a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81425ce0)
Location: fs/seq_file.c:903
Inline: True
Direct callers:
  - kernel/module/procfs.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch2_start
  - block/mq-deadline.c:deadline_dispatch1_start
  - block/mq-deadline.c:deadline_dispatch0_start
  - block/mq-deadline.c:deadline_write2_fifo_start
  - block/mq-deadline.c:deadline_read2_fifo_start
  - block/mq-deadline.c:deadline_write1_fifo_start
  - block/mq-deadline.c:deadline_read1_fifo_start
  - block/mq-deadline.c:deadline_write0_fifo_start
  - block/mq-deadline.c:deadline_read0_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81425ce0-ffffffff81425d12: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b2540)
Location: fs/seq_file.c:903
Inline: True
Direct callers:
  - kernel/module/procfs.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - kernel/trace/rv/rv.c:available_monitors_start
  - kernel/trace/rv/rv_reactors.c:reactors_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch2_start
  - block/mq-deadline.c:deadline_dispatch1_start
  - block/mq-deadline.c:deadline_dispatch0_start
  - block/mq-deadline.c:deadline_write2_fifo_start
  - block/mq-deadline.c:deadline_read2_fifo_start
  - block/mq-deadline.c:deadline_write1_fifo_start
  - block/mq-deadline.c:deadline_read1_fifo_start
  - block/mq-deadline.c:deadline_write0_fifo_start
  - block/mq-deadline.c:deadline_read0_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff814b2540-ffffffff814b2572: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e7590)
Location: fs/seq_file.c:903
Inline: True
Direct callers:
  - kernel/module/procfs.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - kernel/trace/rv/rv.c:available_monitors_start
  - kernel/trace/rv/rv_reactors.c:reactors_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch2_start
  - block/mq-deadline.c:deadline_dispatch1_start
  - block/mq-deadline.c:deadline_dispatch0_start
  - block/mq-deadline.c:deadline_write2_fifo_start
  - block/mq-deadline.c:deadline_read2_fifo_start
  - block/mq-deadline.c:deadline_write1_fifo_start
  - block/mq-deadline.c:deadline_read1_fifo_start
  - block/mq-deadline.c:deadline_write0_fifo_start
  - block/mq-deadline.c:deadline_read0_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff814e7590-ffffffff814e75c2: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151b420)
Location: fs/seq_file.c:903
Inline: True
Direct callers:
  - kernel/module/procfs.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - kernel/trace/rv/rv.c:available_monitors_start
  - kernel/trace/rv/rv_reactors.c:reactors_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch2_start
  - block/mq-deadline.c:deadline_dispatch1_start
  - block/mq-deadline.c:deadline_dispatch0_start
  - block/mq-deadline.c:deadline_write2_fifo_start
  - block/mq-deadline.c:deadline_read2_fifo_start
  - block/mq-deadline.c:deadline_write1_fifo_start
  - block/mq-deadline.c:deadline_read1_fifo_start
  - block/mq-deadline.c:deadline_write0_fifo_start
  - block/mq-deadline.c:deadline_read0_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff8151b420-ffffffff8151b452: seq_list_start (STB_GLOBAL)
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
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bb620)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffff8000103bb620-ffff8000103bb678: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0598e90)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
c0598e90-c0598ee4: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b8ab0)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
c0000000004b8ab0-c0000000004b8af8: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d1c6)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffe00027d1c6-ffffffe00027d206: seq_list_start (STB_GLOBAL)
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
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300250)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff81300250-ffffffff8130027a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f0e70)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff812f0e70-ffffffff812f0e9a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe040)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff812fe040-ffffffff812fe06a: seq_list_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct list_head *seq_list_start(struct list_head *head, loff_t pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f380)
Location: fs/seq_file.c:896
Inline: True
Direct callers:
  - kernel/module.c:m_start
  - kernel/kprobes.c:kprobe_blacklist_seq_start
  - kernel/trace/trace.c:tracing_err_log_seq_start
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_dynevent.c:dyn_event_seq_start
  - mm/slab_common.c:memcg_slab_start
  - mm/slab_common.c:slab_start
  - mm/vmalloc.c:s_start
  - fs/namespace.c:m_start
  - fs/proc/base.c:timers_start
  - fs/proc/proc_tty.c:t_start
  - crypto/proc.c:c_start
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
  - lib/error-inject.c:ei_seq_start
  - drivers/pwm/core.c:pwm_seq_start
  - drivers/char/misc.c:misc_seq_start
```
**Symbols:**

```
ffffffff8130f380-ffffffff8130f3aa: seq_list_start (STB_GLOBAL)
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
