# Function: <code>trace_buffer_unlock_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_buffer_unlock_commit(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114fb20)
Location: kernel/trace/trace.c:1695
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff8114fb20-ffffffff8114fb81: trace_buffer_unlock_commit (STB_GLOBAL)
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
In kernel/trace/trace_sched_wakeup.c (ffffffff81161d54)
Location: kernel/trace/trace.h:1109
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811636b6)
Location: kernel/trace/trace.h:1109
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff81166a91)
Location: kernel/trace/trace.h:1109
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff8116a4da)
Location: kernel/trace/trace.h:1109
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c7d5)
Location: kernel/trace/trace.h:1109
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117d242)
Location: kernel/trace/trace.h:1109
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
In kernel/trace/trace.c (ffffffff81163351)
Location: kernel/trace/trace.h:1128
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c8ae)
Location: kernel/trace/trace.h:1128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8116e9e6)
Location: kernel/trace/trace.h:1128
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff8117233a)
Location: kernel/trace/trace.h:1128
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff81177aa0)
Location: kernel/trace/trace.h:1128
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188e52)
Location: kernel/trace/trace.h:1128
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
In kernel/trace/trace.c (ffffffff81166729)
Location: kernel/trace/trace.h:1244
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fc5e)
Location: kernel/trace/trace.h:1244
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81171c02)
Location: kernel/trace/trace.h:1244
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff8117570d)
Location: kernel/trace/trace.h:1244
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff8117a746)
Location: kernel/trace/trace.h:1244
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118ba99)
Location: kernel/trace/trace.h:1244
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
In kernel/trace/trace.c (ffffffff811736b9)
Location: kernel/trace/trace.h:1246
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cdb9)
Location: kernel/trace/trace.h:1246
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8117ed92)
Location: kernel/trace/trace.h:1246
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff81182c3b)
Location: kernel/trace/trace.h:1246
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff81187fb1)
Location: kernel/trace/trace.h:1246
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199539)
Location: kernel/trace/trace.h:1246
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
In kernel/trace/trace.c (ffffffff81182687)
Location: kernel/trace/trace.h:1251
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118be7b)
Location: kernel/trace/trace.h:1251
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8118de96)
Location: kernel/trace/trace.h:1251
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff81191dc1)
Location: kernel/trace/trace.h:1251
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff81197160)
Location: kernel/trace/trace.h:1251
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811aeca6)
Location: kernel/trace/trace.h:1251
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
In kernel/trace/trace.c (ffffffff8118ffe7)
Location: kernel/trace/trace.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199899)
Location: kernel/trace/trace.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8119b81d)
Location: kernel/trace/trace.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff8119f5f1)
Location: kernel/trace/trace.h:1314
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a52b0)
Location: kernel/trace/trace.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd226)
Location: kernel/trace/trace.h:1314
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
In kernel/trace/trace.c (ffffffff8119d788)
Location: kernel/trace/trace.h:1360
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a74de)
Location: kernel/trace/trace.h:1360
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811a93d4)
Location: kernel/trace/trace.h:1360
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811ad318)
Location: kernel/trace/trace.h:1360
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b3430)
Location: kernel/trace/trace.h:1360
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cca86)
Location: kernel/trace/trace.h:1360
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
In kernel/trace/trace.c (ffffffff811a9158)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2cce)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b4c04)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811b8b68)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bea20)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d9025)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811cac98)
Location: kernel/trace/trace.h:1447
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cd410)
Location: kernel/trace/trace.h:1447
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff811d1660)
Location: kernel/trace/trace.h:1447
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d8250)
Location: kernel/trace/trace.h:1447
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4d2e)
Location: kernel/trace/trace.h:1447
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8378)
Location: kernel/trace/trace.h:1303
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811ca900)
Location: kernel/trace/trace.h:1303
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff811cea60)
Location: kernel/trace/trace.h:1303
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d5310)
Location: kernel/trace/trace.h:1303
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f36be)
Location: kernel/trace/trace.h:1303
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9b5f)
Location: kernel/trace/trace.h:1307
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cbdef)
Location: kernel/trace/trace.h:1307
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811d0076)
Location: kernel/trace/trace.h:1307
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d697f)
Location: kernel/trace/trace.h:1307
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4635)
Location: kernel/trace/trace.h:1307
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5655)
Location: kernel/trace/trace.h:1313
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811f83d6)
Location: kernel/trace/trace.h:1313
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811fcb4e)
Location: kernel/trace/trace.h:1313
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_syscalls.c (ffffffff8120381f)
Location: kernel/trace/trace.h:1313
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225995)
Location: kernel/trace/trace.h:1313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8122eeda)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812320e7)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff81236a97)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8127aefc)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8127e737)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff81283773)
Location: kernel/trace/trace.h:1321
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
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
In kernel/trace/trace_sched_wakeup.c (ffffffff81292a1c)
Location: kernel/trace/trace.h:1352
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129b1b7)
Location: kernel/trace/trace.h:1352
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff812a041f)
Location: kernel/trace/trace.h:1352
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
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
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae105)
Location: kernel/trace/trace.h:1370
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b6867)
Location: kernel/trace/trace.h:1370
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff812bbb4f)
Location: kernel/trace/trace.h:1370
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
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
In kernel/trace/trace.c (ffff800010225e08)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102309b0)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/blktrace.c (ffff8000102372ac)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffff80001023e000)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a668)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace.c (c0463344)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (c046c9e0)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/blktrace.c (c0472c3c)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_syscalls.c (c0479644)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (c048c110)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace.c (c0000000002ab738)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb0d8)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/blktrace.c (c0000000002c2f90)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (c0000000002cd944)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc180)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace.c (ffffffe000180c70)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe0001892c0)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/blktrace.c (ffffffe00018e178)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffe000193a1a)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace.c (ffffffff811a1778)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab2ee)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811ad224)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811b1188)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b7040)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d1645)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace.c (ffffffff81194748)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e5f7)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811a00b4)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811a4125)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9e29)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c4415)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace.c (ffffffff8119f548)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a90be)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811aaff4)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811aef58)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4e10)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf415)
Location: kernel/trace/trace.h:1380
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
In kernel/trace/trace.c (ffffffff811ad2c8)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6efe)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b8e64)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff811bce5c)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2eb0)
Location: kernel/trace/trace.h:1380
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd6b5)
Location: kernel/trace/trace.h:1380
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
