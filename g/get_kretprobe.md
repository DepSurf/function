# Function: <code>get_kretprobe</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193637)
Location: include/linux/kprobes.h:231
Inline: True
Inline callers:
  - kernel/kprobes.c:__kretprobe_trampoline_handler
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb4e0)
Location: include/linux/kprobes.h:231
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
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
In kernel/kprobes.c (ffffffff811945e4)
Location: include/linux/kprobes.h:231
Inline: True
Inline callers:
  - kernel/kprobes.c:__kretprobe_trampoline_handler
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec8b0)
Location: include/linux/kprobes.h:231
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
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
In kernel/kprobes.c (ffffffff811bd484)
Location: include/linux/kprobes.h:225
Inline: True
Inline callers:
  - kernel/kprobes.c:__kretprobe_trampoline_handler
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d910)
Location: include/linux/kprobes.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125c6f0)
Location: include/linux/kprobes.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ae270)
Location: include/linux/kprobes.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812cfe80)
Location: include/linux/kprobes.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ed880)
Location: include/linux/kprobes.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
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
