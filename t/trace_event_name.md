# Function: <code>trace_event_name</code>

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
In kernel/trace/trace_output.c (ffffffff811534ca)
Location: include/linux/trace_events.h:311
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff8115dac7)
Location: include/linux/trace_events.h:311
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:trace_event_init
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81165ae8)
Location: include/linux/trace_events.h:311
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_kprobe.c (ffffffff811679f1)
Location: include/linux/trace_events.h:311
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116e641)
Location: include/linux/trace_events.h:311
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probes_profile_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
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
In kernel/trace/trace_output.c (ffffffff8115d9ba)
Location: include/linux/trace_events.h:283
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff81fade72)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81170148)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_kprobe.c (ffffffff81175680)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c714)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:probes_profile_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
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
In kernel/trace/trace_output.c (ffffffff8116842a)
Location: include/linux/trace_events.h:283
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff81fea2ef)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117b8b8)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_kprobe.c (ffffffff81181070)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188324)
Location: include/linux/trace_events.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:probes_profile_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
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
In kernel/trace/trace_output.c (ffffffff8116b51a)
Location: include/linux/trace_events.h:287
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff820cad08)
Location: include/linux/trace_events.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117e598)
Location: include/linux/trace_events.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_kprobe.c (ffffffff81183e3e)
Location: include/linux/trace_events.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118afab)
Location: include/linux/trace_events.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:probes_profile_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
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
In kernel/trace/trace_output.c (ffffffff811785aa)
Location: include/linux/trace_events.h:312
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff826d3377)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118be38)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_kprobe.c (ffffffff81191b9e)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198a5b)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:probes_profile_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
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
In kernel/trace/trace_output.c (ffffffff811877be)
Location: include/linux/trace_events.h:312
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff826fdb71)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119a89c)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811a21a4)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a8a11)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:probes_profile_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811afd4d)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:probes_profile_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
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
In kernel/trace/trace_output.c (ffffffff8119512e)
Location: include/linux/trace_events.h:312
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff828b4a8b)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a8a8c)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b0fd3)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b6dd1)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811be3bd)
Location: include/linux/trace_events.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_output.c (ffffffff811a2ddf)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff828cd87e)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b69dc)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bf4e1)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c5e82)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cdfbd)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_output.c (ffffffff811ae7df)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff828d5df4)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c201c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cad31)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d1be2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811da61d)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c57eb)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff811d5149)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dbbc8)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dffe4)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e6b26)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:local_field_var_ref
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ee552)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f70ad)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811d7333-ffffffff811d7345: trace_event_name.isra.0 (STB_LOCAL)
ffffffff811ebb50-ffffffff811ebb61: trace_event_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c2e1b)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff811d22d9)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d8cf8)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_synth.c (ffffffff81be6323)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e44e6)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:local_field_var_ref
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec7a2)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5c5d)
Location: include/linux/trace_events.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff81be6098-ffffffff81be60aa: trace_event_name.isra.0 (STB_LOCAL)
ffffffff811e9ca0-ffffffff811e9cb1: trace_event_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c3e1b)
Location: include/linux/trace_events.h:391
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff811d37d9)
Location: include/linux/trace_events.h:391
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:test_event_printk
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811da278)
Location: include/linux/trace_events.h:391
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_synth.c (ffffffff81bd7fde)
Location: include/linux/trace_events.h:391
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5ac6)
Location: include/linux/trace_events.h:391
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ed532)
Location: include/linux/trace_events.h:391
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6b4d)
Location: include/linux/trace_events.h:391
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811d2590-ffffffff811d25a1: trace_event_name.isra.0 (STB_LOCAL)
ffffffff811eaba0-ffffffff811eabb1: trace_event_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811ef08b)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff8120056d)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:test_event_printk
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81207b21)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_eprobe.c (ffffffff8120aaee)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_events_synth.c (ffffffff81cb6d8c)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812168c8)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121e5a2)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff81224e9b)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff8122811d)
Location: include/linux/trace_events.h:440
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff811ff2f0-ffffffff811ff301: trace_event_name.isra.0 (STB_LOCAL)
ffffffff8121b9a0-ffffffff8121b9b1: trace_event_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81228a0f)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff8123c0ed)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812439d4)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_eprobe.c (ffffffff81246b27)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_events_synth.c (ffffffff81e67dd0)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff81254ee0)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:last_cmd_set
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125dbb1)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff81264d53)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812681fc)
Location: include/linux/trace_events.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff81e672ed-ffffffff81e6730d: trace_event_name.isra.0 (STB_LOCAL)
ffffffff8125ad80-ffffffff8125ada1: trace_event_name.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_output.c (ffffffff812740e2)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff8128b64d)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812915a4)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_eprobe.c (ffffffff81293c6a)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_events_synth.c (ffffffff81297a25)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a4376)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:last_cmd_set
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ae621)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812b68f3)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ba3bc)
Location: include/linux/trace_events.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8128caaa)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:print_event_fields
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff812a854d)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
Direct callers:
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812ae804)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b0d5a)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b4b95)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c2239)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:last_cmd_set
```
```
In kernel/trace/trace_kprobe.c (ffffffff812d0b11)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812d9de3)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dd9b1)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e0190)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - kernel/trace/trace_fprobe.c:trace_fprobe_match
```
**Symbols:**

```
ffffffff812a46e0-ffffffff812a4701: trace_event_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812a7e7a)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:print_event_fields
  - kernel/trace/trace_output.c:trace_raw_output_prep
```
```
In kernel/trace/trace_events.c (ffffffff812c425d)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_callback
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:test_event_printk
  - kernel/trace/trace_events.c:test_event_printk
Direct callers:
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cad24)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cd31a)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d12a3)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
```
In kernel/trace/trace_events_hist.c (ffffffff812de6a1)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ee57e)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812f7d43)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fbaa1)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fe0f0)
Location: include/linux/trace_events.h:463
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - kernel/trace/trace_fprobe.c:trace_fprobe_match
```
**Symbols:**

```
ffffffff812c0040-ffffffff812c0061: trace_event_name.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_output.c (ffff80001022bc78)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffff80001144e6fc)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff800010241738)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffff80001024a174)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffff800010251d78)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffff80001025ad14)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (c046927c)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (c1528db8)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
Direct callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c047d190)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_kprobe.c (c0484c58)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (c048ddec)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
c04759c4-c04759e0: trace_event_name.part.0 (STB_LOCAL)
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
In kernel/trace/trace_output.c (c0000000002b3eac)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (c0000000013751e8)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d2cf4)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (c0000000002e5000)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (c0000000002f01c8)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (c0000000002fe850)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_output.c (ffffffe000185c80)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffe00000ed42)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffe00019670c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
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
In kernel/trace/trace_output.c (ffffffff811a6dff)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff828beca5)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ba63c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c3351)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ca202)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d2c3d)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_output.c (ffffffff81199d7f)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff828b7345)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ad41c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b6131)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bcfd2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c5a0d)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_output.c (ffffffff811a4bcf)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff828d1a28)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b840c)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c1121)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c7fd2)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0a0d)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_output.c (ffffffff811b296f)
Location: include/linux/trace_events.h:313
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff828d6e49)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_enable_print
  - kernel/trace/trace_events.c:__find_event_file
  - kernel/trace/trace_events.c:event_init
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:system_enable_read
  - kernel/trace/trace_events.c:t_show
  - kernel/trace/trace_events.c:__ftrace_set_clr_event_nolock
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c64ac)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cf1c1)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d6232)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811deccd)
Location: include/linux/trace_events.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
</details>
</li>
</ul>

## Differences
