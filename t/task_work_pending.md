# Function: <code>task_work_pending</code>

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
In kernel/signal.c (ffffffff810e4e14)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_notify
```
```
In kernel/task_work.c (ffffffff810f7875)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
```
```
In kernel/entry/common.c (ffffffff8118a355)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8118a776)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff816d8c44)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__io_uring_show_fdinfo
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff816db3a5)
Location: include/linux/task_work.h:23
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
In kernel/signal.c (ffffffff81105484)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_notify
```
```
In kernel/task_work.c (ffffffff8111a045)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
```
```
In kernel/entry/common.c (ffffffff811c68c5)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811c6d52)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff8178f9ef)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff8179a7b7)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/fdinfo.c (ffffffff8179b753)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/io-wq.c (ffffffff817a5925)
Location: include/linux/task_work.h:23
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
In kernel/signal.c (ffffffff81111714)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_notify
```
```
In kernel/task_work.c (ffffffff811272b5)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
```
```
In kernel/entry/common.c (ffffffff811d94e5)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811d9b63)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff817d1335)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff817db837)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/fdinfo.c (ffffffff817dc878)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/io-wq.c (ffffffff817e68e5)
Location: include/linux/task_work.h:23
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
In kernel/signal.c (ffffffff8111b0b4)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_notify
```
```
In kernel/task_work.c (ffffffff81131895)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
```
```
In kernel/entry/common.c (ffffffff82223fad)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
```
In kernel/entry/kvm.c (ffffffff811ef813)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff818145e2)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff8181fba2)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/fdinfo.c (ffffffff81820a4d)
Location: include/linux/task_work.h:23
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/io-wq.c (ffffffff8182c6a5)
Location: include/linux/task_work.h:23
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
