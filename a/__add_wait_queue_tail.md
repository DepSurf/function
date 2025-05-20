# Function: <code>__add_wait_queue_tail</code>

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
In kernel/sched/wait.c (ffffffff810c326a)
Location: include/linux/wait.h:129
Inline: True
Inline callers:
  - kernel/sched/wait.c:add_wait_queue_exclusive
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/completion.c (ffffffff81820de3)
Location: include/linux/wait.h:129
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_io
```
```
In fs/timerfd.c (ffffffff8125839a)
Location: include/linux/wait.h:129
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/fuse/dev.c (ffffffff81310c95)
Location: include/linux/wait.h:129
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
In kernel/sched/wait.c (ffffffff810c72e9)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff8189b4b8)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/timerfd.c (ffffffff81280ca1)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/fuse/dev.c (ffffffff81345103)
Location: include/linux/wait.h:180
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
In kernel/sched/wait.c (ffffffff810cd198)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:add_wait_queue_exclusive
```
```
In kernel/sched/completion.c (ffffffff818cfad8)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In mm/filemap.c (ffffffff811afea5)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In fs/timerfd.c (ffffffff812947e1)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/fuse/dev.c (ffffffff8135aec2)
Location: include/linux/wait.h:180
Inline: True
```
</details>
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
