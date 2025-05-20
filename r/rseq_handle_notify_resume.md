# Function: <code>rseq_handle_notify_resume</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003faf)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff8102d6c3)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/entry/common.c (ffffffff81003d14)
Location: include/linux/sched.h:1817
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff8102e90d)
Location: include/linux/sched.h:1817
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/entry/common.c (ffffffff8100414a)
Location: include/linux/sched.h:1890
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff81030baa)
Location: include/linux/sched.h:1890
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/entry/common.c (ffffffff8100414a)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff81031032)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/entry/common.c (ffffffff810050d9)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff81033976)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
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
In arch/x86/kernel/signal.c (ffffffff810343e6)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
```
```
In kernel/entry/common.c (ffffffff8113ba8c)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
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
In arch/x86/kernel/signal.c (ffffffff81035ef8)
Location: include/linux/sched.h:2074
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/entry/common.c (ffffffff8113cd5c)
Location: include/linux/sched.h:2074
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
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
In arch/x86/kernel/signal.c (ffffffff8103b179)
Location: include/linux/sched.h:2193
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/entry/common.c (ffffffff8115fe7c)
Location: include/linux/sched.h:2193
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811602d0)
Location: include/linux/sched.h:2193
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
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
In arch/x86/kernel/signal.c (ffffffff8104210f)
Location: include/linux/sched.h:2289
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/entry/common.c (ffffffff8118a377)
Location: include/linux/sched.h:2289
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8118a79f)
Location: include/linux/sched.h:2289
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
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
In arch/x86/kernel/signal.c (ffffffff8104b1ab)
Location: include/linux/sched.h:2317
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/entry/common.c (ffffffff811c68e7)
Location: include/linux/sched.h:2317
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811c6d7b)
Location: include/linux/sched.h:2317
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff8178a8c2)
Location: include/linux/sched.h:2317
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8179a2b2)
Location: include/linux/sched.h:2317
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a5992)
Location: include/linux/sched.h:2317
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
In arch/x86/kernel/signal.c (ffffffff8104ba4b)
Location: include/linux/sched.h:2334
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/entry/common.c (ffffffff811d9507)
Location: include/linux/sched.h:2334
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811d9b8c)
Location: include/linux/sched.h:2334
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff817cb2b2)
Location: include/linux/sched.h:2334
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff817db312)
Location: include/linux/sched.h:2334
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e6952)
Location: include/linux/sched.h:2334
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
In arch/x86/kernel/signal.c (ffffffff81052ccb)
Location: include/linux/rseq.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/entry/common.c (ffffffff82223fd8)
Location: include/linux/rseq.h:34
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
```
In kernel/entry/kvm.c (ffffffff811ef841)
Location: include/linux/rseq.h:34
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff8180f857)
Location: include/linux/rseq.h:34
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8181f637)
Location: include/linux/rseq.h:34
Inline: True
```
```
In io_uring/io-wq.c (ffffffff8182c717)
Location: include/linux/rseq.h:34
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/signal.c (ffff80001009350c)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/signal.c (c030e830)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/signal.c (c0000000000238c4)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/entry/common.c (ffffffff8100414a)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff81031192)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/entry/common.c (ffffffff8100240f)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff81020bb2)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/entry/common.c (ffffffff81004137)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff81030ff2)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/entry/common.c (ffffffff8100422a)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
```
In arch/x86/kernel/signal.c (ffffffff81031e96)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
</ul>

## Differences
