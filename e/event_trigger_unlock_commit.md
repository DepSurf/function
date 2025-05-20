# Function: <code>event_trigger_unlock_commit</code>

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
In kernel/trace/trace_events.c (ffffffff8115feb9)
Location: include/linux/trace_events.h:509
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81161e81)
Location: include/linux/trace_events.h:509
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116fab7)
Location: include/linux/trace_events.h:509
Inline: True
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
In kernel/trace/trace_events.c (ffffffff8116a499)
Location: kernel/trace/trace.h:1183
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c770)
Location: kernel/trace/trace.h:1183
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117d1a7)
Location: kernel/trace/trace.h:1183
Inline: True
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
In kernel/trace/trace.c (ffffffff81163250)
Location: kernel/trace/trace.h:1202
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81177a2b)
Location: kernel/trace/trace.h:1202
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188db7)
Location: kernel/trace/trace.h:1202
Inline: True
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
In kernel/trace/trace.c (ffffffff811666f0)
Location: kernel/trace/trace.h:1318
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff8117a695)
Location: kernel/trace/trace.h:1318
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b9c2)
Location: kernel/trace/trace.h:1318
Inline: True
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
In kernel/trace/trace.c (ffffffff81173680)
Location: kernel/trace/trace.h:1320
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81187f02)
Location: kernel/trace/trace.h:1320
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199462)
Location: kernel/trace/trace.h:1320
Inline: True
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
In kernel/trace/trace.c (ffffffff81182660)
Location: kernel/trace/trace.h:1325
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81197146)
Location: kernel/trace/trace.h:1325
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811aec8e)
Location: kernel/trace/trace.h:1325
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ffc0)
Location: kernel/trace/trace.h:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a5298)
Location: kernel/trace/trace.h:1388
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd20e)
Location: kernel/trace/trace.h:1388
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d763)
Location: kernel/trace/trace.h:1434
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b340f)
Location: kernel/trace/trace.h:1434
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cca6b)
Location: kernel/trace/trace.h:1434
Inline: True
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
In kernel/trace/trace.c (ffffffff811a9133)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811be9ff)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d900a)
Location: kernel/trace/trace.h:1454
Inline: True
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
In kernel/trace/trace_syscalls.c (ffffffff811d822e)
Location: kernel/trace/trace.h:1521
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4d0b)
Location: kernel/trace/trace.h:1521
Inline: True
Inline callers:
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
In kernel/trace/trace_syscalls.c (ffffffff811d52ee)
Location: kernel/trace/trace.h:1377
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f369b)
Location: kernel/trace/trace.h:1377
Inline: True
Inline callers:
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
In kernel/trace/trace_syscalls.c (ffffffff811d695d)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4612)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
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
In kernel/trace/trace_syscalls.c (ffffffff81203807)
Location: kernel/trace/trace.h:1398
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225981)
Location: kernel/trace/trace.h:1398
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225df0)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffff80001023dfe4)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a650)
Location: kernel/trace/trace.h:1454
Inline: True
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
In kernel/trace/trace.c (c0463328)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (c0479620)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (c048c0f0)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
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
In kernel/trace/trace.c (c0000000002ab718)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (c0000000002cd920)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc160)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000180c3c)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffe0001939fa)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
</details>
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
In kernel/trace/trace.c (ffffffff811a1753)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b701f)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d162a)
Location: kernel/trace/trace.h:1454
Inline: True
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
In kernel/trace/trace.c (ffffffff81194723)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9e08)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c43fa)
Location: kernel/trace/trace.h:1454
Inline: True
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
In kernel/trace/trace.c (ffffffff8119f523)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4def)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf3fa)
Location: kernel/trace/trace.h:1454
Inline: True
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
In kernel/trace/trace.c (ffffffff811ad2a3)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2e8f)
Location: kernel/trace/trace.h:1454
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd69a)
Location: kernel/trace/trace.h:1454
Inline: True
```
</details>
</li>
</ul>

## Differences
