# Function: <code>task_pgrp</code>

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
In kernel/fork.c (ffffffff8107f2ee)
Location: include/linux/sched.h:1887
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810820f8)
Location: include/linux/sched.h:1887
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/signal.c (ffffffff8108f9b9)
Location: include/linux/sched.h:1887
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff810939c6)
Location: include/linux/sched.h:1887
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_getpgrp
```
```
In block/ioprio.c (ffffffff813cdd0a)
Location: include/linux/sched.h:1887
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff814e0182)
Location: include/linux/sched.h:1887
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810814a4)
Location: include/linux/sched.h:2026
Inline: True
```
```
In kernel/exit.c (ffffffff810851ad)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff81092a39)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff81097fef)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In block/ioprio.c (ffffffff8141253e)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In drivers/tty/tty_io.c (ffffffff81532574)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__proc_set_tty
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
In kernel/fork.c (ffffffff81085ef2)
Location: include/linux/sched.h:2113
Inline: True
```
```
In kernel/exit.c (ffffffff8108a11d)
Location: include/linux/sched.h:2113
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810979c9)
Location: include/linux/sched.h:2113
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff8109cf9f)
Location: include/linux/sched.h:2113
Inline: True
Inline callers:
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In block/ioprio.c (ffffffff8142d99e)
Location: include/linux/sched.h:2113
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In drivers/tty/tty_io.c (ffffffff8155eca4)
Location: include/linux/sched.h:2113
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__proc_set_tty
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
In kernel/fork.c (ffffffff8108291a)
Location: include/linux/sched.h:1123
Inline: True
```
```
In kernel/exit.c (ffffffff8108724d)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff81094cbc)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff81099e7f)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In block/ioprio.c (ffffffff8143ace0)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157cd74)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108974a)
Location: include/linux/sched.h:1123
Inline: True
```
```
In kernel/exit.c (ffffffff8108dfbd)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109bb5d)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
```
In kernel/sys.c (ffffffff810a0b5f)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In block/ioprio.c (ffffffff81466d00)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e19e4)
Location: include/linux/sched.h:1123
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff8108d106)
Location: include/linux/sched.h:1215
Inline: True
```
```
In kernel/exit.c (ffffffff81091a75)
Location: include/linux/sched.h:1215
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109fbd8)
Location: include/linux/sched.h:1215
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_kill
```
```
In kernel/sys.c (ffffffff810a747b)
Location: include/linux/sched.h:1215
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff8149a1cd)
Location: include/linux/sched.h:1215
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161aca4)
Location: include/linux/sched.h:1215
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff81094e2c)
Location: include/linux/sched/signal.h:591
Inline: True
```
```
In kernel/exit.c (ffffffff81099d55)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810a7e34)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b018b)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff814b44dd)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81637f14)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff81099485)
Location: include/linux/sched/signal.h:622
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e365)
Location: include/linux/sched/signal.h:622
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810adae7)
Location: include/linux/sched/signal.h:622
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b5b59)
Location: include/linux/sched/signal.h:622
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff814e29fd)
Location: include/linux/sched/signal.h:622
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166c1f4)
Location: include/linux/sched/signal.h:622
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff8109fa7f)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a48c5)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b4107)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bc149)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff814fbdbd)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168e864)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810a6b21)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810abc65)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810bd3e7)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810c3ae9)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff8155ba45)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740b76)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810a2633)
Location: include/linux/sched/signal.h:650
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a7265)
Location: include/linux/sched/signal.h:650
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b86e7)
Location: include/linux/sched/signal.h:650
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810beed9)
Location: include/linux/sched/signal.h:650
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff81577bad)
Location: include/linux/sched/signal.h:650
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175caa6)
Location: include/linux/sched/signal.h:650
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810a3326)
Location: include/linux/sched/signal.h:656
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a82f5)
Location: include/linux/sched/signal.h:656
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b9c67)
Location: include/linux/sched/signal.h:656
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810c0869)
Location: include/linux/sched/signal.h:656
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff8157f8ed)
Location: include/linux/sched/signal.h:656
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740936)
Location: include/linux/sched/signal.h:656
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810b4ab1)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810b9d55)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810cc277)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810d3359)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff815e4b8d)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c1396)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810caf7d)
Location: include/linux/sched/signal.h:694
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810d0875)
Location: include/linux/sched/signal.h:694
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810e34a4)
Location: include/linux/sched/signal.h:694
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810ec97b)
Location: include/linux/sched/signal.h:694
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff81693b74)
Location: include/linux/sched/signal.h:694
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818fdd66)
Location: include/linux/sched/signal.h:694
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810e852a)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ef205)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff81103a14)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff8110dcfb)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff81752ba0)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81a57516)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810f4189)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810fb225)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8110fc54)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff81119f8b)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff8178eef9)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81aa1b16)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810fd54b)
Location: include/linux/sched/signal.h:687
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff811046d5)
Location: include/linux/sched/signal.h:687
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff811195c4)
Location: include/linux/sched/signal.h:687
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff8112397b)
Location: include/linux/sched/signal.h:687
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In block/ioprio.c (ffffffff817d1800)
Location: include/linux/sched/signal.h:687
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81af4576)
Location: include/linux/sched/signal.h:687
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffff8000100f4024)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fa4f8)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffff800010110258)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_kill
```
```
In kernel/sys.c (ffff800010118bf0)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_getpgrp
  - kernel/sys.c:__arm64_sys_getpgid
  - kernel/sys.c:__arm64_sys_getpgid
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
```
```
In block/ioprio.c (ffff8000105fde28)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffff80001085ff94)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (c0352aa0)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c03584e4)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c0369634)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
```
```
In kernel/sys.c (c036d250)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In block/ioprio.c (c07a9020)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (c0966edc)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (c00000000013a3f0)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c000000000141888)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c0000000001579d0)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
```
```
In kernel/sys.c (c000000000160694)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:__se_sys_getpgid
  - kernel/sys.c:__se_sys_getpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In block/ioprio.c (c00000000079791c)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (c0000000008ff1f0)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffe0000c07f6)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c45b4)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffe0000d164a)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
```
```
In kernel/sys.c (ffffffe0000d3f88)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getpgid
  - kernel/sys.c:__se_sys_getpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In block/ioprio.c (ffffffe000439a9e)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffe000537ee2)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff8109939f)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e1e5)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ae477)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b64b9)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff814f439d)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816542e4)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff81087def)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108cbf5)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109cdc7)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810a4df9)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff814e48ad)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816346c4)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff8109934f)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e195)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ad9d7)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b5a19)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff814f042d)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816826a4)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810a0f88)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a6095)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b5c27)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bdd89)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In block/ioprio.c (ffffffff815094da)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8169cd04)
Location: include/linux/sched/signal.h:614
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
</details>
</li>
</ul>

## Differences
