# Function: <code>call_fetch</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811675fa)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff8116cdd2)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_deref_u8
  - kernel/trace/trace_probe.c:fetch_deref_u16
  - kernel/trace/trace_probe.c:fetch_deref_u64
  - kernel/trace/trace_probe.c:fetch_deref_string
  - kernel/trace/trace_probe.c:fetch_deref_string_size
  - kernel/trace/trace_probe.c:fetch_bitfield_u8
  - kernel/trace/trace_probe.c:fetch_bitfield_u16
  - kernel/trace/trace_probe.c:fetch_bitfield_u32
  - kernel/trace/trace_probe.c:fetch_bitfield_u64
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116fc97)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
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
In kernel/trace/trace_kprobe.c (ffffffff81174df2)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff8117a67d)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_bitfield_u64
  - kernel/trace/trace_probe.c:fetch_bitfield_u32
  - kernel/trace/trace_probe.c:fetch_bitfield_u16
  - kernel/trace/trace_probe.c:fetch_bitfield_u8
  - kernel/trace/trace_probe.c:fetch_deref_string_size
  - kernel/trace/trace_probe.c:fetch_deref_string
  - kernel/trace/trace_probe.c:fetch_deref_u64
  - kernel/trace/trace_probe.c:fetch_deref_u16
  - kernel/trace/trace_probe.c:fetch_deref_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117d3b7)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
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
In kernel/trace/trace_kprobe.c (ffffffff81180872)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff8118614d)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_bitfield_u64
  - kernel/trace/trace_probe.c:fetch_bitfield_u32
  - kernel/trace/trace_probe.c:fetch_bitfield_u16
  - kernel/trace/trace_probe.c:fetch_bitfield_u8
  - kernel/trace/trace_probe.c:fetch_deref_string_size
  - kernel/trace/trace_probe.c:fetch_deref_string
  - kernel/trace/trace_probe.c:fetch_deref_u64
  - kernel/trace/trace_probe.c:fetch_deref_u16
  - kernel/trace/trace_probe.c:fetch_deref_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188fc7)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
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
In kernel/trace/trace_kprobe.c (ffffffff81183787)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff81188e6d)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_bitfield_u64
  - kernel/trace/trace_probe.c:fetch_bitfield_u32
  - kernel/trace/trace_probe.c:fetch_bitfield_u16
  - kernel/trace/trace_probe.c:fetch_bitfield_u8
  - kernel/trace/trace_probe.c:fetch_deref_string_size
  - kernel/trace/trace_probe.c:fetch_deref_u64
  - kernel/trace/trace_probe.c:fetch_deref_u32
  - kernel/trace/trace_probe.c:fetch_deref_u16
  - kernel/trace/trace_probe.c:fetch_deref_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118bcdf)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
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
In kernel/trace/trace_kprobe.c (ffffffff8119143b)
Location: kernel/trace/trace_probe.h:316
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff81196aed)
Location: kernel/trace/trace_probe.h:316
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_bitfield_u64
  - kernel/trace/trace_probe.c:fetch_bitfield_u32
  - kernel/trace/trace_probe.c:fetch_bitfield_u16
  - kernel/trace/trace_probe.c:fetch_bitfield_u8
  - kernel/trace/trace_probe.c:fetch_deref_string_size
  - kernel/trace/trace_probe.c:fetch_deref_u64
  - kernel/trace/trace_probe.c:fetch_deref_u32
  - kernel/trace/trace_probe.c:fetch_deref_u16
  - kernel/trace/trace_probe.c:fetch_deref_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8119978b)
Location: kernel/trace/trace_probe.h:316
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
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
In kernel/trace/trace_kprobe.c (ffffffff811a6971)
Location: kernel/trace/trace_probe.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_probe.c (ffffffff811ac3a3)
Location: kernel/trace/trace_probe.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:fetch_bitfield_u64
  - kernel/trace/trace_probe.c:fetch_bitfield_u32
  - kernel/trace/trace_probe.c:fetch_bitfield_u16
  - kernel/trace/trace_probe.c:fetch_bitfield_u8
  - kernel/trace/trace_probe.c:fetch_deref_string_size
  - kernel/trace/trace_probe.c:fetch_deref_u64
  - kernel/trace/trace_probe.c:fetch_deref_u32
  - kernel/trace/trace_probe.c:fetch_deref_u16
  - kernel/trace/trace_probe.c:fetch_deref_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff811aef98)
Location: kernel/trace/trace_probe.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
