# Function: <code>timespec64_sub</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110d4b0)
Location: include/linux/time64.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/select.c (ffffffff8128b207)
Location: include/linux/time64.h:76
Inline: True
Inline callers:
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff8178a6ca)
Location: include/linux/time64.h:76
Inline: True
```
```
In net/socket.c (ffffffff8182998c)
Location: include/linux/time64.h:76
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8111919e)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812b1967)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff817cb86c)
Location: include/linux/time64.h:77
Inline: True
```
```
In net/socket.c (ffffffff81873bed)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff81124146)
Location: include/linux/time64.h:78
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812c6a67)
Location: include/linux/time64.h:78
Inline: True
Inline callers:
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff817f2e6c)
Location: include/linux/time64.h:78
Inline: True
```
```
In net/socket.c (ffffffff81892bb9)
Location: include/linux/time64.h:78
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8112e716)
Location: include/linux/time64.h:81
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812e3559)
Location: include/linux/time64.h:81
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff81833aec)
Location: include/linux/time64.h:81
Inline: True
```
```
In net/socket.c (ffffffff818dce9a)
Location: include/linux/time64.h:81
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8113a6c6)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812f4fe9)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff8186545c)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (ffffffff8190db9a)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff81149c59)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff8132d649)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff81938cbc)
Location: include/linux/time64.h:75
Inline: True
```
```
In net/socket.c (ffffffff819e211a)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff81145db9)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff81338f44)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In fs/proc/stat.c (ffffffff813d7348)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
```
In drivers/rtc/class.c (ffffffff8193ee9c)
Location: include/linux/time64.h:75
Inline: True
```
```
In net/socket.c (ffffffff819e1dc2)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff81147076)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff8133f504)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In fs/proc/stat.c (ffffffff813de197)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
```
In drivers/rtc/class.c (ffffffff8192269c)
Location: include/linux/time64.h:75
Inline: True
```
```
In net/socket.c (ffffffff819c7e22)
Location: include/linux/time64.h:75
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8116aa89)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff8138ce94)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In fs/proc/stat.c (ffffffff8142f974)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
```
In drivers/rtc/class.c (ffffffff819c565c)
Location: include/linux/time64.h:77
Inline: True
```
```
In net/socket.c (ffffffff81a77172)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8119e65a)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/select.c (ffffffff8140e1b7)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In fs/proc/stat.c (ffffffff814a960a)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
```
In drivers/rtc/class.c (ffffffff81b25bbd)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
```
```
In net/socket.c (ffffffff81bea47d)
Location: include/linux/time64.h:77
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff811dd23a)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/select.c (ffffffff81498d20)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In fs/proc/stat.c (ffffffff8153f0f3)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
```
In drivers/rtc/class.c (ffffffff81cb91bd)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
```
```
In net/socket.c (ffffffff81d96d2d)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff811f174a)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/select.c (ffffffff814cddb0)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In fs/proc/stat.c (ffffffff81577443)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
```
In drivers/rtc/class.c (ffffffff81d208ed)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
```
```
In net/socket.c (ffffffff81e0539d)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff81207880)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/select.c (ffffffff815006f0)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In fs/proc/stat.c (ffffffff815afd43)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
```
In drivers/rtc/class.c (ffffffff81dd661d)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
```
```
In net/socket.c (ffffffff81ec1c5d)
Location: include/linux/time64.h:80
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffff8000101a4b74)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffff8000103a22b0)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffff800010aa6fe4)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (ffff800010ba4e24)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (c03eeee0)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (c0584e1c)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (c0b85b80)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (c0cc5b6c)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (c0000000002066c0)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (c00000000049bbec)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (c000000000b87a70)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (c000000000c78570)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffe000131132)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffe00026a8c8)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In net/socket.c (ffffffe00073aa26)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff81132e76)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812ed5c9)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff8181810c)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (ffffffff818adb9a)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff811258d6)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812de1f9)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff817df7fc)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (ffffffff81867aea)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff81130b96)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812eb3d9)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff818595ec)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (ffffffff818feb9a)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8113d5b6)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/select.c (ffffffff812fc3c9)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff818746cc)
Location: include/linux/time64.h:83
Inline: True
```
```
In net/socket.c (ffffffff8191fc07)
Location: include/linux/time64.h:83
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
</details>
</li>
</ul>

## Differences
