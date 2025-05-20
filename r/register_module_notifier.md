# Function: <code>register_module_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81104de0)
Location: kernel/module.c:285
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
```
**Symbols:**

```
ffffffff81104de0-ffffffff81104dfa: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110c6c0)
Location: kernel/module.c:287
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
```
**Symbols:**

```
ffffffff8110c6c0-ffffffff8110c6da: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114110)
Location: kernel/module.c:287
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
```
**Symbols:**

```
ffffffff81114110-ffffffff8111412a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114f10)
Location: kernel/module.c:290
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
```
**Symbols:**

```
ffffffff81114f10-ffffffff81114f2a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811204b0)
Location: kernel/module.c:300
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
```
**Symbols:**

```
ffffffff811204b0-ffffffff811204ca: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112df70)
Location: kernel/module.c:299
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff8112df70-ffffffff8112df8a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139860)
Location: kernel/module.c:299
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff81139860-ffffffff8113987a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81144a10)
Location: kernel/module.c:295
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff81144a10-ffffffff81144a2a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811504f0)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff811504f0-ffffffff8115050a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81160ea0)
Location: kernel/module.c:300
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff81160ea0-ffffffff81160eba: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115cfb0)
Location: kernel/module.c:302
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/bpf/btf.c:btf_module_init
  - kernel/static_call.c:static_call_init
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff8115cfb0-ffffffff8115cfca: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e1a0)
Location: kernel/module.c:300
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/bpf/btf.c:btf_module_init
  - kernel/static_call.c:static_call_init
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff8115e1a0-ffffffff8115e1ba: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81183420)
Location: kernel/module.c:301
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/bpf/btf.c:btf_module_init
  - kernel/static_call.c:static_call_init
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff81183420-ffffffff8118343a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118b0c0)
Location: kernel/module/main.c:130
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/bpf/btf.c:btf_module_init
  - kernel/static_call_inline.c:static_call_init
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff8118b0c0-ffffffff8118b0e2: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811c77f0)
Location: kernel/module/main.c:128
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/bpf/btf.c:btf_module_init
  - kernel/static_call_inline.c:static_call_init
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff811c77f0-ffffffff811c7812: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811da670)
Location: kernel/module/main.c:135
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/bpf/btf.c:btf_module_init
  - kernel/static_call_inline.c:static_call_init
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff811da670-ffffffff811da692: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f0320)
Location: kernel/module/main.c:135
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/bpf/btf.c:btf_module_init
  - kernel/static_call_inline.c:static_call_init
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff811f0320-ffffffff811f0342: register_module_notifier (STB_GLOBAL)
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
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bf238)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffff8000101bf238-ffff8000101bf26c: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0406ad0)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
c0406ad0-c0406af8: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000224510)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
c000000000224510-c000000000224550: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001417d2)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
```
**Symbols:**

```
ffffffe0001417d2-ffffffe000141804: register_module_notifier (STB_GLOBAL)
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
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148b10)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff81148b10-ffffffff81148b2a: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113bdc0)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff8113bdc0-ffffffff8113bdda: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811469c0)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff811469c0-ffffffff811469da: register_module_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_module_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811535d0)
Location: kernel/module.c:297
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_module_notifier
  - kernel/kprobes.c:init_kprobes
  - kernel/tracepoint.c:init_tracepoints
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/bpf_trace.c:bpf_event_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/jump_label.c:jump_label_init_module
  - lib/error-inject.c:init_error_injection
```
**Symbols:**

```
ffffffff811535d0-ffffffff811535ea: register_module_notifier (STB_GLOBAL)
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
