# Function: <code>timespec_sub</code>

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
In kernel/time/timekeeping.c (ffffffff810f4e0f)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
```
```
In fs/select.c (ffffffff81220d3b)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - fs/select.c:poll_select_copy_remaining
```
```
In fs/compat.c (ffffffff81263e2b)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - fs/compat.c:poll_select_copy_remaining
```
```
In drivers/rtc/class.c (ffffffff81673630)
Location: include/linux/time.h:80
Inline: True
```
```
In net/socket.c (ffffffff816ff876)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff810fd54c)
Location: include/linux/time.h:80
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
In fs/select.c (ffffffff81248997)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - fs/select.c:poll_select_copy_remaining
```
```
In fs/compat.c (ffffffff8128ff8f)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - fs/compat.c:poll_select_copy_remaining
```
```
In drivers/rtc/class.c (ffffffff816d3e38)
Location: include/linux/time.h:80
Inline: True
```
```
In net/socket.c (ffffffff81766318)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8110033c)
Location: include/linux/time.h:80
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
In fs/select.c (ffffffff8125b9c7)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - fs/select.c:poll_select_copy_remaining
```
```
In fs/compat.c (ffffffff812a4fcf)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - fs/compat.c:poll_select_copy_remaining
```
```
In drivers/rtc/class.c (ffffffff81703b18)
Location: include/linux/time.h:80
Inline: True
```
```
In net/socket.c (ffffffff81793398)
Location: include/linux/time.h:80
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
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
In kernel/time/timekeeping.c (ffffffff8110250d)
Location: include/linux/time.h:89
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
In fs/select.c (ffffffff81268953)
Location: include/linux/time.h:89
Inline: True
Inline callers:
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
```
```
In drivers/rtc/class.c (ffffffff8171946a)
Location: include/linux/time.h:89
Inline: True
```
```
In net/socket.c (ffffffff817b17ec)
Location: include/linux/time.h:89
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
```
</details>
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
