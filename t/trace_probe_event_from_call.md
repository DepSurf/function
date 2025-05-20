# Function: <code>trace_probe_event_from_call</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d1d80)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811da7f0)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (ffffffff811ee770)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f72b0)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (ffffffff811ec9c0)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5e60)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (ffffffff811ed720)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6d50)
Location: kernel/trace/trace_probe.h:294
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_eprobe.c (ffffffff8120a38d)
Location: kernel/trace/trace_probe.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:print_eprobe_event
  - kernel/trace/trace_eprobe.c:eprobe_event_define_fields
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121e790)
Location: kernel/trace/trace_probe.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:bpf_get_kprobe_info
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff81228320)
Location: kernel/trace/trace_probe.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:bpf_get_uprobe_info
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_probe.h:295
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:295
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_probe.h:295
Inline: True
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
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_probe.h:300
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:300
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_probe.h:300
Inline: True
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
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
```
```
In kernel/trace/trace_fprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
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
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
```
```
In kernel/trace/trace_fprobe.c (0)
Location: kernel/trace/trace_probe.h:304
Inline: True
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
In kernel/trace/trace_kprobe.c (ffff800010251f48)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffff80001025af00)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (c0484e44)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (c048dff8)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (c0000000002f0428)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (c0000000002feae8)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (ffffffff811ca3a0)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d2e10)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (ffffffff811bd170)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c5be0)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (ffffffff811c8170)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0be0)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
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
In kernel/trace/trace_kprobe.c (ffffffff811d63d0)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kretprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:kprobe_event_define_fields
  - kernel/trace/trace_kprobe.c:print_kretprobe_event
  - kernel/trace/trace_kprobe.c:print_kprobe_event
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
```
In kernel/trace/trace_uprobe.c (ffffffff811deea0)
Location: kernel/trace/trace_probe.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:destroy_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_event_define_fields
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:print_uprobe_event
```
</details>
</li>
</ul>

## Differences
