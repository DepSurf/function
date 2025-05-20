# Function: <code>process_common_fetch_insn</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812b1304)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cee6f)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e158d)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff812cd8b4)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec86f)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff5dd)
Location: kernel/trace/trace_probe_tmpl.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
</details>
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
