# Function: <code>pid_has_task</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3b3c)
Location: include/linux/pid.h:90
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff810ad49d)
Location: include/linux/pid.h:90
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/pid.c (ffffffff810cd738)
Location: include/linux/pid.h:90
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152788)
Location: include/linux/pid.h:90
Inline: True
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
In kernel/fork.c (ffffffff8109f28c)
Location: include/linux/pid.h:91
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff810a8b6d)
Location: include/linux/pid.h:91
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/pid.c (ffffffff810c827f)
Location: include/linux/pid.h:91
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114e9d8)
Location: include/linux/pid.h:91
Inline: True
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
In kernel/fork.c (ffffffff810a015c)
Location: include/linux/pid.h:91
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff810a9b6d)
Location: include/linux/pid.h:91
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/pid.c (ffffffff810c9da4)
Location: include/linux/pid.h:91
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fe71)
Location: include/linux/pid.h:91
Inline: True
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
In kernel/fork.c (ffffffff810b156c)
Location: include/linux/pid.h:92
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff810bb69d)
Location: include/linux/pid.h:92
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/pid.c (ffffffff810dd999)
Location: include/linux/pid.h:92
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811740a1)
Location: include/linux/pid.h:92
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813ccd82)
Location: include/linux/pid.h:92
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In kernel/fork.c (ffffffff810c787c)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff810d20dd)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/pid.c (ffffffff810f7458)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8d9f)
Location: include/linux/pid.h:93
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814559c0)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In kernel/fork.c (ffffffff810e43ec)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff810f0b51)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/pid.c (ffffffff81119bc8)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e8bef)
Location: include/linux/pid.h:93
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4940)
Location: include/linux/pid.h:93
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In kernel/fork.c (ffffffff810f30fa)
Location: include/linux/pid.h:94
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_prepare
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff810fcb01)
Location: include/linux/pid.h:94
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/pid.c (ffffffff811264af)
Location: include/linux/pid.h:94
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd1fd)
Location: include/linux/pid.h:94
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b76e)
Location: include/linux/pid.h:94
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In kernel/fork.c (ffffffff810fc4aa)
Location: include/linux/pid.h:88
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_prepare
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In kernel/exit.c (ffffffff81106f14)
Location: include/linux/pid.h:88
Inline: True
Inline callers:
  - kernel/exit.c:__do_wait
```
```
In kernel/pid.c (ffffffff81130ab7)
Location: include/linux/pid.h:88
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812133fd)
Location: include/linux/pid.h:88
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154fd6e)
Location: include/linux/pid.h:88
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
