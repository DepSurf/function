# Function: <code>trace_probe_event_call</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff828cece6)
Location: kernel/trace/trace_probe.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
```
```
In kernel/trace/trace_probe.c (ffffffff811cb9b0)
Location: kernel/trace/trace_probe.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce12d)
Location: kernel/trace/trace_probe.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
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
In kernel/trace/trace_kprobe.c (ffffffff828d71b6)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d79f0)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811da734)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff82cf6d09)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_boot_kprobe_events
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f4390)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f71d7)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
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
In kernel/trace/trace_kprobe.c (ffffffff82fe3810)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_boot_kprobe_events
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f2d40)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5d87)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
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
In kernel/trace/trace_kprobe.c (ffffffff831ee038)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff811f3bc0)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6c77)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
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
In kernel/trace/trace_eprobe.c (ffffffff8120ae01)
Location: kernel/trace/trace_probe.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff832d2cfe)
Location: kernel/trace/trace_probe.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81224e80)
Location: kernel/trace/trace_probe.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff81228246)
Location: kernel/trace/trace_probe.h:290
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_eprobe.c (ffffffff81246f89)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff8348716c)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81264d30)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff81268358)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_eprobe.c (ffffffff8129406e)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff83eb6ba1)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812b68d0)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ba528)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812b1023)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff836dc181)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812d9dc0)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ddb38)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812dfcd4)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
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
In kernel/trace/trace_eprobe.c (ffffffff812cd5f4)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (ffffffff8390e7b1)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812f7d20)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fbc28)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fdc34)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
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
In kernel/trace/trace_kprobe.c (ffff80001144fb98)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffff800010257d60)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffff80001025ae20)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
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
In kernel/trace/trace_kprobe.c (c152a378)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (c048aea0)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (c048df38)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
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
In kernel/trace/trace_kprobe.c (c000000001376e7c)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c0000000002f9d8c)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (c0000000002fe9e4)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/trace/trace_kprobe.c (ffffffff828c0067)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d0010)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d2d54)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff828b8707)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811c2de0)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c5b24)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff828d2dea)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cdde0)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0b24)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff828d820b)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811dc040)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
  - kernel/trace/trace_probe.c:trace_probe_init
  - kernel/trace/trace_probe.c:traceprobe_set_print_fmt
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dede4)
Location: kernel/trace/trace_probe.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
</ul>

## Differences
