# Function: <code>tty_kref_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0a60)
Location: drivers/tty/tty_io.c:1665
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:proc_clear_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
Direct callers:
  - kernel/exit.c:release_task
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff814e0a60-ffffffff814e0a85: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81534fef)
Location: drivers/tty/tty_io.c:1667
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:proc_clear_tty
Direct callers:
  - kernel/exit.c:release_task
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81532170-ffffffff81532195: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8156171e)
Location: drivers/tty/tty_io.c:1667
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:proc_clear_tty
Direct callers:
  - kernel/exit.c:release_task
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8155e8a0-ffffffff8155e8c5: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81571e20)
Location: drivers/tty/tty_io.c:1435
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81571e20-ffffffff81571e81: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d9b0d)
Location: drivers/tty/tty_io.c:1453
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff815d8750-ffffffff815d877a: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81612a8d)
Location: drivers/tty/tty_io.c:1471
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81610940-ffffffff8161096b: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162fb2d)
Location: drivers/tty/tty_io.c:1483
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8162da70-ffffffff8162da9b: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81663a2f)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81661620-ffffffff81661649: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8168609f)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81683c70-ffffffff81683c99: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81738102)
Location: drivers/tty/tty_io.c:1489
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81735300-ffffffff81735382: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817544be)
Location: drivers/tty/tty_io.c:1570
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff817514b0-ffffffff81751532: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8173807d)
Location: drivers/tty/tty_io.c:1585
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81735340-ffffffff817353c2: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b8b1d)
Location: drivers/tty/tty_io.c:1578
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff817b5d00-ffffffff817b5d82: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f4ae7)
Location: drivers/tty/tty_io.c:1567
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff818f1810-ffffffff818f18c2: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4d117)
Location: drivers/tty/tty_io.c:1562
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81a498a0-ffffffff81a4994a: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a97417)
Location: drivers/tty/tty_io.c:1571
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81a93ad0-ffffffff81a93b7a: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae9e56)
Location: drivers/tty/tty_io.c:1569
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81ae6540-ffffffff81ae65ea: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010853c9c)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffff80001084f2e0-ffff80001084f348: tty_kref_put.part.0 (STB_LOCAL)
ffff80001084f348-ffff80001084f378: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (c095e538)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
c095b5d8-c095b63c: tty_kref_put.part.0 (STB_LOCAL)
c095b63c-c095b660: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ed9b0)
Location: drivers/tty/tty_io.c:1485
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_close
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_close
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
c0000000008ed9b0-c0000000008eda54: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe0005302f4)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffe00052cf24-ffffffe00052cf6a: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164bb1f)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff816496f0-ffffffff81649719: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162bf6f)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81629b50-ffffffff81629b79: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81679edf)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81677ab0-ffffffff81677ad9: tty_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_kref_put(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8169453f)
Location: drivers/tty/tty_io.c:1485
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - kernel/exit.c:release_task
  - kernel/audit.c:audit_set_loginuid
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/tty_mutex.c:tty_unlock
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81692f50-ffffffff81692f79: tty_kref_put (STB_GLOBAL)
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
