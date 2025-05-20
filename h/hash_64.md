# Function: <code>hash_64</code>

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
In arch/x86/mm/kmmio.c (ffffffff810735df)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In kernel/workqueue.c (ffffffff810980e5)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In kernel/cgroup.c (ffffffff81115a07)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8112c8e5)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/trace/ftrace.c (ffffffff81140030)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
```
In kernel/events/core.c (ffffffff81180411)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/filemap.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In mm/ksm.c (ffffffff811e69f1)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/huge_memory.c (ffffffff811f7889)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - mm/huge_memory.c:__khugepaged_enter
```
```
In fs/namei.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In fs/locks.c (ffffffff8126042e)
Location: include/linux/hash.h:35
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff8137101a)
Location: include/linux/hash.h:35
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/linux/hash.h:35
Inline: True
```
```
In block/elevator.c (ffffffff813b3bcf)
Location: include/linux/hash.h:35
Inline: True
```
</details>
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
