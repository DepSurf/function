# Function: <code>trace_probe_group_name</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811c368f)
Location: kernel/trace/trace_probe.h:268
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cbc8c)
Location: kernel/trace/trace_probe.h:268
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811ceec1)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d7f80)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811ebdac)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f54e0)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811e9efc)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3e70)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811eb0fc)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4b20)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
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
In kernel/trace/trace_eprobe.c (ffffffff8120a566)
Location: kernel/trace/trace_probe.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121bf0c)
Location: kernel/trace/trace_probe.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff81224eaf)
Location: kernel/trace/trace_probe.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225ed0)
Location: kernel/trace/trace_probe.h:284
Inline: True
Inline callers:
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
In kernel/trace/trace_eprobe.c (ffffffff8124653d)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125c933)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff81264d60)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff81267095)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_eprobe.c (ffffffff81293715)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ab9c3)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812b6900)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b90e5)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
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
In kernel/trace/trace_eprobe.c (ffffffff812b0a15)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce2a3)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812d9df0)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dc745)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e01a2)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812cce15)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_match
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ebca3)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_probe.c (ffffffff812f7d50)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_register_event_call
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa825)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fe102)
Location: kernel/trace/trace_probe.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
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
In kernel/trace/trace_kprobe.c (ffff80001024f708)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffff800010258374)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (c04838d4)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (c048c5d8)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (c0000000002ecd88)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (c0000000002fb028)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811c74e1)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d05a0)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811ba2c1)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3370)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811c52b1)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce370)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811d3511)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:find_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_match
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dc5d0)
Location: kernel/trace/trace_probe.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:find_probe_event
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
</details>
</li>
</ul>

## Differences
