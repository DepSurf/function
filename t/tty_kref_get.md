# Function: <code>tty_kref_get</code>

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
In kernel/fork.c (ffffffff8107f35d)
Location: include/linux/tty.h:415
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In drivers/tty/tty_io.c (ffffffff814e0ac8)
Location: include/linux/tty.h:415
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/tty/tty_port.c (ffffffff814eb325)
Location: include/linux/tty.h:415
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff818243b5)
Location: include/linux/tty.h:415
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
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
In kernel/fork.c (ffffffff81081513)
Location: include/linux/tty.h:436
Inline: True
```
```
In kernel/audit.c (ffffffff8112a89a)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff815352a9)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
```
```
In drivers/tty/tty_port.c (ffffffff8153c1a5)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8153cb59)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
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
In kernel/fork.c (ffffffff81085f5d)
Location: include/linux/tty.h:436
Inline: True
```
```
In kernel/audit.c (ffffffff811345ba)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff815619cd)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
```
```
In drivers/tty/tty_port.c (ffffffff81568805)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff815691a9)
Location: include/linux/tty.h:436
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
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
In kernel/fork.c (ffffffff81082989)
Location: include/linux/tty.h:447
Inline: True
```
```
In kernel/audit.c (ffffffff81135a66)
Location: include/linux/tty.h:447
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81575337)
Location: include/linux/tty.h:447
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
```
```
In drivers/tty/tty_port.c (ffffffff8157bae5)
Location: include/linux/tty.h:447
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8157c739)
Location: include/linux/tty.h:447
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157ccb4)
Location: include/linux/tty.h:447
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810897b5)
Location: include/linux/tty.h:453
Inline: True
```
```
In kernel/audit.c (ffffffff811427a6)
Location: include/linux/tty.h:453
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff815d9c91)
Location: include/linux/tty.h:453
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff815e0475)
Location: include/linux/tty.h:453
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff815e1239)
Location: include/linux/tty.h:453
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e1964)
Location: include/linux/tty.h:453
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff8108d163)
Location: include/linux/tty.h:455
Inline: True
```
```
In kernel/audit.c (ffffffff81151185)
Location: include/linux/tty.h:455
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81612cc2)
Location: include/linux/tty.h:455
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff81619735)
Location: include/linux/tty.h:455
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8161a4c9)
Location: include/linux/tty.h:455
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161ac24)
Location: include/linux/tty.h:455
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff81094e97)
Location: include/linux/tty.h:462
Inline: True
```
```
In kernel/audit.c (ffffffff8115de39)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff8162fd62)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff816369a5)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81637749)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81637e94)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810994f4)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff8116a169)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81663b85)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff8166abf5)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8166ba1a)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166c133)
Location: include/linux/tty.h:462
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff8109faee)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff81176009)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff816861f5)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff8168d2c5)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8168e08a)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168e7a3)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810a6b8c)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff8118858b)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81737dc1)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff8173fa5c)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8174031a)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740ad5)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810a26ae)
Location: include/linux/tty.h:468
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff811858db)
Location: include/linux/tty.h:468
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81754181)
Location: include/linux/tty.h:468
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff8175b8dc)
Location: include/linux/tty.h:468
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8175c24a)
Location: include/linux/tty.h:468
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175ca05)
Location: include/linux/tty.h:468
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810a33a0)
Location: include/linux/tty.h:426
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff811868cb)
Location: include/linux/tty.h:426
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff8173822e)
Location: include/linux/tty.h:426
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff8173f77c)
Location: include/linux/tty.h:426
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff817400ea)
Location: include/linux/tty.h:426
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740895)
Location: include/linux/tty.h:426
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810b4b2d)
Location: include/linux/tty.h:312
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff811aecfb)
Location: include/linux/tty.h:312
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff817b8cce)
Location: include/linux/tty.h:312
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff817bffdc)
Location: include/linux/tty.h:312
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff817c088a)
Location: include/linux/tty.h:312
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c12f5)
Location: include/linux/tty.h:312
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810caff9)
Location: include/linux/tty.h:407
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff811e0f37)
Location: include/linux/tty.h:407
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff818f4c8e)
Location: include/linux/tty.h:407
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff818fc71a)
Location: include/linux/tty.h:407
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff818fd0e9)
Location: include/linux/tty.h:407
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818fdcb2)
Location: include/linux/tty.h:407
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
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
In kernel/fork.c (ffffffff810e85a6)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff81226d77)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81a4d2b9)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff81a55d5a)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81a56795)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81a57452)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810f4205)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff8123d397)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81a975b7)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff81aa033a)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81aa0d75)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81aa1a52)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810fd5c7)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff812572c7)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81ae9ff6)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff81af2d8a)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81af37d5)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81af44b2)
Location: include/linux/tty.h:401
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffff8000100f4070)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffff8000101eb074)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffff800010853bd0)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffff80001085e4b4)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffff80001085f290)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffff80001085fcf0)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (c0352b10)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (c042ac8c)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (c095e658)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (c0965cd0)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (c0966760)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (c0967090)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (c00000000013a440)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (c00000000025c614)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (c0000000008f3130)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (c0000000008fd1c4)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (c0000000008fe7d4)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (c0000000008ff0cc)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffe0000c0836)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffe00015f93e)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffe00053043e)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffe0005369ee)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffe00053778e)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffe000537e30)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff8109940e)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff8116e629)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff8164bc75)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff81652d45)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81653b0a)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654223)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff81087e5e)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff811617c9)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff8162c0c5)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff81633185)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81633eea)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81634603)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810993be)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff8116c3f9)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff8167a035)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff81681105)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81681eca)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816825e3)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
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
In kernel/fork.c (ffffffff810a0ff7)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/audit.c (ffffffff81179bb9)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In drivers/tty/tty_io.c (ffffffff81694695)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffff8169b755)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8169c50a)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8169cc43)
Location: include/linux/tty.h:464
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
</details>
</li>
</ul>

## Differences
