# Function: <code>resume_user_mode_work</code>

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
In kernel/entry/common.c (ffffffff8118a34f)
Location: include/linux/resume_user_mode.h:40
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8118a769)
Location: include/linux/resume_user_mode.h:40
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
In kernel/entry/common.c (ffffffff811c68bf)
Location: include/linux/resume_user_mode.h:40
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811c6d45)
Location: include/linux/resume_user_mode.h:40
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff8178a895)
Location: include/linux/resume_user_mode.h:40
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8179a285)
Location: include/linux/resume_user_mode.h:40
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a5965)
Location: include/linux/resume_user_mode.h:40
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
In kernel/entry/common.c (ffffffff811d94df)
Location: include/linux/resume_user_mode.h:40
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811d9b56)
Location: include/linux/resume_user_mode.h:40
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff817cb285)
Location: include/linux/resume_user_mode.h:40
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff817db2e5)
Location: include/linux/resume_user_mode.h:40
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e6925)
Location: include/linux/resume_user_mode.h:40
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
In kernel/entry/common.c (ffffffff82223fa7)
Location: include/linux/resume_user_mode.h:41
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
```
In kernel/entry/kvm.c (ffffffff811ef806)
Location: include/linux/resume_user_mode.h:41
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In io_uring/io_uring.c (ffffffff8180f825)
Location: include/linux/resume_user_mode.h:41
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8181f605)
Location: include/linux/resume_user_mode.h:41
Inline: True
```
```
In io_uring/io-wq.c (ffffffff8182c6e5)
Location: include/linux/resume_user_mode.h:41
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
