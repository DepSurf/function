# Function: <code>task_session</code>

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
In kernel/fork.c (ffffffff8107f304)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81082108)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8108d06d)
Location: include/linux/sched.h:1892
Inline: True
```
```
In kernel/sys.c (ffffffff81094c68)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:sys_setsid
```
```
In drivers/tty/tty_io.c (ffffffff814e0c35)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
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
In kernel/fork.c (ffffffff810814ba)
Location: include/linux/sched.h:2031
Inline: True
```
```
In kernel/exit.c (ffffffff81085171)
Location: include/linux/sched.h:2031
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff81090235)
Location: include/linux/sched.h:2031
Inline: True
```
```
In kernel/sys.c (ffffffff81098132)
Location: include/linux/sched.h:2031
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
```
```
In drivers/tty/tty_io.c (ffffffff81534226)
Location: include/linux/sched.h:2031
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
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
In kernel/fork.c (ffffffff81085f07)
Location: include/linux/sched.h:2118
Inline: True
```
```
In kernel/exit.c (ffffffff8108a0e1)
Location: include/linux/sched.h:2118
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810951b5)
Location: include/linux/sched.h:2118
Inline: True
```
```
In kernel/sys.c (ffffffff8109d0e2)
Location: include/linux/sched.h:2118
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
```
```
In drivers/tty/tty_io.c (ffffffff81560951)
Location: include/linux/sched.h:2118
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
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
In kernel/fork.c (ffffffff81082930)
Location: include/linux/sched.h:1128
Inline: True
```
```
In kernel/exit.c (ffffffff81087206)
Location: include/linux/sched.h:1128
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109222a)
Location: include/linux/sched.h:1128
Inline: True
```
```
In kernel/sys.c (ffffffff81099fc2)
Location: include/linux/sched.h:1128
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157d6ac)
Location: include/linux/sched.h:1128
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff8108975f)
Location: include/linux/sched.h:1128
Inline: True
```
```
In kernel/exit.c (ffffffff8108df66)
Location: include/linux/sched.h:1128
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810990ba)
Location: include/linux/sched.h:1128
Inline: True
```
```
In kernel/sys.c (ffffffff810a0ca2)
Location: include/linux/sched.h:1128
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e21d1)
Location: include/linux/sched.h:1128
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff8108d11b)
Location: include/linux/sched.h:1220
Inline: True
```
```
In kernel/exit.c (ffffffff81091a9f)
Location: include/linux/sched.h:1220
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8109c8d9)
Location: include/linux/sched.h:1220
Inline: True
```
```
In kernel/sys.c (ffffffff810a7454)
Location: include/linux/sched.h:1220
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161b481)
Location: include/linux/sched.h:1220
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff81094e48)
Location: include/linux/sched/signal.h:596
Inline: True
```
```
In kernel/exit.c (ffffffff81099d7f)
Location: include/linux/sched/signal.h:596
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810a4bbe)
Location: include/linux/sched/signal.h:596
Inline: True
```
```
In kernel/sys.c (ffffffff810b0164)
Location: include/linux/sched/signal.h:596
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816387d2)
Location: include/linux/sched/signal.h:596
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810994a2)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e390)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810a98a9)
Location: include/linux/sched/signal.h:627
Inline: True
```
```
In kernel/sys.c (ffffffff810b5b32)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166ca41)
Location: include/linux/sched/signal.h:627
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff8109fa9c)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a48f0)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810afe39)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (ffffffff810bc122)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168f0b1)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810a6b3d)
Location: include/linux/sched/signal.h:642
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810abc90)
Location: include/linux/sched/signal.h:642
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b7899)
Location: include/linux/sched/signal.h:642
Inline: True
```
```
In kernel/sys.c (ffffffff810c3ac2)
Location: include/linux/sched/signal.h:642
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740dd1)
Location: include/linux/sched/signal.h:642
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocspgrp
  - drivers/tty/tty_jobctrl.c:tiocspgrp
  - drivers/tty/tty_jobctrl.c:tiocspgrp
  - drivers/tty/tty_jobctrl.c:tiocsctty
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
In kernel/fork.c (ffffffff810a264f)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a7290)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b2b29)
Location: include/linux/sched/signal.h:655
Inline: True
```
```
In kernel/sys.c (ffffffff810beeb2)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175d052)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
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
In kernel/fork.c (ffffffff810a3342)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a8320)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b4169)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In kernel/sys.c (ffffffff810c0842)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174139b)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810b4acd)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810b9d80)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810c6429)
Location: include/linux/sched/signal.h:659
Inline: True
```
```
In kernel/sys.c (ffffffff810d3332)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c1dfb)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810caf99)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810d089f)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810ddd73)
Location: include/linux/sched/signal.h:699
Inline: True
```
```
In kernel/sys.c (ffffffff810ec954)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818fe871)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810e8546)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ef22f)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810fe1d3)
Location: include/linux/sched/signal.h:700
Inline: True
```
```
In kernel/sys.c (ffffffff8110dcd4)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81a580b1)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810f41a5)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810fb24f)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff8110a293)
Location: include/linux/sched/signal.h:700
Inline: True
```
```
In kernel/sys.c (ffffffff81119f64)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81aa268e)
Location: include/linux/sched/signal.h:700
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810fd567)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff811046ff)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff81113c33)
Location: include/linux/sched/signal.h:692
Inline: True
```
```
In kernel/sys.c (ffffffff81123954)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81af506e)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffff8000100f4034)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fa518)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffff80001010abac)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (ffff800010118bcc)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_getsid
  - kernel/sys.c:__arm64_sys_getsid
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860bc0)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (c0352ab4)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0358508)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c0364338)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (c036d22c)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (c0967a10)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (c00000000013a400)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0000000001418ac)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (c000000000152690)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (c00000000016066c)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (c0000000008ffe84)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffe0000c0806)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c45cc)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffe0000cd9d6)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (ffffffe0000d3f6a)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffe0005387d2)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810993bc)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e210)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810aa1a9)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (ffffffff810b6492)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654b31)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff81087e0c)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108cc20)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff81098bb9)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (ffffffff810a4dd2)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81634f01)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff8109936c)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109e1c0)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810a9709)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (ffffffff810b59f2)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81682ef1)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
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
In kernel/fork.c (ffffffff810a0fa5)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a60c0)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:kill_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/signal.c (ffffffff810b1a29)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sys.c (ffffffff810bdd62)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8169d536)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
</details>
</li>
</ul>

## Differences
