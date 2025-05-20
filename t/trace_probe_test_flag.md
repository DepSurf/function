# Function: <code>trace_probe_test_flag</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811c6030)
Location: kernel/trace/trace_probe.h:240
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cdb70)
Location: kernel/trace/trace_probe.h:240
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811d1d9e)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811da1c1)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ee78f)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6c6c)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ec9df)
Location: kernel/trace/trace_probe.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f580c)
Location: kernel/trace/trace_probe.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ed73f)
Location: kernel/trace/trace_probe.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f66fc)
Location: kernel/trace/trace_probe.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff8120a3f8)
Location: kernel/trace/trace_probe.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121e7af)
Location: kernel/trace/trace_probe.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff81226984)
Location: kernel/trace/trace_probe.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812463a9)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125de0f)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812665be)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812933a9)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ae8cf)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b845e)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812b057f)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812d0de7)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dba8d)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
```
```
In kernel/trace/trace_fprobe.c (ffffffff812df38a)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
  - kernel/trace/trace_fprobe.c:fexit_dispatcher
  - kernel/trace/trace_fprobe.c:fexit_dispatcher
  - kernel/trace/trace_fprobe.c:fentry_dispatcher
  - kernel/trace/trace_fprobe.c:fentry_dispatcher
  - kernel/trace/trace_fprobe.c:trace_fprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812ccb3f)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ee8e7)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9b6d)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fd2ea)
Location: kernel/trace/trace_probe.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
  - kernel/trace/trace_fprobe.c:fexit_dispatcher
  - kernel/trace/trace_fprobe.c:fexit_dispatcher
  - kernel/trace/trace_fprobe.c:fentry_dispatcher
  - kernel/trace/trace_fprobe.c:fentry_dispatcher
  - kernel/trace/trace_fprobe.c:trace_fprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffff800010251f64)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a8e4)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (c0484e58)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (c048d95c)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (c0000000002f0444)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (c0000000002fe29c)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ca3be)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d27e1)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811bd18e)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c55b1)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811c818e)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d05b1)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811d63ee)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811de851)
Location: kernel/trace/trace_probe.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
```
</details>
</li>
</ul>

## Differences
