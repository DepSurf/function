# Function: <code>__next_thread</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81106ffc)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/exit.c:__do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff8111ab5d)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81238bf4)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/bpf/task_iter.c (ffffffff81349c31)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In fs/exec.c (ffffffff814eb0c1)
Location: include/linux/sched/signal.h:716
Inline: True
```
```
In fs/proc/base.c (ffffffff815a916b)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
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
