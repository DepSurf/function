# Function: <code>idr_set_cursor</code>

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
In kernel/pid.c (ffffffff810aa0cc)
Location: include/linux/idr.h:61
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff8113f504)
Location: include/linux/idr.h:61
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
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
In kernel/pid.c (ffffffff810b0cfa)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff8114de44)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e7c53)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810b9df6)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff8115ab14)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fc883)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810bfcea)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff811671c4)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131d247)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810c60ba)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81173084)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81330087)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810cdf02)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81184e84)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8136a013)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810c89e2)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81181e83)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81377338)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810ca482)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81182fd3)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d748)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810dd2d2)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff811ab083)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca685)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810f6bc9)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff811dc7bc)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451775)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff811192a9)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff812220dc)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0285)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff81126779)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff8123858c)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516b40)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff81130d69)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff8125225c)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154af30)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffff8000101248e8)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffff8000101e7480)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ecc68)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (c03778b0)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (c042794c)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (c05c2c04)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (c00000000016e4e0)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (c000000000257ef8)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3c68)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffe0000dc7dc)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffe00015c966)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a07e0)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810c043a)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff8116b6a4)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81328667)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810aec44)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff8115e8a4)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81319207)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810bf98a)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81169474)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81326137)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
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
In kernel/pid.c (ffffffff810c7dc0)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81176b64)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337045)
Location: include/linux/idr.h:79
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
```
</details>
</li>
</ul>

## Differences
