# Function: <code>ktime_get_boottime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107eb34)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff81092bc7)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/time/hrtimer.c (ffffffff810eeb10)
Location: include/linux/timekeeping.h:188
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff810f0ab6)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/time/alarmtimer.c (ffffffff810face0)
Location: include/linux/timekeeping.h:188
Inline: False
```
```
In kernel/events/core.c (ffffffff81179811)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boot_ns
```
```
In fs/proc/uptime.c (ffffffff8128340d)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff8166d199)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/charger-manager.c (ffffffff816816b4)
Location: include/linux/timekeeping.h:188
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff810eeb10-ffffffff810eeb20: ktime_get_boottime (STB_LOCAL)
ffffffff810face0-ffffffff810facf0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080809)
Location: include/linux/timekeeping.h:204
Inline: True
```
```
In kernel/sys.c (ffffffff81095d57)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810d239c)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff810f5af0)
Location: include/linux/timekeeping.h:204
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff810f7ad6)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/time/alarmtimer.c (ffffffff81101fd0)
Location: include/linux/timekeeping.h:204
Inline: False
```
```
In kernel/events/core.c (ffffffff8118a0b1)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boot_ns
```
```
In fs/proc/uptime.c (ffffffff812b0468)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff816cd4c9)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/charger-manager.c (ffffffff816e24a4)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff810f5af0-ffffffff810f5b00: ktime_get_boottime (STB_LOCAL)
ffffffff81101fd0-ffffffff81101fe0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810850d9)
Location: include/linux/timekeeping.h:204
Inline: True
```
```
In kernel/sys.c (ffffffff8109ad27)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810d8f4c)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff810fcab0)
Location: include/linux/timekeeping.h:204
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811047f0)
Location: include/linux/timekeeping.h:204
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81105476)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/events/core.c (ffffffff811994a1)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boot_ns
```
```
In fs/proc/uptime.c (ffffffff812c5e5d)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff816fb469)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/supply/charger-manager.c (ffffffff81712913)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff810fcab0-ffffffff810fcac0: ktime_get_boottime (STB_LOCAL)
ffffffff811047f0-ffffffff81104800: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81082006)
Location: include/linux/timekeeping.h:193
Inline: True
```
```
In kernel/sys.c (ffffffff81097b29)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810d7f4c)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff810fef10)
Location: include/linux/timekeeping.h:193
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81106bb0)
Location: include/linux/timekeeping.h:193
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81107906)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/events/core.c (ffffffff811a13f1)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boot_ns
```
```
In fs/proc/uptime.c (ffffffff812d3066)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff81710eec)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172acb6)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff810fef10-ffffffff810fef20: ktime_get_boottime (STB_LOCAL)
ffffffff81106bb0-ffffffff81106bc0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088876)
Location: include/linux/timekeeping.h:73
Inline: True
```
```
In kernel/sys.c (ffffffff8109e819)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810e003c)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81109cf0)
Location: include/linux/timekeeping.h:73
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81111c60)
Location: include/linux/timekeeping.h:73
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81112a76)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff8119f9f8)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811b4f71)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boot_ns
```
```
In fs/proc/uptime.c (ffffffff812f785c)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff8178216c)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c456)
Location: include/linux/timekeeping.h:73
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81109cf0-ffffffff81109d00: ktime_get_boottime (STB_LOCAL)
ffffffff81111c60-ffffffff81111c70: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108c5eb)
Location: include/linux/timekeeping.h:78
Inline: True
```
```
In kernel/sys.c (ffffffff810a4087)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810e86f5)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81115810)
Location: include/linux/timekeeping.h:78
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8111d650)
Location: include/linux/timekeeping.h:78
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8111e4d5)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811b5e83)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811d3dd0)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boot_ns
```
```
In fs/proc/uptime.c (ffffffff81324bda)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff817c2e89)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e4cab)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81115810-ffffffff81115820: ktime_get_boottime (STB_LOCAL)
ffffffff8111d650-ffffffff8111d660: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81094a66)
Location: include/linux/timekeeping.h:93
Inline: True
```
```
In kernel/sys.c (ffffffff810ace57)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810f3d05)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81120ee0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81128e00)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81129d25)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811c3ac2)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811e42d0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boot_ns
```
```
In fs/proc/uptime.c (ffffffff8133bd7a)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff817ea3e9)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/supply/charger-manager.c (ffffffff818103bc)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81120ee0-ffffffff81120ef0: ktime_get_boottime (STB_LOCAL)
ffffffff81128e00-ffffffff81128e10: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109921b)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b26a6)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810fc1e5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff8112b660)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81133850)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811347a5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811d5250)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811fb5c0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff81363fb7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/input/evdev.c (ffffffff8182aee9)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851f4a)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (ffffffff81863828)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff8112b660-ffffffff8112b670: ktime_get_boottime (STB_LOCAL)
ffffffff81133850-ffffffff81133860: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f813)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b8d76)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff81108605)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff811377e0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8113f7a0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811407b5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811e1975)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81208970)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff8137c247)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffff81883937)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (ffffffff81895577)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff811377e0-ffffffff811377f0: ktime_get_boottime (STB_LOCAL)
ffffffff8113f7a0-ffffffff8113f7b0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a6924)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810c0eea)
Location: include/linux/timekeeping.h:93
Inline: True
```
```
In kernel/power/process.c (ffffffff81113205)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81146210)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8114e296)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114f6a5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff8115a44c)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff81200302)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff812313f0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff813c5b0b)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffff81952759)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff81965b97)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81146210-ffffffff81146220: ktime_get_boottime (STB_LOCAL)
ffffffff8114e260-ffffffff8114e270: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2401)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bc04a)
Location: include/linux/timekeeping.h:92
Inline: True
```
```
In kernel/power/process.c (ffffffff81110255)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81142730)
Location: include/linux/timekeeping.h:92
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8114a526)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114b925)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811564a5)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff811ff758)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8123b060)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff813d7aab)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffff81c25724)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff8196c667)
Location: include/linux/timekeeping.h:92
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81142730-ffffffff81142740: ktime_get_boottime (STB_LOCAL)
ffffffff8114a4f0-ffffffff8114a500: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a30be)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bd8ca)
Location: include/linux/timekeeping.h:93
Inline: True
```
```
In kernel/power/process.c (ffffffff81110c95)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81143900)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8114b9e6)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8114cdd5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811578a5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff81200103)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8123f820)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff813de961)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffff81c176ab)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff81951627)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81143900-ffffffff81143910: ktime_get_boottime (STB_LOCAL)
ffffffff8114b9b0-ffffffff8114b9c0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b484f)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810d039d)
Location: include/linux/timekeeping.h:93
Inline: True
```
```
In kernel/power/process.c (ffffffff81130775)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81166cf0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8116f6f6)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff81170e15)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff8117c71a)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff81231e26)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8127a040)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff814302b7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d266f0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff819f6b67)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81166cf0-ffffffff81166d00: ktime_get_boottime (STB_LOCAL)
ffffffff8116f6c0-ffffffff8116f6d0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cad41)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810e92dd)
Location: include/linux/timekeeping.h:93
Inline: True
```
```
In kernel/power/process.c (ffffffff81151f75)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff8119a4b0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811a3c06)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811a54a5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811b2008)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff81275116)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff812cd530)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff814a9f5c)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/char/random.c (ffffffff8193481c)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
```
```
In drivers/power/supply/charger-manager.c (ffffffff81ef23fa)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff81b556e7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff8119a4b0-ffffffff8119a4c6: ktime_get_boottime (STB_LOCAL)
ffffffff811a3bc0-ffffffff811a3bd6: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e82d6)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff8110a1ad)
Location: include/linux/timekeeping.h:93
Inline: True
```
```
In kernel/power/process.c (ffffffff81180d96)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff811d8c00)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811e3456)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811e4e85)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff811f2e38)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff812ca5e3)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81335450)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff8153fb02)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/regulator/core.c (ffffffff81a392c8)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/char/random.c (ffffffff81a941bc)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cd95ef)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff81cee7a7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff811d8c00-ffffffff811d8c16: ktime_get_boottime (STB_LOCAL)
ffffffff811e3400-ffffffff811e3416: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f3f35)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff8111647d)
Location: include/linux/timekeeping.h:93
Inline: True
```
```
In kernel/power/process.c (ffffffff81191c86)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff811ed030)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811f7a86)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff811f94e5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff81207605)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff812f1f9d)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff813661a0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff81577e82)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/regulator/core.c (ffffffff81a82ea8)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81adf9dc)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d4185f)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff81d57527)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff811ed030-ffffffff811ed046: ktime_get_boottime (STB_LOCAL)
ffffffff811f7a30-ffffffff811f7a46: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fd2f7)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff8111fe6d)
Location: include/linux/timekeeping.h:94
Inline: True
```
```
In kernel/power/process.c (ffffffff811a0676)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81203260)
Location: include/linux/timekeeping.h:94
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8120dc26)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:get_boottime_timespec
```
```
In kernel/time/posix-timers.c (ffffffff8120f6d5)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
```
```
In kernel/time/namespace.c (ffffffff8121e815)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
```
```
In kernel/bpf/syscall.c (ffffffff81310e13)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8138f2c0)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff815b05e1)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/regulator/core.c (ffffffff81ad5658)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81b32dfc)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df820f)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/md/md.c (ffffffff81e14167)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81203260-ffffffff81203276: ktime_get_boottime (STB_LOCAL)
ffffffff8120dbd0-ffffffff8120dbe6: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3eb0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff8000101144d8)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffff80001016f9e4)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffff8000101a0af8)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffff8000101a8d08)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffff8000101aab80)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffff8000102649c0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffff800010291d68)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffff8000104489f8)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffff800010acf56c)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (ffff800010aeaddc)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffff8000101a0af8-ffff8000101a0b10: ktime_get_boottime (STB_LOCAL)
ffff8000101a8d08-ffff8000101a8d20: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03528a0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c036ea60)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_sysinfo
```
```
In kernel/power/process.c (c03ba5e4)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (c03ea8e8)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (c03f4c94)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (c03f6210)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (c0496bd4)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (c04c2f3c)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (c060db70)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (c0bafe68)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (c0bc36b0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
c03ea8e8-c03ea900: ktime_get_boottime (STB_LOCAL)
c03f4c94-c03f4cac: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013a220)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c00000000015d164)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (c0000000001c79f4)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (c000000000201f20)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (c00000000020cd80)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (c00000000020e7d0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (c0000000003093f0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (c0000000003403c4)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (c00000000055f100)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (c000000000bb2e88)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (c000000000bd62a4)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
c000000000201f20-c000000000201f50: ktime_get_boottime (STB_LOCAL)
c00000000020cd80-c00000000020cdb0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c06b8)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffe0000d217c)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_sysinfo
```
```
In kernel/power/process.c (ffffffe00010dac8)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffe00012e422)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffe000135078)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffe000135ecc)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffe0001a0624)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffe0001c4628)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffe0002de550)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cbfcc)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (ffffffe0006e027e)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffe00012e422-ffffffe00012e43c: ktime_get_boottime (STB_LOCAL)
ffffffe000135078-ffffffe000135092: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099133)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b30e6)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff81101745)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff8112ff90)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81137f50)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81138f65)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811d9f95)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81200f90)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff81374827)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/md/md.c (ffffffff8183b3f7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff8112ff90-ffffffff8112ffa0: ktime_get_boottime (STB_LOCAL)
ffffffff81137f50-ffffffff81137f60: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087b83)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810a1a16)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810f1b05)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff81122a00)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8112a9a0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8112b9b5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811ccd55)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811f3ce0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff813652f7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/md/md.c (ffffffff81802a67)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81122a00-ffffffff81122a10: ktime_get_boottime (STB_LOCAL)
ffffffff8112a9a0-ffffffff8112a9b0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810990e3)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b2646)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff810fead5)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff8112dcb0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81135c70)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81136c85)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811d7d65)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811fed60)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff813722f7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffff81878de7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (ffffffff8188aa27)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff8112dcb0-ffffffff8112dcc0: ktime_get_boottime (STB_LOCAL)
ffffffff81135c70-ffffffff81135c80: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_boottime();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0d1c)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bac46)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/sys.c:do_sysinfo
```
```
In kernel/power/process.c (ffffffff81109d95)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/time/hrtimer.c (ffffffff8113a600)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811426c0)
Location: include/linux/timekeeping.h:93
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81143715)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_boottime
```
```
In kernel/bpf/syscall.c (ffffffff811e6105)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8120ddf0)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_boottime_ns
```
```
In fs/proc/uptime.c (ffffffff81385cd7)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - fs/proc/uptime.c:uptime_proc_show
```
```
In drivers/power/supply/charger-manager.c (ffffffff81894787)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/md/md.c (ffffffff818a1067)
Location: include/linux/timekeeping.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff8113a600-ffffffff8113a610: ktime_get_boottime (STB_LOCAL)
ffffffff811426c0-ffffffff811426d0: ktime_get_boottime (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
