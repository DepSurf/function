# Function: <code>__event_trigger_test_discard</code>

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
In kernel/trace/trace_events.c (ffffffff8115febb)
Location: include/linux/trace_events.h:476
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81161e87)
Location: include/linux/trace_events.h:476
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff81168618)
Location: include/linux/trace_events.h:476
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116fac2)
Location: include/linux/trace_events.h:476
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
In kernel/trace/trace_events.c (ffffffff8116a49b)
Location: kernel/trace/trace.h:1148
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c77a)
Location: kernel/trace/trace.h:1148
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff81175c52)
Location: kernel/trace/trace.h:1148
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117d1b2)
Location: kernel/trace/trace.h:1148
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
In kernel/trace/trace.c (ffffffff81163252)
Location: kernel/trace/trace.h:1167
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81177a2b)
Location: kernel/trace/trace.h:1167
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff81181642)
Location: kernel/trace/trace.h:1167
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188dc2)
Location: kernel/trace/trace.h:1167
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
In kernel/trace/trace.c (ffffffff811666f2)
Location: kernel/trace/trace.h:1283
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff8117a695)
Location: kernel/trace/trace.h:1283
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811843de)
Location: kernel/trace/trace.h:1283
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b9d0)
Location: kernel/trace/trace.h:1283
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
In kernel/trace/trace.c (ffffffff81173682)
Location: kernel/trace/trace.h:1285
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81187f02)
Location: kernel/trace/trace.h:1285
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff81192147)
Location: kernel/trace/trace.h:1285
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199470)
Location: kernel/trace/trace.h:1285
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
Location: kernel/trace/trace.h:1290
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81197146)
Location: kernel/trace/trace.h:1290
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a7713)
Location: kernel/trace/trace.h:1290
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811aec8e)
Location: kernel/trace/trace.h:1290
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
Location: kernel/trace/trace.h:1353
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a5298)
Location: kernel/trace/trace.h:1353
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b6494)
Location: kernel/trace/trace.h:1353
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd20e)
Location: kernel/trace/trace.h:1353
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
Location: kernel/trace/trace.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b340f)
Location: kernel/trace/trace.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c5515)
Location: kernel/trace/trace.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cca6b)
Location: kernel/trace/trace.h:1399
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811be9ff)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d11aa)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d900a)
Location: kernel/trace/trace.h:1419
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
In kernel/trace/trace.c (ffffffff811c12fd)
Location: kernel/trace/trace.h:1486
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d822e)
Location: kernel/trace/trace.h:1486
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4d0b)
Location: kernel/trace/trace.h:1486
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
In kernel/trace/trace.c (ffffffff811bef4c)
Location: kernel/trace/trace.h:1342
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d52ee)
Location: kernel/trace/trace.h:1342
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f369b)
Location: kernel/trace/trace.h:1342
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
In kernel/trace/trace.c (ffffffff811bf7f6)
Location: kernel/trace/trace.h:1346
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d695d)
Location: kernel/trace/trace.h:1346
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4612)
Location: kernel/trace/trace.h:1346
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
In kernel/trace/trace.c (ffffffff811ea146)
Location: kernel/trace/trace.h:1352
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81203807)
Location: kernel/trace/trace.h:1352
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225981)
Location: kernel/trace/trace.h:1352
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
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
In kernel/trace/trace.c (ffffffff81221fd6)
Location: kernel/trace/trace.h:1362
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff8126cf96)
Location: kernel/trace/trace.h:1362
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff81284126)
Location: kernel/trace/trace.h:1395
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff8129f226)
Location: kernel/trace/trace.h:1413
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffff800010225df0)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffff80001023dfe4)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffff800010251620)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a650)
Location: kernel/trace/trace.h:1419
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (c0479620)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c04832a0)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (c048c0f0)
Location: kernel/trace/trace.h:1419
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (c0000000002cd920)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c0000000002eeb2c)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc160)
Location: kernel/trace/trace.h:1419
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffe0001939fe)
Location: kernel/trace/trace.h:1419
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b701f)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c97ca)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d162a)
Location: kernel/trace/trace.h:1419
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9e08)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bc5a3)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c43fa)
Location: kernel/trace/trace.h:1419
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4def)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c759a)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf3fa)
Location: kernel/trace/trace.h:1419
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
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2e8f)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d57fa)
Location: kernel/trace/trace.h:1419
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd69a)
Location: kernel/trace/trace.h:1419
Inline: True
```
</details>
</li>
</ul>

## Differences
