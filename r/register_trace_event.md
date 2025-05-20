# Function: <code>register_trace_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81153ee0)
Location: kernel/trace/trace_output.c:671
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81153ee0-ffffffff8115414b: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8115d0a0)
Location: kernel/trace/trace_output.c:675
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8115d0a0-ffffffff8115d358: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81167b10)
Location: kernel/trace/trace_output.c:675
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81167b10-ffffffff81167dc8: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8116ad80)
Location: kernel/trace/trace_output.c:745
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8116ad80-ffffffff8116afd7: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81177e60)
Location: kernel/trace/trace_output.c:736
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81177e60-ffffffff811780b7: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:737
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811883a8-ffffffff811883be: register_trace_event.cold.11 (STB_LOCAL)
ffffffff81187060-ffffffff811872c5: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff81195c58-ffffffff81195c6e: register_trace_event.cold.9 (STB_LOCAL)
ffffffff811949d0-ffffffff81194c35: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff811a39ad-ffffffff811a3a0e: register_trace_event.cold (STB_LOCAL)
ffffffff811a26f0-ffffffff811a2929: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff811af2f8-ffffffff811af30e: register_trace_event.cold (STB_LOCAL)
ffffffff811ae0d0-ffffffff811ae326: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:728
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff811c73d8-ffffffff811c73ee: register_trace_event.cold (STB_LOCAL)
ffffffff811c6930-ffffffff811c6b50: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:728
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff81be5aaf-ffffffff81be5ac5: register_trace_event.cold (STB_LOCAL)
ffffffff811c3f60-ffffffff811c4171: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:746
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff81bd7965-ffffffff81bd797b: register_trace_event.cold (STB_LOCAL)
ffffffff811c4eb0-ffffffff811c50c1: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:751
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff81cb588f-ffffffff81cb58a5: register_trace_event.cold (STB_LOCAL)
ffffffff811f03f0-ffffffff811f0601: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81228ae0)
Location: kernel/trace/trace_output.c:751
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff81228ae0-ffffffff81228d2f: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812741c0)
Location: kernel/trace/trace_output.c:736
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff812741c0-ffffffff81274332: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8128aef0)
Location: kernel/trace/trace_output.c:739
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff8128aef0-ffffffff8128b062: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812a62a0)
Location: kernel/trace/trace_output.c:739
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff812a62a0-ffffffff812a6412: register_trace_event (STB_GLOBAL)
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
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffff80001022b4a8)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffff80001022b4a8-ffff80001022b748: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0468aa4)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
c0468aa4-c0468d38: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0000000002b33a0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
c0000000002b33a0-c0000000002b372c: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffe00018560c)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
```
**Symbols:**

```
ffffffe00018560c-ffffffe0001857c8: register_trace_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff811a7918-ffffffff811a792e: register_trace_event.cold (STB_LOCAL)
ffffffff811a66f0-ffffffff811a6946: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff8119a898-ffffffff8119a8ae: register_trace_event.cold (STB_LOCAL)
ffffffff81199670-ffffffff811998c6: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff811a56e8-ffffffff811a56fe: register_trace_event.cold (STB_LOCAL)
ffffffff811a44c0-ffffffff811a4716: register_trace_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_trace_event(struct trace_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_output.c (0)
Location: kernel/trace/trace_output.c:716
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:init_events
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
  - kernel/trace/trace_events.c:trace_event_raw_init
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
**Symbols:**

```
ffffffff811b3488-ffffffff811b349e: register_trace_event.cold (STB_LOCAL)
ffffffff811b2250-ffffffff811b24a6: register_trace_event (STB_GLOBAL)
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
