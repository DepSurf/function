# Function: <code>trace_probe_name</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811c3975)
Location: kernel/trace/trace_probe.h:263
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cbe55)
Location: kernel/trace/trace_probe.h:263
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811cf376)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d820f)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ebf85)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5b0d)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ea0d5)
Location: kernel/trace/trace_probe.h:277
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f449d)
Location: kernel/trace/trace_probe.h:277
Inline: True
Inline callers:
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb2d5)
Location: kernel/trace/trace_probe.h:277
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f548d)
Location: kernel/trace/trace_probe.h:277
Inline: True
Inline callers:
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff8120a67f)
Location: kernel/trace/trace_probe.h:279
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c045)
Location: kernel/trace/trace_probe.h:279
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff81224e9b)
Location: kernel/trace/trace_probe.h:279
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff8122758d)
Location: kernel/trace/trace_probe.h:279
Inline: True
Inline callers:
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81246678)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125ca86)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff81264d53)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812676e4)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81293855)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff812abb33)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812b68f3)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b9831)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812b073a)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce418)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812d9de3)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dcacb)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e0182)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - kernel/trace/trace_fprobe.c:trace_fprobe_match
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
In kernel/trace/trace_eprobe.c (ffffffff812cccfa)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ebe18)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812f7d43)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fabab)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:print_uprobe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fe0e2)
Location: kernel/trace/trace_probe.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:print_fexit_event
  - kernel/trace/trace_fprobe.c:print_fentry_event
  - kernel/trace/trace_fprobe.c:trace_fprobe_match
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
In kernel/trace/trace_kprobe.c (ffff80001024fc34)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffff80001025863c)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0483a14)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (c048cf2c)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002ed520)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (c0000000002fb67c)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811c7996)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d082f)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811ba776)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c35ff)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811c5766)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce5ff)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811d39c6)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dc85f)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
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
