# Function: <code>__trace_event_discard_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115669f)
Location: kernel/trace/trace.h:1123
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8116a4b0)
Location: kernel/trace/trace.h:1123
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c78f)
Location: kernel/trace/trace.h:1123
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff81175c6c)
Location: kernel/trace/trace.h:1123
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117d1c8)
Location: kernel/trace/trace.h:1123
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
In kernel/trace/trace.c (ffffffff8116326b)
Location: kernel/trace/trace.h:1142
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81177a53)
Location: kernel/trace/trace.h:1142
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff8118165c)
Location: kernel/trace/trace.h:1142
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188dd8)
Location: kernel/trace/trace.h:1142
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
In kernel/trace/trace.c (ffffffff81166703)
Location: kernel/trace/trace.h:1258
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff8117a6c1)
Location: kernel/trace/trace.h:1258
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811843f4)
Location: kernel/trace/trace.h:1258
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b9f1)
Location: kernel/trace/trace.h:1258
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
In kernel/trace/trace.c (ffffffff81173693)
Location: kernel/trace/trace.h:1260
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff81187f2e)
Location: kernel/trace/trace.h:1260
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff8119215d)
Location: kernel/trace/trace.h:1260
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199491)
Location: kernel/trace/trace.h:1260
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
In kernel/trace/trace.c (ffffffff811827a4)
Location: kernel/trace/trace.h:1265
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811971cc)
Location: kernel/trace/trace.h:1265
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a784f)
Location: kernel/trace/trace.h:1265
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811aed01)
Location: kernel/trace/trace.h:1265
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
In kernel/trace/trace.c (ffffffff81190104)
Location: kernel/trace/trace.h:1328
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a531e)
Location: kernel/trace/trace.h:1328
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b65a5)
Location: kernel/trace/trace.h:1328
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd281)
Location: kernel/trace/trace.h:1328
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
In kernel/trace/trace.c (ffffffff8119d8a8)
Location: kernel/trace/trace.h:1374
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b34b5)
Location: kernel/trace/trace.h:1374
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c5626)
Location: kernel/trace/trace.h:1374
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ccae3)
Location: kernel/trace/trace.h:1374
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
In kernel/trace/trace.c (ffffffff811a9278)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811beaa5)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d12d5)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d9082)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (ffffffff811bcd54)
Location: kernel/trace/trace.h:1461
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d8311)
Location: kernel/trace/trace.h:1461
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4df0)
Location: kernel/trace/trace.h:1461
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
In kernel/trace/trace.c (ffffffff811ba966)
Location: kernel/trace/trace.h:1317
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d53d1)
Location: kernel/trace/trace.h:1317
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3780)
Location: kernel/trace/trace.h:1317
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
In kernel/trace/trace.c (ffffffff811be6be)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d6a36)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f46f9)
Location: kernel/trace/trace.h:1321
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
In kernel/trace/trace.c (ffffffff811e8f50)
Location: kernel/trace/trace.h:1327
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff812038ea)
Location: kernel/trace/trace.h:1327
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225a87)
Location: kernel/trace/trace.h:1327
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
In kernel/trace/trace.c (ffffffff812221b1)
Location: kernel/trace/trace.h:1335
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:call_filter_check_discard
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
In kernel/trace/trace.c (ffffffff8126d171)
Location: kernel/trace/trace.h:1335
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:call_filter_check_discard
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
In kernel/trace/trace.c (ffffffff81284301)
Location: kernel/trace/trace.h:1368
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:call_filter_check_discard
```
```
In kernel/trace/trace_events_user.c (ffffffff812c3d13)
Location: kernel/trace/trace.h:1368
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_ftrace
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
In kernel/trace/trace.c (ffffffff8129f409)
Location: kernel/trace/trace.h:1386
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:call_filter_check_discard
```
```
In kernel/trace/trace_events_user.c (ffffffff812e0563)
Location: kernel/trace/trace.h:1386
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_ftrace
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
In kernel/trace/trace.c (ffff800010225f38)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffff80001023e0d0)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffff80001025173c)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a750)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (c0463394)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (c04796d4)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c04833b0)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (c048c1f8)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (c0000000002ab8d8)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (c0000000002cda90)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (c0000000002eecc4)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc310)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (ffffffe000180cba)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffe000193a9a)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (ffffffff811a1898)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b70c5)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c98f5)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d16a2)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (ffffffff81194868)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9eae)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bc6ce)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c4472)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (ffffffff8119f668)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4e95)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c76c5)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf472)
Location: kernel/trace/trace.h:1394
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
In kernel/trace/trace.c (ffffffff811ad3e8)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2f35)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d5925)
Location: kernel/trace/trace.h:1394
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd712)
Location: kernel/trace/trace.h:1394
Inline: True
```
</details>
</li>
</ul>

## Differences
