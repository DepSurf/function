# Function: <code>checkpoint_restore_ns_capable</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bdb44)
Location: include/linux/capability.h:264
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/pid.c (ffffffff810c889a)
Location: include/linux/capability.h:264
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81181e36)
Location: include/linux/capability.h:264
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/proc/base.c (ffffffff813ce5f5)
Location: include/linux/capability.h:264
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
In kernel/sys.c (ffffffff810bec94)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/pid.c (ffffffff810ca33a)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81182f86)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/proc/base.c (ffffffff813d5275)
Location: include/linux/capability.h:267
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
In kernel/sys.c (ffffffff810d0c94)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/pid.c (ffffffff810dd18a)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff811ab036)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/proc/base.c (ffffffff81426bb5)
Location: include/linux/capability.h:267
Inline: True
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
In kernel/sys.c (ffffffff810ea1ae)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/pid.c (ffffffff810f6a7b)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff811dc775)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/proc/base.c (ffffffff814a0e15)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_get_link
```
```
In ipc/ipc_sysctl.c (ffffffff8159f3b5)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:ipc_permissions
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
In kernel/sys.c (ffffffff8110ac9e)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/pid.c (ffffffff8111915b)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81222095)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/proc/base.c (ffffffff81535df5)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_get_link
```
```
In ipc/ipc_sysctl.c (ffffffff81648b85)
Location: include/linux/capability.h:267
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:ipc_permissions
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
In kernel/sys.c (ffffffff81116e5e)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/pid.c (ffffffff8112662b)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81238545)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/proc/base.c (ffffffff8156dfc5)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_get_link
```
```
In ipc/ipc_sysctl.c (ffffffff816810e3)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:ipc_permissions
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
In kernel/sys.c (ffffffff8112084e)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/pid.c (ffffffff81130c1b)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/pid_namespace.c (ffffffff81252215)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pid_ns_ctl_handler
```
```
In fs/proc/base.c (ffffffff815a6955)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_get_link
```
```
In ipc/ipc_sysctl.c (ffffffff816bd503)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:ipc_permissions
```
```
In drivers/tty/tty_ioctl.c (ffffffff81aefd7b)
Location: include/linux/capability.h:205
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
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
