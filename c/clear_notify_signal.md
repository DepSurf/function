# Function: <code>clear_notify_signal</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e4e0f)
Location: include/linux/sched/signal.h:354
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
```
In io_uring/io_uring.c (ffffffff816d8c60)
Location: include/linux/sched/signal.h:354
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff816db39f)
Location: include/linux/sched/signal.h:354
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
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
In kernel/signal.c (ffffffff8110547f)
Location: include/linux/sched/signal.h:355
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
```
In io_uring/io_uring.c (ffffffff8178a8e7)
Location: include/linux/sched/signal.h:355
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8179a2d7)
Location: include/linux/sched/signal.h:355
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a59b7)
Location: include/linux/sched/signal.h:355
Inline: True
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
In kernel/signal.c (ffffffff8111170f)
Location: include/linux/sched/signal.h:355
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
```
In io_uring/io_uring.c (ffffffff817cb2d7)
Location: include/linux/sched/signal.h:355
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff817db337)
Location: include/linux/sched/signal.h:355
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e6977)
Location: include/linux/sched/signal.h:355
Inline: True
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
In kernel/signal.c (ffffffff8111b0af)
Location: include/linux/sched/signal.h:347
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
```
In io_uring/io_uring.c (ffffffff8180f87c)
Location: include/linux/sched/signal.h:347
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8181f65c)
Location: include/linux/sched/signal.h:347
Inline: True
```
```
In io_uring/io-wq.c (ffffffff8182c73c)
Location: include/linux/sched/signal.h:347
Inline: True
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
